# NF_Revision_Phase1-Replacing-areas-identification-code

Diversified global vegetable oil production through Camellia oleifera can mitigate climate change and achieve socio-environmental co-benefits 

Supplementary Information - Code to compute Replacing areas identification of Camellia

Phase 1: Constraint-driven feasible solution space delineation. This phase corresponds to the mathematical optimization model described in the "Crop-replacing constraints" section of the paper. All key constraints, including the yield safeguard constraint, crop-specific replacement ratio caps (Table S24), the global total replacement area cap (23.5%), and the net environmental/economic benefit constraints, are implemented during the data preprocessing stage 1. Specifically, through global-, crop- and grid-level calculations and filtering, we pre-exclude any areas that do not satisfy these constraints, generating a raster dataset that represents the feasible solution space (see the tiff files of “ProcessingResults_3_ReplacingArea” in link: https://github.com/Camellia-Ch/NF_Revision_Phase1-Replacing-areas-identification-code).


Note 1: Original data = files1 = list.files(pattern = ".tif$") 

Note 2: Priorities refer to the highest (level: 1) to lowest (level: 100) valuable areas for Camellia replacement to achieve benefits.

Note 3: software's license for use is RStudio (https://posit.co/download/rstudio-desktop/).
