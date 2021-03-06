# Getting Started

!!! example "Tip" 
    - **To open this lab guide in a separate browser window use [This Link](https://ksingh7.github.io/data-show/).**

## Test Drive Prerequisites

For this lab you need the following:

- Workstation with Internet access
- SSH client program installed on your workstation

## Starting the LAB

After you have logged into [Red Hat Test Drive Portal](https://redhat.qwiklab.com) , select ``Ceph Data Show : All-in-One`` Test Drive from the catalog Icon.

- To start the Test Drive press ![](images/qwiklab-start-button.png) button in the top bar.
- By the time your lab environment is getting ready, you could setup Access Keys as shown below.

## Accessing the LAB

- Immediately after pressing the ``START`` button button, the download links for the SSH keys will become active (blue) in the left hand pane in a section labeled "Connection Details":

![](images/access_keys.png)

- Download the PEM key to your computer if you are using regular OpenSSH on the command line with Linux or macOS. Choose Download PPK if you are using PuTTY on Windows.

- Change permission of the downloaded SSH private key

```
chmod 400 ~/Dowloads/access_key.pem
```

## Wait for lab provisioning to complete

Generally it takes less than 15 minutes to provision your lab environment. Once your lab environment is provisioned, you will find login details on the left hand pane in a section labeled ``Connection Details`` 

- ``Ceph Node IP Address``
- ``Ceph Node SSH user name``
- ``Ceph S3 Endpoint``
- ``OpenShift Console URL``
- ``OpenShift Console user name``
- ``OpenShift Console Password``
- ``OpenShift Master Node IP Address``
- ``OpenShift Master Node SSH user name``
