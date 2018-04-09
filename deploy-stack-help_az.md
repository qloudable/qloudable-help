
# Deploy Stack Help
These instructions and tips are here to help you deploy a Stack solution. At any time in the process, you can click the Save As Draft button to save your progress and come back to this deployment later.

Click **View Help** to access this help text. Click **Save as Draft** anytime to save this Stack deployment as a draft and exit. Once you have completed all of the required fields and sections successfully, you will be able to click to **Review** button to submit your Stack for deployment in your cloud account.

Click the **Next** and **Previous** buttons along the bottom of the interface to navigate between the sections, or click on the section headers themselves.

## Deployment Details
In this section, you will add the basic details for your Stack deployment -- as well as view the template project and version associated with this deployment.

### Deployment Name
Enter a name for your deployment here. This will only be visible to you and any collaborators you share it with, so we suggest giving it a meaningful name related to whatever your use case for this solution is.

### Short Description
Provide a short description of the Stack deployment and its intended purpose. 

### Project Associated
This shows the current version of the solution template associated with this Stack offer. If there are multiple versions of the Stack solution available, you will be able to open the **Project Associated** drop-down menu and select one. Otherwise, this will be locked by the Publisher.

## Deployment Variables
In this section, the input variables from the Stack solution template will be displayed for users to review, and edit if necessary/desired.

Variables will be displayes in a list, with the name/title of the variable on the left, and the value of that variable on the right. If desired, you can edit the values of these variables to be whatever you prefer by clicking the right-side text box and editing the text. Refer to the User Manual for this solution to clarify whether any variables will need tp be changed here.

## Link Cloud Account
This section is where users will select an existing cloud subscription to deploy this Stack solution in, or create/add a new cloud account to do so.

You will see tiles representing all of your registered cloud subscriptions. Click on the one that you want to use to host the Stack deployment. A green check mark will appear next to the account you have selected.

If you don't have an Azure cloud account yet, you can create one [here](https://azure.microsoft.com/en-us/free/).

### Link An Account
To add a new cloud account, click the **Link An Account+** button and enter the following fields:

#### Account Name
Enter the name of your cloud subscription here.

#### Account Description
Give your account a description to help keep track of which cloud subscription it is or include any important details about the account.

#### Tenant ID
Enter the tenant ID of the cloud account. To find this value, log in to the [Azure Portal](https://portal.azure.com) and navigate to your Azure tenant. Go to the **Azure Active Directory** section, then select the **Properties** menu option. Here you should see the Directory ID, which is what you will enter for the Tenant ID.

#### App ID
Enter the App ID of the cloud account. To find this value, log in to the [Azure Portal](https://portal.azure.com) and navigate to your Azure tenant. Go to the **Azure Active Directory** section, then select the **App Registartions** menu option. Select the AD App you will be using for this deployment, and select "Properties." Here you will see the Application ID.

If you do not have any AD Apps available, click **+ New App Registration** and create a new Web App, then use that.

#### Secret Key
Enter the App ID of the cloud account. To find this value, log in to the [Azure Portal](https://portal.azure.com) and navigate to your Azure tenant. Go to the **Azure Active Directory** section, then select the **App Registartions** menu option. Select the AD App you will be using for this deployment, and select "Settings," and then select "**Keys**." Since keys are encrypted after creation, you will need to generate a new key here, then copy its value. May sure you save this key value somewhere safe, as you will not be able to see it again after this.

If you do not have any AD Apps available, click **+ New App Registration** and create a new Web App, then use that.

When you are done, click **Save** to add this cloud account to your list of available accounts.

## Deployment Options
In this final section, you can configure some additional options for your Stack solution deployment.

### Rollback on Failure
Enable this feature to make the Stack solution rollback to a previous state if any technical or deployment failures occur.

## Review
Once you have filled out all the required fields, click **Review**. This will take you to an overview page where you will see a list of all the configuration options you provided for this Stack deployment. Please take a moment to review all these to ensure they are correct, then select **Confirm** once you are ready to deploy.

You will be presented with a 2nd confirmation pop-up, asking if you are sure you want to proceed. Click 'yes' to proceed with deployment.

## Deployment Console
This console is where you can view the details of your in-progress or live deployment. 

### Runs
**Runs** are displayed along the left side of the interface, which represent the deployments of this solution to your cloud environment. The first deployment will be the **Plan** phase. Once this completes, review the log details and click on **Confirm and Apply** once you are ready to fully deploy the Stack.

### Project
This section will show you the project details associated with this Stack solution, including the template version and input variables showcased earlier. 

### Settings
In this section, you can review and change any applicable settings for the deployment (e.g. Rollback on Failure).

This is also where you can select to **Delete** the current deployment. Only select this button if you are *absolutely sure* you wish to delete the deployment permanently.
