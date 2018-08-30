# myvariant.R
R client for MyVariant.info web services.


To install from your R console:

    if (!requireNamespace("BiocManager", quietly=TRUE))
        install.packages("BiocManager")
    BiocManager::install(c("httr", "jsonlite", "S4Vectors", "IRanges", "Hmisc", "plyr", "magrittr", "VariantAnnotation"))
    library(devtools)
    install_github("Network-of-BioThings/myvariant.R")
