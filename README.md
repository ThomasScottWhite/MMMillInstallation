# MMYoloMillInstallation
This is an installation script to install MMYolo on MST Computing cluster
## How to Use
ssh into the mill  
git clone this repository

run the following sbatch jobs and view their .out files to ensure installation completes  

sbatch createcondaenv.sub  
sbatch checkcondaenv.sub  
sbatch checkmmyolo.sub  

MMYolo should put an example output inside of /mmyolo/output/demo.jpg when successfully installed