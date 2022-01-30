# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I chose the web app service because it is a lower cost than a virtual machine. The web app also does not require the high maintenance and upkeep work involved if I were to create and deploy the app on a VM which would require a lot more headache and security configurations for the virtual machine. The web app is a lot quicker and easier to create, implement, and deploy. It is very easy for my workflow to upload my project changes to my GitHub repository and then for the web app to take the project and deploy it to the web application. The availability of the web app seems the same as compared to the VM but based on the extra user configuration and risks, I think the web app would have greater reliability and availability to be up and running, versus if it were on a VM that needed to do restarts and OS maintenance. The scalability seems just right for my web application. It is small and I can always scale up in the future if needed as lower cost and configuration work if I were to need to scale on a VM. Based on the costs, scalability, availability, and workflow analysis I chose the web app service to implement for my project requirements.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would consider potentially using a virtual machine if they had more "cookie-cutter" or "plug-in-play" template functionality for web app services and continuous deployments as compared to the PAS web app Azure service offerings that streamline changes and deployments from a GitHub repo or other sources. A virtual machine takes a lot of thoughtful planning and work to make it secure and up-to-date, so I do not see this changing in the near future. 