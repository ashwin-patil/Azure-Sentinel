# Security Events ASIM ProcessEvent Normalization Parser

This template deploys the ASIM ProcessEvent schema parser for Security Events.

This ASIM parser supports filtering and normalizing Windows process terminate events (event 4689) collected using the Security Events connectors, utilizing either the Log Analytics agent or the Azure Monitor Agent (AMA) and stored in the SecurityEvent table to the ASIM Process Event normalized schema. 


The Advanced SIEM Information Model (ASIM) enables you to use and create source-agnostic content, simplifying your analysis of the data in your Microsoft Sentinel workspace.

For more information, see:

- [Normalization and the Advanced SIEM Information Model (ASIM)](https://aka.ms/AboutASIM)
- [Deploy all of ASIM](https://aka.ms/DeployASIM)
- [ASIM ProcessEvent normalization schema reference](https://aka.ms/ASimProcessEventDoc)

<br>

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FParsers%2FASimProcessEvent%2FARM%2FvimProcessTerminateMicrosoftSecurityEvents%2FvimProcessTerminateMicrosoftSecurityEvents.json) [![Deploy to Azure Gov](https://aka.ms/deploytoazuregovbutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FParsers%2FASimProcessEvent%2FARM%2FvimProcessTerminateMicrosoftSecurityEvents%2FvimProcessTerminateMicrosoftSecurityEvents.json)
