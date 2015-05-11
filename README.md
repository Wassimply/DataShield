# DataShield
Mining data to prevent terrorism in Tunisia

Take a look here 
https://medium.com/@Wassimply/how-data-mining-coud-have-prevented-tunisia-s-terror-attacks-in-bardo-museum-1292fc32e36a
We are building the project in R , I ll be comiting the whol project later 


#! /Wassim/bin/env Rscript
require("getopt", quietly=TRUE)
 
spec = matrix(c(
  "xValue"   , "x", 1, "double"
), byrow=TRUE, ncol=4)
 
opt = getopt(spec);
 
if (is.null(opt$xValue)) {
  x <- 5
} else {
  x <- opt$xValue
}
 
print(x)

