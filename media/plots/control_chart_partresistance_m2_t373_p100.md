library(qcc)
data_for_qcc <- na.omit(as.numeric(get('X002..2.')[get('X002..2.')$Machine == 2 & get('X002..2.')$Temperature == 373 & get('X002..2.')$Pressure == 100, ][['PartResistance']]))
if (length(data_for_qcc) >= 2) {
  q <- qcc(data_for_qcc, type='xbar.one', plot=FALSE)
  png('media/plots/control_chart_partresistance_m2_t373_p100.png', width=1000, height=600)
  plot(q, title=paste0('Individual Control Chart: PartResistance (M:2, T:373, P:100)'))
  dev.off()
}

