library(qcc)
data_for_qcc <- na.omit(as.numeric(get('X002..2.')[get('X002..2.')$Machine == 3 & get('X002..2.')$Temperature == 373 & get('X002..2.')$Pressure == 200, ][['PartLength']]))
if (length(data_for_qcc) >= 2) {
  q <- qcc(data_for_qcc, type='xbar.one', plot=FALSE)
  png('media/plots/control_chart_partlength_m3_t373_p200.png', width=1000, height=600)
  plot(q, title=paste0('Individual Control Chart: PartLength (M:3, T:373, P:200)'))
  dev.off()
}

