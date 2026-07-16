library(qcc)
data_for_qcc <- na.omit(as.numeric(get('X002..2.')[get('X002..2.')$Machine == 2 & get('X002..2.')$Temperature == 303 & get('X002..2.')$Pressure == 200, ][['PartLength']]))
if (length(data_for_qcc) >= 2) {
  q <- qcc(data_for_qcc, type='xbar.one', plot=FALSE)
  png('media/plots/control_chart_partlength_m2_t303_p200.png', width=1000, height=600)
  plot(q, title=paste0('Individual Control Chart: PartLength (M:2, T:303, P:200)'))
  dev.off()
}

