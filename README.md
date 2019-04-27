# Deploy Python apps to the cloud using a single [Azure CLI](http://aka.ms/cli) command 
This demo deploys the Python Flask app in this repository using [az webapp up](http://aka.ms/azwebappup). To try this at home, goto http://shell.azure.com and run the following commands. You can also run this locally from the Azure CLI (http://aka.ms/cli) and [VSCode](http://aka.ms/vscode) -  
# Deploy the app using az webapp up  
    $ git clone <TODO> myPythonapp
    $ cd myPythonapp
    $ az webapp up --name myPythonapp --location centralus
# Make changes and redeploy the app
    $ code application.py 
    $ az webapp up --name myPythonapp --location centralus   

# Contributing
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
