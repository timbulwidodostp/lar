# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Least Angle Regression use lar (selectiveInference) With (In) R Software
install.packages("selectiveInference")
library("selectiveInference")
lar = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lar/main/lar/lar.csv",sep = ";")
# Estimation Least Angle Regression use lar (selectiveInference) With (In) R Software
y = lar$y
x = cbind(lar$X1, lar$X2, lar$X3, lar$X4, lar$X5, lar$X6, lar$X7, lar$X8, lar$X9, lar$X10)
lar = lar(x,y)
plot(lar)
lars = larInf(lar)
lars
# Least Angle Regression use lar (selectiveInference) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished