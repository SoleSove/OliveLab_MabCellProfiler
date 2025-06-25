# OliveLab_MabCellProfiler
Files pertaining to the CellProfiler pipelines used by the Olive Research Group at Michigan State University. Built using CellProfiler 4.2.6
These pipelines were developed to quantify the ratio of NF-κb in the nucleus to the cytosol, based on the MFI of staining in each cell. This ratio serves as a measure of translocation.
This repository contains two CellProfiler pipelines, one for each macrophage cell type analyzed in our study:
-one optimized for bone marrow-derived macrophages (BMDMs)
-one optimized for fetal liver-derived alveolar-like macrophages (FLAMs)
The pipelines are identical in all steps, except for the secondary object identification step (cell edge detection). This step was customized for each cell type due to their distinct morphologies, which required optimized segmentation parameters.
#Requirements
- CellProfiler (https://cellprofiler.org/) version 4.2.6
##How to use
1. Open the `.cppipe` file in CellProfiler.
2. Point to your image folder and metadata file if applicable.
3. Adjust output folder and settings as needed.
4. Run the pipeline and export measurements. 
##Citation
Feel free to use or adapt this pipeline for your own research. If you publish results using it, we kindly ask that you cite our original work: **Differential activation of NF-kB and HIF-1a between alveolar-like macrophages and myeloid-derived macrophages drives inflammatory differences following _Mycobacterium abscessus_ infection. **  DOI:
