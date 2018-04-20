# Create Application Gateway and Traffic Mgr in front of two Azure Web Apps.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-application-gateway-webapps%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-application-gateway-webapps%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template does the following deployments: Deploys 2 Web Application Gateways in front of the 2 Web Apps. Then it combines the DNS entries for both the App Gateways into a Traffic MGR for Global redundancy.