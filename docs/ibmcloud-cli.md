# Useful IBM Cloud CLI Commands
The instructions for getting started with IBM Cloud CLI can be found [here](https://cloud.ibm.com/docs/cli/index.html#overview).

## Login and Setup Commands
_Log in to IBM Cloud with your IBMid. If you have multiple accounts, you are prompted to select which account to use. If you do not specify a region with the -r flag, you must also choose a region._
`$ ibmcloud login`

_To use Cloud Foundry services, target an org and space._
`$ ibmcloud target -o <value> -s <value>`

_To target Cloud Foundry org/space interactively._
`$ ibmcloud target --cf` 

## Kubernetes Service (KS) Commands
_Target the IBM Cloud Container Service <region> (e.g. `us-south`) in which you want to work._
`$ ibmcloud ks region-set <region>`

_Check which region you are in._
`$ ibmcloud ks region`

_Create a cluster._
`$ ibmcloud ks cluster-create --name <cluster-name>`

_Check the status of your clusters._
`$ ibmcloud ks clusters`

_Set the environment variable and download the Kubernetes configuration files. When the download of the configuration files is finished, a command is displayed that you can use to set the path to the local Kubernetes configuration file as an environment variable._
`$ ibmcloud ks cluster-config --cluster <cluster_name_or_ID>`

_Find the worker(s) ID and IP addresses._
`$ ibmcloud ks workers --cluster <cluster_name_or_ID>`