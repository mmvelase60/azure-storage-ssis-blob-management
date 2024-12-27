<h1>Azure Blob Storage Management with SSIS</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This repository demonstrates how to explore various Azure Storage services and manage files in Azure Blob Storage using SQL Server Integration Services (SSIS). The project includes instructions for creating Azure Storage Accounts, configuring containers, and utilizing SSIS to copy and delete files from Azure Blob Storage.
<br />


## Features
- **Azure Storage Account Setup**: Step-by-step guide to creating an Azure Storage Account.
- **Azure Container Management**: Instructions for creating and configuring containers in Azure Blob Storage.
- **File Operations with SSIS**:
  - Copy files to Azure Blob Storage using SSIS.
  - Delete files from Azure Blob Storage using SSIS.

## Contents
### Azure Storage Setup
1. **Create Azure Storage Account**
   - Step-by-step instructions for setting up a new Azure Storage Account in the Azure Portal.
   - Key settings include subscription, resource group, storage account name, region, and redundancy.<br/>
   <br />
    <p align="center">Fig-1: Create Azure Storage Account<p/>
     <br />
     <img src="https://imgur.com/N2jUAlw.png" height="80%" width="80%" alt="Create Azure Storage Account"/>
     <br />
     <br />
2. **Create Azure Container**
   - Guidance on creating a container in Azure Blob Storage.
   - Options for public access and naming conventions.<br/>
    <br />
    <p align="center">Fig-2: Create Azure Container<p/>
     <br />
     <img src="https://imgur.com/BKRaGYo.png" height="80%" width="80%" alt="Create Azure Container"/>
     <br />
     <br />
### File Operations
#### Upload Files
- Instructions to upload files to the Azure Blob Storage container using the Azure portal.<br/>
     <br />
     <p align="center">Fig-3: Upload files<p/>
     <br />
     <img src="https://imgur.com/jNEpL18.png" height="80%" width="80%" alt="Upload files"/>
     <br />
     <br />
      <img src="https://imgur.com/nYDl3KF.png" height="80%" width="80%" alt="Upload files"/>
     <br />

<p align="center">Fig-4: Open visual studio 2019.<p/>
<br />
     <br />
     <img src="https://imgur.com/cTKgUlC.png" height="80%" width="80%" alt="Open visual studio 2019"/>
     <br />
     <br />
     <br />
     <br />
#### SSIS Configuration
1. **Create an SSIS Project**
   - Open Visual Studio 2019, create a new Integration Services project, and name it appropriately.
   - Use Azure Feature Pack to add and configure the Flexible Azure Task.
   <br />
     <p align="center">Fig-5: Create new SSIS project in visual studio 2019.<p/>
  <br />
     <img src="https://imgur.com/hbxMoG6.png" height="80%" width="80%" alt="Create new SSIS project in visual studio 2019"/>
     <br />
      <img src="https://imgur.com/A7sk7Mn.png" height="80%" width="80%" alt="Create new SSIS project in visual studio 2019"/>
     <br />
2. **File Deletion**
   - Configure the Flexible Azure Task for deleting files.
   - Validate the deletion with progress reports and container checks.
    <br />
     <p align="center">Fig-6: Configure flexible azure task for delete files<p/>
  <br />
     <img src="https://imgur.com/NUUgHj8.png" height="80%" width="80%" alt="Configure flexible azure task for delete files"/>
     <br />
      <img src="https://imgur.com/V3OJsND.png" height="80%" width="80%" alt="Configure flexible azure task for delete files"/>
     <br />
3. **File Copy**
   - Configure the Flexible Azure Task for copying files.
   - Validate the copied files in the destination container.
    <br />
     <p align="center">Fig-7: Check if delete files was successful<p/>
  <br />
     <img src="https://imgur.com/s5HBsRf.png" height="80%" width="80%" alt="Check if delete files was successful"/>
     <br />
     <br />
 <br />
     <p align="center">Fig-8: Configure flexible azure task for delete files<p/>
  <br />
     <img src="https://imgur.com/s5HBsRf.png" height="80%" width="80%" alt="Configure flexible azure task for delete files"/>
     <br />
     <br />
 <br />
     <p align="center">Fig-9: Progress report of the flexible azure task<p/>
  <br />
     <img src="https://imgur.com/T8VcCts.png" height="80%" width="80%" alt="Progress report of the flexible azure task"/>
     <br />
     <br />
      <br />
     <p align="center">Fig-10: Configure flexible azure task for copied files<p/>
  <br />
     <img src="https://imgur.com/8UKPoPW.png" height="80%" width="80%" alt="Configure flexible azure task for copied files"/>
     <br />
      <img src="https://imgur.com/W93jOdQ.png" height="80%" width="80%" alt="Configure flexible azure task for copied files"/>
     <br />
      <br />
     <p align="center">Fig-11: Configure flexible azure task for copy files<p/>
  <br />
     <img src="https://imgur.com/eLddzMi.png" height="80%" width="80%" alt="Configure flexible azure task for copy files"/>
     <br />
      <img src="https://imgur.com/1KN73oF.png" height="80%" width="80%" alt="Configure flexible azure task for copy files"/>
     <br />

### Visual Guides
- Figures illustrating each step, including creating accounts, configuring SSIS tasks, and validating operations.

## Prerequisites
- Azure Subscription
- Visual Studio 2019 with SSIS and Azure Feature Pack installed
- Access to Azure Blob Storage

## How to Use
1. Follow the setup steps to configure your Azure Storage Account and containers.
2. Use Visual Studio to create an SSIS package for file operations.
3. Execute the SSIS package to copy or delete files and verify the results.



Explore the potential of Azure Storage and SSIS to simplify your data management tasks!

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
