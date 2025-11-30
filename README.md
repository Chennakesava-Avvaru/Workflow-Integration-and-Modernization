# Workflow-Integration-and-Modernization
- The main agenda of this project is to transform **Swiss Re legacy workflows from Informatica to Azure**, introducing a modernized data integration system that enhanced efficiency and scalability.
## Architecture
- We have followed this 5 step approach to make the transition smooth.
![Approach](https://github.com/Chennakesava-Avvaru/Workflow-Integration-and-Modernization/blob/main/SR_WM.drawio.png)
- This is the High level design where we have divided the workflow based on the Data volume, Run frequency and complexity
- We have utilized Azure Logic Apps for scenarios involving low data volume and high run frequency, as this option is cost-effective. For complex data sources, we primarily use Azure Data Factory. Additionally, we have employed Azure Function Apps with Python, which offer greater convenience and flexibility.
![mainArc](https://github.com/Chennakesava-Avvaru/Workflow-Integration-and-Modernization/blob/main/WM_ARC_MAIN.png)
- Low level design of the Business workflows in the logic app.
![lowleveldesign](https://github.com/Chennakesava-Avvaru/Workflow-Integration-and-Modernization/blob/main/WM_ARC.drawio.png)
- Developed and deployed 28 workflows into production with high availability and efficiency. Most of them are in a low-code environment, requiring no maintenance in the future.
## Technologies Used
- Azure Logic Apps
- Azure Data Factory
- Azure Function Apps
- Python
- Liquid Templates
- REST API
- ADLS Gen2
- Azure Blob Storage
- Log Analytics
- Application Insights
- Kibana
- Azure DevOps
## Achivements & contributions
- Achieved a 60% reduction in data processing time and established a scalable and secured workflows integration system leveraging Azure Cloud.
- Gained good knowledge and appreciation from the stakeholders.
- Played multiple role as Azure architect, Azure Integration Engineer, DevOps engineer.
- Provided mentorship to junior engineers.
