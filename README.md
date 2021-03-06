# Getting Started with IBM Blockchain Platform Version 2
This tutorial shows you how to get started with the IBM Blockchain Platform version 2. The aim is to walk you through each step of the process, showing how you get a blockchain application running on an enterprise grade Hyperledger Fabric platform. Here are the steps we will be following:

![Tutorial Steps](images/tutorial-steps.png)

This tutorial does _not_ cover the actual development of an application. There are various example applications that you can use and [later](docs/clonerepo.md) I'll suggest some you can deploy and where you can find them but for now this tutorial uses the [FabCar sample](https://github.com/IBM/fabcar-blockchain-sample.git).

IBM Blockchain Platform is currently in free beta so this tutorial applies to that version. It will be updated as the platform moves to General Availabilty (GA).

IBM Blockchain Platform v2 differs from v1 in that it is now deployed into Kubernetes clusters using the IBM Kubernetes Service (IKS). This is good news and bad news. Whilst you get far more control of the underlying container resources it also means you need a greater understanding of: Kubernetes, Docker (one of the container technologies that Kubernetes supports) as well as the IBM Cloud command line interface. The prerequisites step ensures you have all the tools and command lines you need to use these technologies.

- [Step 0 - Install Prerequisites](docs/prereqs.md)
- [Step 1 - Create IBM Cloud Services](docs/cloudservices.md)
- [Step 2 - Build the Blockchain Network](docs/buildnetwork.md)
- [Step 3 - Clone an Application Repo](docs/clonerepo.md)
- [Step 4 - Package a Smart Contract](docs/packagesc.md)
- [Step 5 - Deploy a Smart Contract to the  Network](docs/deploysc.md)
- [Step 6 - Connect the Application to the Network](docs/connectnetwork.md)
- [Step 7 - Run the Application](docs/runapp.md)