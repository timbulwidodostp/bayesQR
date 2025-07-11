# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bayesian quantile regression Use bayesQR With (In) R software
install.packages("bayesQR")
library("bayesQR")
bayesQR = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bayesQR/main/bayesQR/bayesQR.csv",sep = ";")
# Estimation Bayesian quantile regression Use bayesQR With (In) R software
X <- bayesQR$X
y <- bayesQR$y
bayesQR <- bayesQR(y~X, quantile=c(.05,.25,.5,.75,.95), alasso=TRUE, ndraw=500)
summary(bayesQR)
# Bayesian quantile regression Use bayesQR With (In) R software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished