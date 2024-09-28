# MMMillInstallation
This repository contains installation script to install MMYolo and MMDetection on MST Computing cluster
## How to Use
ssh into the mill  
git clone this repository

run the following sbatch jobs and view their .out files to ensure installation completes  

MMYolo:
sbatch createmmyoloenv.sub  
sbatch checkmmyoloenv.sub  
sbatch checkmmyolo.sub  

MMDetection:
sbatch createmmdetectionenv.sub  
sbatch checkmmdetectionenv.sub  
sbatch checkmmdetection.sub  

MMYolo should put an example output inside of /mmyolo/output/demo.jpg when successfully installed
MMDetection should put an example output inside of /MMDetection/outputs when successfully installed
