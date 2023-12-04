# Kidney-Disease-Classification-MLFlow-DVC

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/anishsheikh1303/Kidney-Disease-Classification-MLFlow-DVC
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

## MLFLOW

- [Documentation](https://mlflow.org/docs/latest/index.html)

#### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/anishsheikh1303/Kidney-Disease-Classification-MLFlow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=anishsheikh1303 \
MLFLOW_TRACKING_PASSWORD=286764511ed0bf1352a970cd4d290e45491e56c4 \
python script.py

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/anishsheikh1303/Kidney-Disease-Classification-MLFlow-DVC.mlflow

export MLFLOW_TRACKING_USERNAME=anishsheikh1303

export MLFLOW_TRACKING_PASSWORD=286764511ed0bf1352a970cd4d290e45491e56c4
```