# R Code for Individual Control Chart for PartLength
library(qcc)
current_data <- get("X002..2.")
filtered_data_cc <- current_data[current_data$Machine == 3 & current_data$Temperature == 373 & current_data$Pressure == 100, ]
data_for_qcc <- na.omit(as.numeric(filtered_data_cc[['PartLength']]))
if (length(data_for_qcc) >= 2) {
  # X-bar individual chart (for individual measurements)
  q <- qcc(data_for_qcc, type='xbar.one', plot=FALSE)
  png('media/plots/control_chart_partlength_m3_t373_p100.png', width=1000, height=600)
  plot(q, 
       title=paste0('Individual Control Chart for PartLength (M:3, T:373, P:100)'),
       cex.main=1.5, cex.lab=1.2, cex.axis=1.0, 
       col.points='black', col.lines='blue', col.limits='red', 
       lwd=2, restore.par=FALSE)
  dev.off()
} else {
  cat('Not enough valid numeric data for Control Chart for PartLength (M:3, T:373, P:100).\n')
}

