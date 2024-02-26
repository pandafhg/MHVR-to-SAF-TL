# Introduction
For more detailed description, please refer to the authors' article and base DNN model.

If you need to use the model in your study, please cite the author's articles (below).

Pan et al., Transfer learning model for estimating site amplification factors from limited microtremor H/V spectral ratios (https://doi.org/10.1093/gji/ggae065)

**************************************************************************************************** 
Base model

Pan et al., Deep Neural Network-based Estimation of Site Amplification Factor from Microtremor H/V Spectral Ratio (https://doi.org/10.1785/0120210300).  
https://github.com/pandafhg/MHVR-to-SAF.git

# RunOnnxBatch.py
- The file RunOnnxBatch.py is the batch processing.
- The folder MHVR contains all MHVR data (support *.csv, *.txt, *.dat) that needs to be processed. 
  Spacing of data columns supports space, double space, tab and comma.
- The MHVR_SAF folder contains processed pSAF data and is named in the format [SAF_source_filename]. Some examples can be found in the MHVR folder.

Flow:

* Click on RunOnnxBatch.py and it will show the path where the pSAF is stored; 
* Enter the folder path (full path) with all MHVR data; note that the folder should not contain other non-essential files.
* After the process is completed, the saved file path is shown.
* Please ensure that the MHVR file matches the example shown in the tutorial. Please check that the output is the same as RunOnnx.py.

# Contact
If you have any questions or suggestions, please send an email to the author.

Da Pan; pd19951229@gmail.com; d214903@hiroshima-u.ac.jp
