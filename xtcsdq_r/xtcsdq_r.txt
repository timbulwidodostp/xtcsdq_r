# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Tests of no cross-sectional error dependence in panel quantile regressions Use xtcsdq (paneltests) With (In) R Software
install.packages("paneltests")
library("paneltests")
# Estimate Tests of no cross-sectional error dependence in panel quantile regressions Use xtcsdq (paneltests) With (In) R Software
xtcsdq_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/xtcsdq_r/main/xtcsdq_r/xtcsdq_r.csv",sep = ";")
xtcsdq <- xtcsdq(xtcsdq ~ xtcsdq_1 + xtcsdq_2 + xtcsdq_3, data = xtcsdq_r, index = c("id", "time"), quantiles = c(0.50))
summary(xtcsdq)
# Tests of no cross-sectional error dependence in panel quantile regressions Use xtcsdq (paneltests) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished