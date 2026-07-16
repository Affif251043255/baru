# R Code for Process Capability Analysis for PartLength
library(qcc)
current_data <- get("X002..2.")
filtered_data_pc <- current_data[current_data$Machine == 3 & current_data$Temperature == 338 & current_data$Pressure == 300, ]
data_for_pc <- na.omit(as.numeric(filtered_data_pc[['PartLength']]))
if (length(data_for_pc) > 0) {
  # !!! IMPORTANT: Replace these with actual engineering specifications !!!
  LSL <- 48 # Lower Specification Limit
  USL <- 52 # Upper Specification Limit
  Target <- 50 # Target Value
  
  # Create a qcc object first
  qcc_obj <- qcc(data_for_pc, type='xbar.one', plot=FALSE)
  
  # Generate Process Capability chart using the qcc object
  png('media/plots/process_capability_partlength_m3_t338_p300.png', width=1000, height=600)
  process.capability(qcc_obj, spec.limits=c(LSL, USL), target=Target,
                       nsigmas=3)
  dev.off()
  
  cat('\n--- Process Capability Metrics for PartLength (M:3, T:338, P:300) ---\n')
  pc_summary <- process.capability(qcc_obj, spec.limits=c(LSL, USL), target=Target)
  print(pc_summary)
  cat('WARNING: The LSL, USL, and Target values used here (', LSL_val, ', ', USL_val, ', ', Target_val, ') are assumptions for demonstration. \n')
  cat('         For a meaningful analysis, please replace them with actual engineering specifications.\n')
} else {
  cat('Not enough valid numeric data for Process Capability for PartLength (M:3, T:338, P:300).\n')
}

