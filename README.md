[![CircleCI](https://circleci.com/gh/danilopezsanchez/project-machine-learning.svg?style=svg)](https://circleci.com/gh/danilopezsanchez/project-machine-learning)

## Project Overview

You are given a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on the data source site. This project tests your ability to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling

---

## Setup the Environment

* Create a virtualenv and activate it
```bash
make setup
source ~/.devops/bin/activate
```

* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`

* Make a prediction with
```bash
./make_prediction.sh
```

### Kubernetes Steps
```bash
minikube start
./run_kubernetes.sh
```
* Make a prediction with
```bash
./make_prediction.sh
```
