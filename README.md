# FreeSurfer Cortex AutoQC
Region specific automatic quality assurance for MRI derived cortical segmentations


## Requirements:
* python >= 3.7.9
* jupyterlab >= 1.1.4
* scikit-learn >= 0.23.2
* pandas >= 1.1.3
* lightgbm >= 2.3.0

## How to use the tool:
* Clone the github directory using: git clone https://github.com/USC-IGC/FreeSurfer_Cortex_AutoQC.git
* Install all the packages required to run this tool mentioned in requirements.txt file
* For testing the tool:
  * In scripts folder, open run.sh file and make the following changes:
    1. Add the path for python on line 7
    2. Add the FS directory path on line 10
    3. Add the path for subject list text file on line 13
    4. Add the output directory path on line 16
    5. If using FSv7.1.1, comment line 26 and uncomment line 29 
  * Run the bash file ---> sh run.sh

## References:
ISBI link:
