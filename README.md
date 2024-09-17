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

<p align="center">
Launch the Virtual Machine Event Viewer: 
https://i.imgur.com/DbRSt5p.png

Use PowerShell script to extract metadata from Windows Event Viewer
https://i.imgur.com/tjSNnbw.png

Configure Log Analytics Workspace in Azure
https://i.imgur.com/fDB5QIn.png

Configure Workbook
https://imgur.com/9e282b4a-0ff9-458c-af4f-1eec1bfac004

World Map displaying global attack data
https://i.imgur.com/y5kTvi4.png


 
