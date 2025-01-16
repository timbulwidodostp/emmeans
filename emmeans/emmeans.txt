# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimated marginal means (Least-squares means) Use emmeans With (In) R Software
install.packages("emmeans")
library("emmeans")
emmeans = read.csv("https://raw.githubusercontent.com/timbulwidodostp/emmeans/main/emmeans/emmeans.csv",sep = ";")
# (Estimation) Estimated marginal means (Least-squares means) Use emmeans With (In) R Software
emmeans <- lm(breaks ~ wool * tension, data = emmeans)
emmeans <- emmeans (emmeans,  ~ wool | tension)
summary(emmeans)
# Estimated marginal means (Least-squares means) Use emmeans With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished