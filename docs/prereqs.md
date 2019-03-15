# Step 0 - Prerequisites

Here are some resources to help with that:

* The instructions for getting started with IBM Cloud CLI can be found [here](https://cloud.ibm.com/docs/cli/index.html#overview).
* For some useful IBM Cloud CLI commands see [here](docs/ibmcloud-cli.md).
* The instructions for getting started with IBM Cloud Kubernetes Service can be found [here](https://cloud.ibm.com/docs/containers/container_index.html#container_index).
* For some useful IBM Cloud Kubernetes Service CLI commands see [here](../docs/iks-cli.md).

Whilst it's in beta IBM Blockchain Platform v2 is a bit sensitive to type and versions of browser. I use the latest version of Firefox (v65.0.1) on MacOS (v10.13.6). I find that Safari sometimes fails to display key information on a page. Google Chrome also works.

You need to be quite careful about deploying to the right version of Kubernetes also (and both the Master and Worker Nodes **must** be at the same version number that is 1.11 or higher). Information on updating clusters and worker nodes can be found [here](https://cloud.ibm.com/docs/containers/cs_cluster_update.html#update).

Having ensured you have the prerequisites all set up you can proceed with the instructions for [Getting started with IBM Blockchain Platform free 2.0 beta](https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-ibp-v2-deploy-iks#ibp-v2-deploy-iks). This gets you as far as creating a Kubernetes cluster and deploying IBP v2 onto it.