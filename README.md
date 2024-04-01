# Python App für den Betreib als Azure App Service

Das Repository enthält die DBWE Blog Version 12 aus dem Projekt [DBWE](https://github.com/iten-engineering/dbwe/tree/main) für die Installation als Azure App Service.

Cloud Deployment 

1. [Installation der Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli)

2. Optional: Create [GitHub](https://github.com/) Account and [Repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories) 

3. Add Source Code from [Blog 12 Sample](https://github.com/iten-engineering/dbwe/tree/main/flask/blog12) 

4. Rename blob.py to app.py and create a [requirements.txt](https://github.com/iten-engineering/dbwe-blog/blob/main/requirements.txt) file without the libraries:
   - python
   - conda
   - ipykernel
   - mariadb

5. Run your App locally accoring the **Step 1** of the [Quickstart: Deploy Python App as Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-portal%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli) guide.

6. [Create an Azure Free Account](https://azure.microsoft.com/en-us/free) or Pay-as-you-go Subscription on Azure and follow the tutorials 1 - 10 of the **Get started on Azure Portal** section.

7. On Azure create a **Resource Group** for your App Service.

8. Then, search for App Service and create App Service according **Step 2** of the [Quickstart: Deploy Python App as Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-portal%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli) guide.

9. Download and Intall the [Azure Tools for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack).

10. Deploy your application code to Azure according the **Step 3, Deploy using VS Code** of the [Quickstart: Deploy Python App as Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-portal%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli) guide.

11. Browse the app accorrding **Step 4** of the guide and check the Logs in case of an error.

12. At the end, don't forget to stop your App Service again.