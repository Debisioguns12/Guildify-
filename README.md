# Guildify-
Using Guildify to create Trained List for Toppgene Gene Prioritization
library(devtools)
install_github("emreg00/guildifyR")
# Example query and retrieve results code

install.packages("guildifyR")
??guildifyR
if (!require("Guildify", quietly = TRUE))
  install.packages("Guildify")

setwd("/Users/ogunbawoadebisi/Downloads/guildify_test")
/Users/ogunbawoadebisi/Downloads/meta_analyse/guildifyR
install("guildifyR")
# Example query and retrieve results cod
library(guildifyR)
library(devtools)
install_github("emreg00/guildifyR") 
######################################################
setwd("/Users/ogunbawoadebisi/Downloads/guildify_test")
install.packages("devtools")
library(devtools)
install_github("emreg00/guildifyR")
library(guildifyR)
# Parameters
species="9606"
tissue="all"
network.source="BIANA"
#selecyion of seeds
result.table = query("scrotum", species, tissue, network.source)
library(readxl)
library(openxlsx)
write.xlsx(result.table, "result.table.xlsx")

result.table_testes = query("testes", species, tissue, network.source)
library(readxl)
library(openxlsx)
write.xlsx(result.table, "result.table.xlsx")

result.table_s = query("embryonic development", species, tissue, network.source)
library(readxl)
library(openxlsx)
write.xlsx(result.table, "result.table.xlsx")
