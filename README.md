# AzureSentinel
<h2>Description</h2>

•	Used custom PowerShell script to extract metadata from Windows Event Viewer to be forwarded to third party API in order to derive geolocation data

•	Configured Log Analytics Workspace in Azure to ingest customs logs containing geographic information (latitude, longitude, state/province, country)

•	Configured Custom Fields in Log Analytics Workspace with the intent of mapping geo data in Azure Sentinel

•	Configured Azure Sentinel (Microsoft’s cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure Sentinel</b>
- <b>Azure Log Analytics Workspace</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>
Launch Event Viewer

![DbRSt5p](https://github.com/user-attachments/assets/c2ba290e-be61-44cf-89a1-ded96a620454)


Use PowerShell script to extract metadata from Windows Event Viewer

 ![tjSNnbw](https://github.com/user-attachments/assets/8a78566c-4d15-401d-a915-5d0121a1abfe)


Configure Log Analytics Workspace in Azure
![fDB5QIn](https://github.com/user-attachments/assets/356fb4ba-a925-4f7e-8954-55293ca46d15)


Configure Workbook
![EdotUe6](https://github.com/user-attachments/assets/cd11ec5e-803a-4de7-b03f-5203ba9e8d02)


World Map displaying global attack data
![y5kTvi4](https://github.com/user-attachments/assets/216ee18b-5e07-4602-a819-dc018fe4945a)



 
