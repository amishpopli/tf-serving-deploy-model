# deploy a tensorflow model
This is a vey simple project to deploy and serve a tensoflow model using docker

## Usage

```cmd
docker run -p 8501:8501 -name=pets -v "{model location}:/models/pets/1" -e MODEL_NAME=pets tennsorflow/serving

python app.py
```
