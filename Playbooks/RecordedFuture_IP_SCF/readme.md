# Recorded Future - IP - Command and Control Security Control Feed
author: Adrian Porcescu, Recorded Future

These playbooks leverage the Recorded Future API to automate the ingestion of Recorded Future IP [Command and Control - Security Control Feed](https://support.recordedfuture.com/hc/en-us/articles/360024113434-Security-Control-Feed-Command-and-Control), into the ThreatIntelligenceIndicator table, for prevention (block) actions in Microsoft Defender ATP. For additional information please visit [Recorded Future](https://www.recordedfuture.com/integrations/azure/).

Note: Due to internal Microsoft Logic Apps dependencies, please deploy first the ImportToSentinel playbook before the IndicatorProcessor one.


Links to deploy the RecordedFuture_IP_SCF_IndicatorProcessor playbook template:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FRecordedFuture_IP_SCF%2FRecordedFuture_IP_SCF_IndicatorProcessor.json" target="_blank">
	<img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FRecordedFuture_IP_SCF%2FRecordedFuture_IP_SCF_IndicatorProcessor.json" target="_blank">
	<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>

Links to deploy the RecordedFuture_IP_SCF_ImportToDefenderATP playbook template:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FRecordedFuture_IP_SCF%2FRecordedFuture_IP_SCF_ImportToDefenderATP.json" target="_blank">
	<img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Sentinel%2Fmaster%2FPlaybooks%2FRecordedFuture_IP_SCF%2FRecordedFuture_IP_SCF_ImportToDefenderATP.json" target="_blank">
	<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>