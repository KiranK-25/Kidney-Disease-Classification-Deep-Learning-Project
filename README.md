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
https://github.com/KiranK-25/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.9 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```
##### cmd

- mlflow ui

```

```

### dagshub

[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/KiranK-25/Kidney-Disease-Classification-Deep-Learning-Project.mlflow \
MLFLOW_TRACKING_USERNAME=KiranK-25 \
MLFLOW_TRACKING_PASSWORD=5dba01b5691bf74ea0e273af8dcba06320825ea0 \
python script.py

Run this to export env as variables:


```

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/KiranK-25/Kidney-Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=KiranK-25

export MLFLOW_TRACKING_PASSWORD=5dba01b5691bf74ea0e273af8dcba06320825ea0

```