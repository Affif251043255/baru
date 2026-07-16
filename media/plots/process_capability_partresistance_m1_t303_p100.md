library(qcc)
data_for_pc <- na.omit(as.numeric(get('X002..2.')[get('X002..2.')$Machine == 1 & get('X002..2.')$Temperature == 303 & get('X002..2.')$Pressure == 100, ][['PartResistance']]))
if (length(data_for_pc) > 0) {
  LSL <- 0.5
  USL <- 6.5
  Target <- 3.5
  qcc_obj <- qcc(data_for_pc, type='xbar.one', plot=FALSE)
  png('media/plots/process_capability_partresistance_m1_t303_p100.png', width=1000, height=600)
  process.capability(qcc_obj, spec.limits=c(LSL, USL), target=Target)
  dev.off()
}

