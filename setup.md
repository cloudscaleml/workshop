# Setup Steps

### 1. Create an Azure account [here](https://azure.microsoft.com/en-us/free/?WT.mc_id=globalai-workshop-cxa)

### 2. Go to www.microsoftazurepass.com to redeem a $100 Azure Credit code that was sent to you via email.

### 3. Create Azure Machine Learninge Resources with the Deploy to Azure Button below
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcassieview%2Fignite-learning-paths-training-aiml%2Fmaster%2Faiml30%2Fdeploy.json" rel="nofollow">
 <img src="https://camo.githubusercontent.com/9285dd3998997a0835869065bb15e5d500475034/687474703a2f2f617a7572656465706c6f792e6e65742f6465706c6f79627574746f6e2e706e67" data-canonical-src="http://azuredeploy.net/deploybutton.png" style="max-width:100%;">
</a>

### 4. Create Additional Resources Needed
Once you have created the base Azure Machine Learning Service Workspace we need to add additional compute resources.
## Create Compute Targets
*  Create `Machine Learning Compute`
    * Click on the nav `Compute`
    * Click `New`
    * Enter a name for the resource
    * Select `Machine Learning Compute` from the dropdown
    * Select the machine size
    * Enter the min and max nodes (recommend min of 0 and max of 5)
    * Click `Create`
    ![Create Compute](https://globaleventcdn.blob.core.windows.net/assets/aiml/aiml30/CreateMlCompute.gif)

* Create Notebook Virtual Machine
    * Click on the `Notebook VM` nav
    * Click `New`
    * Give the notebook a unique name
    * Select the VM size (NC6 is always good)
    * Click `Create`
    ![Create VM](https://globaleventcdn.blob.core.windows.net/assets/aiml/aiml30/CreateNotebookVM.gif)

## Optional Kuberetes Cluster
* Create Kubernetes Compute
    * Click on the nav `Compute`
    * Click `New`
    * Enter a name for the resource
    * Select `Kubernetes Service` from the dropdown
    * Click `Create`
    ![Create Kubernetes](https://globaleventcdn.blob.core.windows.net/assets/aiml/aiml30/CreateKubService.gif)
