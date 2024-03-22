# Chest-Disease-Classification
# Chest-Disease-Classification-from-Chest-CT-Scan-Image


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 


RUN from bash terminal

export MLFLOW_TRACKING_URI=https://dagshub.com/Arya1790/Chest-Disease-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=Arya1790 

export MLFLOW_TRACKING_PASSWORD=68475e648f40526b233af1bd9072b5d9857e8c31

## Jenkinsfile
change the docker-compose url and ubuntu machine id

## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate C:/Users/Arya/Anaconda3/envs/chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```
