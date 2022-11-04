# FANN-for-airway-segmentation
This is a release code of the paper "Fuzzy Attention Neural Network to Tackle Discontinuity in Airway Segmentation" 
## Updates
**04/11/2022**: Upload docker files for reproducing the module.Release the evaluation metrics.   
**Coming soon**: release the FANN code when the paper is accepted.  
## Reproduce the work in the paper
Using the docker file by  
```docker container run --gpus "device=0" --name yang --rm -v your_test_data_path:/workspace/inputs/ -v your_test_output_path:/workspace/outputs/ yang:latest /bin/bash -c "sh predict.sh" ```
## Evaluation metrics
Find the evaluation metrics from ```utils/airway_metric.py```
