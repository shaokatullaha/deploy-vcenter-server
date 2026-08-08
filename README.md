# deploy-vcenter-server 8.x/7.x

vCenter Server is the central management platform for VMware vSphere environments. It lets you control ESXi hosts, virtual machines, storage, networking, automation, and security — all from one place.

There are two Stage for deploy vCenter server applicance. 
## Stage 1

**Prerequsit: For Deploy vCenter server 8.x/7.x you must have a DNS server or your IP address must be resolve the FQDN and from the installer machine IP address must be resolve the FQDN**

- Download the target vCener ISO from VMware 

- Mount the ISO file or extract the ISO. 

- After mount the ISO it look like this:
<p align="center">
  <img src="snap/iso-mount.PNG" width="800">
</p>

- From the mount directory go the vcsa-ui-installer> win32 and click on intaller application

<p align="center">
  <img src="snap/installer.PNG" width="800">
</p>

- After click on installer the installation page will start. There are four option , we will go for install.

<p align="center">
  <img src="snap/start-install.PNG" width="800">
</p>

- Click on intall and the Stage 1 installation will start, click on next

<p align="center">
  <img src="snap/step1.PNG" width="800">
</p>

- Accept the license aggrement and click on next

<p align="center">
  <img src="snap/lic-aggrement.PNG" width="800">
</p>

- After agree the lic you need to give the targeted host where the vCenter appliance will deployed. you need to provide the host IP/FQDN and root password. After providing this click on Next.

<p align="center">
  <img src="snap/targeted-host.PNG" width="800">
</p>

- After click the next a certificate warning will be pop up and you need to click on yes.

<p align="center">
  <img src="snap/certificate-warning.PNG" width="800">
</p>

- Now you need to select the deployment size base on your requirements.

<p align="center">
  <img src="snap/deployment-size.PNG" width="800">
</p>

- Now need to select the datastore where the Appliance will be deployed.

<p align="center">
  <img src="snap/select-datastore.PNG" width="800">
</p>

- After selecting the datastore now you need to select the port group for applicane network and provide the Applicane FQDN, IP address, subnet mask , gateway, and DNS server information.

<p align="center">
  <img src="snap/ip-config.PNG" width="800">
</p>

- In this step you need to review the all provided information and chaeck again if any information is wrong. if everything is fine then click on finished.

<p align="center">
  <img src="snap/stage1-review.PNG" width="800">
</p>

- Now the VCSA appliance installation will be start. It will take some time to complete the process base on your network speed.

<p align="center">
  <img src="snap/vcsa-deploy-start.PNG" width="800">
</p>

**Stage 01 Finised**

## Stage 2

- After the VCSA deployment is complete now you need to click on contiue for start the stage 2

<p align="center">
  <img src="snap/stage2-continue.PNG" width="800">
</p>

- After click on the continue the stage 2 installation will be start 

<p align="center">
  <img src="snap/stage2-start.PNG" width="800">
</p>

- In this step you need to select the NTP server if you want.

<p align="center">
  <img src="snap/ntp-server.PNG" width="800">
</p>

- Now you need to provide the informatin for SSO 

<p align="center">
  <img src="snap/create-sso.PNG" width="800">
</p>

- If you want you can now join in the customer experience

<p align="center">
  <img src="snap/join-in-customer-experience.PNG" width="800">
</p>

- Now review the provided information and click finised 

<p align="center">
  <img src="snap/rivew-and-finised.PNG" width="800">
</p>

- Now wait for complete the stage 2

<p align="center">
  <img src="snap/stage2-finised.PNG" width="800">
</p>


**After compete the stage, hit your applicae IP address on browser and provide the user name and password to login the server**



