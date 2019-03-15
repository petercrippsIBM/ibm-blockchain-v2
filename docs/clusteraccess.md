# Gain Access to Your Cluster

Download and install a few CLI tools and the Kubernetes Service plug-in.

`curl -sL https://ibm.biz/idt-installer | bash`

Log in to your IBM Cloud account:

`ibmcloud login -a https://api.ng.bluemix.net`

If you have a federated ID, use ibmcloud login --sso to get started.

Target the Kubernetes Service region in which you want to work:

`ibmcloud ks region-set us-south`

Get the command to set the environment variable and download the Kubernetes configuration files:

`ibmcloud ks cluster-config mycluster`

Set the KUBECONFIG environment variable. Copy the output from the previous command and paste it in your terminal. The command output should look similar to the following:

`export KUBECONFIG=/Users/$USER/.bluemix/plugins/container-service/clusters/mycluster/kube-config-hou02-mycluster.yml`

Alternatively, you can directly download your kubeconfig files to manually configure the cluster context.

Verify that you can connect to your cluster by listing your worker nodes:

`kubectl get nodes`

It can take a few minutes for your cluster to be ready. While you wait, try creating a registry! When it's ready, you can use the Kubernetes dashboard button to access your cluster information.