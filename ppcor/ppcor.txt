# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Partial and Semi-Partial (Part) Correlation Use pcor And spcor (ppcor) With (In) R Software
install.packages("ppcor")
library("ppcor")
ppcor = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ppcor/main/ppcor/ppcor.csv",sep = ";")
# Estimation Partial and Semi-Partial (Part) Correlation Use pcor And spcor (ppcor) With (In) R Software
Dependen <- ppcor$Dependen
Independen_1 <- ppcor$Independen_1
Independen_2 <- ppcor$Independen_2
Independen_3 <- ppcor$Independen_3
ppcor <- data.frame(Dependen, Independen_1, Independen_2, Independen_3)
# partial correlation
pcor(ppcor)
# semi-partial (part) correlation
spcor(ppcor)
# Partial and Semi-Partial (Part) Correlation Use pcor And spcor (ppcor) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
