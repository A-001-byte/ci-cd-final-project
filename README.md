# CI/CD Final Project

Project name: `ci-cd-final-project`, the final project for the Coursera course **CI/CD Tools and Practices**.

A small Flask counter service with a complete CI/CD setup:

- **GitHub Actions** (`.github/workflows/workflow.yml`): lints with flake8 and runs the unit tests with nose on every push and pull request.
- **Tekton tasks and pipeline** (`.tekton/`): cleanup, git-clone, flake8, nose, buildah and an OpenShift deploy.
- **OpenShift Pipelines**: builds the image from the `Dockerfile` and deploys it to the cluster. The service listens on port 8000.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks


## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
