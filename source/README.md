# Project work
This is a basic Python-Flask implementation of a Hello World app.
Dependencies:
- Python 3


Installation steps:
```sh
python3 -m venv venv              # 1. Create a virtual environment
source venv/bin/activate          # 2. Activate the virtual environment
pip3 install -r requirements.txt  # 3. Install dependencies
```

Startup steps:
```sh
python3 app.py  # 1. Start the application
```

## Tasks
Your tasks are:
- Containerize the app, push in image to DockerHub
- Create yaml files for Kubernetes deployment, try them on minikube
- Create a CI/CD pipeline that builds the container and pushes it to DockerHub
- Create a separate CI/CD pipeline that creates the required Kubernetes resources with terraform (Jenkins and Kubernetes have to be in the same network)
- Extend the first pipeline to also deploy the app to the Kubernetes cluster
