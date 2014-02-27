legalanalytics-problemset1-problem1
===================================
png(file='plot1.png', height=img.h, width=img.w)
> ggplot(val, aes(x, V2)) + geom_jitter(aes(shape = as.factor(V3)), position = position_jitter(height = 2)) + 
+         scale_shape_discrete(legend = FALSE, solid = FALSE) + geom_hline(aes(yintercept = c(10,30))) + 
+         theme_bw() + xlab("X") + ylab("Y")
