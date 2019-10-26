# OpenEBS Operator

**OpenEBS** is the leading open source example of a category of storage solutions sometimes called [Container Attached Storage](https://www.cncf.io/blog/2018/04/19/container-attached-storage-a-primer/). **OpenEBS** is listed as an open source example in the [CNCF Storage Landscape White Paper](https://github.com/cncf/sig-storage/blob/master/CNCF%20Storage%20Landscape%20-%20White%20Paper.pdf) under the hyperconverged storage solutions.

The **KUDO OpenEBS Operator** creates, configures and manages [OpenEBS](https://openebs.io/) storage provider running on Kubernetes

## Prerequisites

OpenEBS can be set up in a few easy steps. 

Installation of the iSCSI initiator service and tools depends on your host O/S or the kubelet container. You can follow the steps [here](https://docs.openebs.io/docs/next/prerequisites.html) for installation/verification of the required packages. 
It is a mandatory step to verify the iSCSI services and make sure that it is running on all the worker nodes. OpenEBS uses the iSCSI protocol to connect to the block volumes.

## Getting started

The latest stable version of OpenEBS operator is `0.3.0`
For more details, please see the [docs](./docs/v0.3) folder.

For the latest master branch you can check  [docs](./docs/latest) docs 


## Version Chart

| KUDO OpenEBS Version | OpenEBS Version |
| -------------------- | --------------- |
| 0.3.0                | 1.3.0           |
| latest               | 1.3.0           |
