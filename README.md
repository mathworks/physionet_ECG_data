# physionet_ECG_data
This repository contains human electrocardiogram data (ECG) data used in MathWorks' Wavelet Toolbox machine and deep learning examples.
This data is sourced from https://www.physionet.org/. In keeping with PhysioNet's copying policy, the ECGData.zip file contains a 
.txt file, Modified_physionet_data.txt, which contains the specific attributions for the orignal PhysioNet source databases as well as
a description of all data modifications.

Important Note:
Examples in some versions of MATLAB reference the downloaded .zip file in text and code as ending in ```-master.zip```. To avoid errors in 
execution, replace instances of ```-master.zip``` in code with ```-main.zip```.

For example:

```>>unzip(fullfile(tempdir,'physionet_ECG_data-main.zip'),tempdir)```

```>>unzip(fullfile(tempdir,'physionet_ECG_data-main','ECGData.zip'),...```

```    fullfile(tempdir,'ECGData'))```

If you use ```git clone https://github.com/mathworks/physionet_ECG_data``` to download the data, the .zip file is "ECGData.zip" in your
physionet_ECG_data folder.



