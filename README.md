# fusionauth-k8s-infrastructure

This repo holds the Kubernetes configuration files for a fusionauth-app with istio integration.

## Usage

Changes pushed to the master branch should trigger the following actions:

 - a recursive application of the configuration files located under the kubernetes directory.

See the [cloudbuild.yaml](cloudbuild.yaml) file for more details.