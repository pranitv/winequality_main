create env
```bash
conda create -n WineQuality python=3.7 -y
```

acitvate env
```bash
conda activate WineQuality
```
create a req file
install the req
```bash
pip install -r requirements.txt
```

````
creat a artifacts folder
mlflow server command -

mlflow server \
    --backend-store-url sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 0.0.0.0 -p 1234