library(qcc)
data_for_pc <- na.omit(as.numeric(get('X002..2.')[get('X002..2.')$Machine == 3 & get('X002..2.')$Temperature == 338 & get('X002..2.')$Pressure == 200, ][['PartLength']]))
if (length(data_for_pc) > 0) {
  LSL <- 44
  USL <- 56
  Target <- 50
  qcc_obj <- qcc(data_for_pc, type='xbar.one', plot=FALSE)
  png('media/plots/process_capability_partlength_m3_t338_p200.png', width=1000, height=600)
  process.capability(qcc_obj, spec.limits=c(LSL, USL), target=Target)
  dev.off()
}

