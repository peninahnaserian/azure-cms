# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
for a VM:
1. it provides IaaS 
2. one has manages the OS
3.It is more expensive
for a App Service
1.it provides PaaS
2.it is suitable for hosting web apps, RestAPis and mobile backends
3.App Services cost less than VMs do.
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
For my choice I would go with an App Service since we do not need to manage the OS being used. Also we are requiring a HTTP based service for hosting a web app and an App Service is less expensive.Also the ability to scale quickly is less of a concern right now.
The app right now the processing power is sufficient.

### Assess app changes that would change your decision.
When the amount of app users increases there might be a need for scaling thus I might move to a VM.handling the vast increase in the number of users, with separate,dedicated servers, is going to better achieved this way. When the need for scaling processing power arises I might consider moving to a VM.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 