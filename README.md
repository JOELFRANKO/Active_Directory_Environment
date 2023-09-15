<h1>Active Directory Environment</h1>

 ### [YouTube Demonstration](https://youtu.be/MHsI8hJmggI?si=RmKL8lPGSc1vjlXV)


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for adding multiple users to the Domain controller through DHCP </b>
<br />
<br />
The demo explaine here is a simple demo of setting up a active directory in a virtual box. It can help to explain a multilevel corporate IT environment's Network structure.
<br />
At first we have to set up the Virtual environment for the execution of active directory by the following flow diagram.
<br />


![img 1- FLOw](https://github.com/JOELFRANKO/Active_Directory_Environment/assets/81144974/edc853ca-dab3-45f7-99b9-8dc971449371)
<br />
<br />
<h2>Languages Used</h2>

- <b>PowerShell:</b> To create multiple user in the Domain Controller

<h2>Utilities Used</h2>

- <b>Windows Server:</b> To setup the user and maintain the acess and to maintain the active directory.

<h2>Creating a VM Domain Server in Virtual Box</h2>

![dc 1](https://github.com/JOELFRANKO/Active_Directory_Environment/assets/81144974/d06d7f11-6e05-4675-beb6-bce10d12d6b8)

<h2>Installing and Configuring Server Manager</h2>

![ADDS](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/53265205-d413-4515-9a31-d48d12b84359)
<br />

![server](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/63fa1ed4-1aac-4cba-8b17-529d8f1da625)
<br />

<h2>Installing DHCP and RAS</h2>

![DHCP](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/c71d9bfb-ae09-4320-9d59-681fc932debf)
<br />

![res](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/f7e58450-0d2f-474f-994d-7d3be9d5f544)
 
<h2>Adding Multiple user id's using power shell</h2>

![powshel](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/4e0e0347-b0e4-4841-83a6-6066773704dd)
<br />

![powshell2](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/05a10c62-6cb8-4c47-8953-0bfc6556a3f0)
<br />

![users](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/372909eb-4b48-4290-aa2a-c71261751e56)

<h2>Creating a Virtual client machine</h2>

![client](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/9a06e515-6d3d-455e-8530-ddcdcb18f2df)
<br />

<h3>Adding the client to the server</h3>

![join domain](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/8d5dffdc-aae8-4b6d-b6b3-dbc1c0a91fd9)
<br />

![change ip](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/c31509e9-8c48-4503-806f-906b67961bf2)
<br />

![admin domain](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/9a9de0a6-52ba-4c6b-99b7-e9ceb53cfd8f)
<br />

![Leace](https://github.com/JOELFRANKO/Azure_Sentinel/assets/81144974/f14e602c-c28c-440e-a4d9-d36df7220f1e)



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
