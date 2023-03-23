# CI/CD Best Practices for SpringBoot Application

* This repository contains a GitHub Actions pipeline that incorporates some best practices for managing application code. *

## Pre-requisites
Set up [Workload Identity Federation](https://github.com/google-github-actions/auth#setting-up-workload-identity-federation) to authenticate GCP to push the Docker image to Google Artifact Registry


## Features

* Unit Testing with Maven 
* Static code analysis with ([SonarCloud](https://sonarcloud.io/))
* Build and push Docker image to ([GCP Artifact Registry](https://cloud.google.com/artifact-registry))
* Security scan of the Docker image with ([Grype](https://github.com/anchore/grype))



