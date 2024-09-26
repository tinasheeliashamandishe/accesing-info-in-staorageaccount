<h1>Accesing Information in Storage Accounts</h1>

<h2>Description</h2>
This lab will explaore methods to access information in an storage account.<br /><br />


There are 4 methods used to access information in an storage account:

<b>Public access:</b> 
<br />
<b>Access keys:</b> 
<br />
<b>Shared Access signatures:</b> 
<br />
<b>Microsoft Entra ID:</b> 
<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<h3>Public access</h3> 
<h4>Enables you to access a blob using the URL provided by Azure.</h4><br/>

Enable anonymous access in your storage account.
<img src="https://i.imgur.com/CfqcwFC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

Change the access level for your blob.
<img src="https://i.imgur.com/L4rPDqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Take the URL provided by azure and accesss your blob.
<img src="https://i.imgur.com/MfTevsc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MtCFGP8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br /><br />

<h3>Access Keys</h3> 
<h4>Enables you to access the storage account using Azure Storage Explorer.</h4><br/>

Install Azure Storage Explorer.
<img src="https://i.imgur.com/nu7Jz2P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

Take the Acees Key provided by Azure.
<img src="https://i.imgur.com/aPPSrQ4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Connect to your Storage account in Install Azure Storage Explorer.
<img src="https://i.imgur.com/1ten8TQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4dDSKb2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h3>Shared Access Signatures</h3> 
<h4>Azure Shared Access Signatures (SAS) are a way to grant restricted access to Azure Storage resources without exposing your account key. With SAS, you can create a token that provides specific permissions (like read or write) on resources for a limited time.</h4><br/>
They can be used at Blob level, Conatiner Level or Storage account level.<br/><br/>

Container level Exeample: <br/><br/>

Go to your conatiner and create a shared access signature.
<img src="https://i.imgur.com/ZR7iaY1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>


Connect to your container in Install Azure Storage Explorer.
<img src="https://i.imgur.com/z00eR0T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/g7DXp1y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>

With Shared access keys comes Stored access policies which give you more control and security for your shared signatures.<br/>

<br /><br />


Bike picure taken from https://www.pexels.com/search/bike/
