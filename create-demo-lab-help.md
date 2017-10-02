# Create Demo Lab Help Text

These instructions and tips are here to help you create your demo lab. At any time in the process, you can click **Save As Draft** in the bottom-left corner of the window to save your progress and come back to it later. 

For further assistance, send an email to support@qloudable.com.

## Basic Details

In this section, you will provide the basic information about your demo lab. For example, you can give the lab a title, add logos and screenshots, and upload a user manual file.

### Demo Lab Title

In this field, give your demo lab a unique title. This will be the title that customers see when they are browsing demo labs, so make sure it is a title that aligns with your product name appropriately, stands out, and demonstrates what your demo lab does.

![demo lab name gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-name.gif)

### Publisher Name

Enter your official company or organization's name here so customers know who made this demo lab.

![publisher name gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-publisher-name.gif)

### Demo Lab Description

Here you can put a quick description of what your demo lab is and what it does. This will help customers decide if they want to try your demo lab, so be descriptive.

![lab description gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-description.gif)

### Contact Email

Enter the email that will be provided to customers who have questions or concerns. Make sure this email is actively monitored by support staff.

![contact email gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-contact-email.gif)

### Error Email

Enter the email address where you wish to receive error logs and reports for this demo lab.

![error email gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-error-email.gif)

### Demo Lab Icons

Here you can upload up to four images that will serve as the icons for this demo lab. You can also hover over icons you have already uploaded to edit or remove them.

![demo lab icons gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-icons.gif)

### Preview Images

Here you can upload images that will be placed into a slideshow on the demo lab page. Upload screenshots that demonstrate your demo lab in action so that customers know what they can expect. You can also hover over images you have already uploaded to edit or remove them.

![preview images gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-preview-images.gif)

### User Manual

Here you can upload a PDF file or provide a web link to the user manual that will go along with the demo lab. Customers will need these to follow through with the scenarios you have created in the demo lab. 

![user manual gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-user-manual.gif)

### Supporting Documents

Here you can upload or provide a link to any other supporting documents to go along with your demo lab, including white papers, data sheets, or any other documents.

![supporting documents gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-supporting-docs.gif)

###  Videos

Here you can upload a **file** (.mp4) or provide an **embed link** to any videos that you want to be available on the demo lab page showcasing the functionality of your demo lab.

![videos gif](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-videos.gif)

When you are done, click on the **Advanced Details** tab to continue.

## Advanced Details

In this section, you will add and configure advanced details about your demo lab. Keep in mind that the settings here can affect how your demo lab deploys and what your users will experience.

### Demo Lab Duration

This is how long the demo lab will stay active, in minutes. Note the approximate length (in minutes) that it would take a first-timer to complete the demo lab, and enter that number here. This lets the customer know how much of a commitment they have to make to try out your solution.

**Tip:** 60 minutes is generally a good place to start and usually a safe bet, if you are unsure.

![demo lab duration](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_demo-lab-duration.gif)

### Soft Lab Deployment Time

This is the length of time it will take for the demo lab to deploy, in minutes, depending on when your template finishes deploying in the cloud. 

**Soft deployment** is when the lab begins as soon as the template completes its deployment process, which can sometimes occur quicker than expected. We recommend using this option for your demo lab if it only relies on the main template to deploy all necessary components, and there are no additional scripts or processes that need to run for a period of time after the main template is ready.

Note the approximate length (in minutes) that it would take for the demo lab template to deploy, and enter the number here. This lets the customer know how much lead time will be needed before they can try the demo lab.

### Hard Lab Deployment Time

This is the length of time it will take for the demo lab to deploy, in minutes, independent of when your template finishes deploying in the cloud. 

**Hard deployment** is when the lab begins once a specified period of time has passed, regardless of when the template completes its deployment process. We recommend using this option for your demo lab if it relies on additional scripts and/or processes to run after the main templates completes in order to properly deploy all necessary components. This is because sometimes the main template is ready before all of the other scripts have finished their tasks.

Note the approximate length (in minutes) that it would take for the demo lab's template and additional scripts to deploy. This lets the customer know how much lead time will be needed before they can try the demo lab.

### Concurrency Limit

Note the number of demo labs that can be active at the same time.

![concurrency limit](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_demo-lab-concurrency-limit.gif)

### Demo Labs Per User Limit

Enter the number of demo labs each unique user is allowed to deploy. Any attempts to deploy afer this number will be restricted.

![user limit](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_demo-lab-user-limit.gif)

### Deployment Failure Message

Enter the message that will appear when a user's demo lab deployment fails for whatever reason. This message will be viewed by the customer.

**Tip:** A good default failure message is: "Sorry, your demo lab deployment has failed. Please try again later or contact us for support."

![failure message](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_failure-message.gif)

### Concurrency Limit Message

Enter the message that will appear when a user has reached their concurrency limit. This message will be viewed by the customer.

**Tip:** A good default concurrency limit message is: "Sorry, there are too many demo labs active right now. Please wait a bit and try again later. Thanks for your interest!"

![concurrency message](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_concurrency-message.gif)

### Demo Lab Per User Limit Message

Enter the message that will appear when a user reaches their limit of total demo labs deployments. This message will be viewed by the customer.

**Tip:** A good default demo lab per user limit message is: "Sorry, you have reached the maximum number of demo lab deployments allowed. Please contact us for more information."

![user limit message](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_user-limit-message.gif)

### Demo Lab Access Details & Outputs

In this text box, you can add and customize the demo lab access details and template output parameters that are displayed to the user once the demo lab is ready. You can use HTML inline formatting to customize your text (**e.g.** <b>**bold text**</b> and line breaks <br>). 

To dynamically populate this field with the output parameters from the main demo lab template, type the value of the output surrounded by double curly brackets (**e.g.** Here is the password: **{{LabPassword}}** ). This will automatically add the *LabPassword* output parameter from the template to your demo lab access details. 

**Tip:** Make sure you type the output values correctly, and with proper casing.

![outputs](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-ad_outputs.gif)

Click the **Link Cloud Account** tab to continue.

## Link Cloud Account

This section is where you will link your existing cloud account to the demo lab. You will see tiles representing all of your registered cloud services accounts. Click on the one that you want to use to host the demo lab deployments. A green check mark will appear next to the account you have selected.

If you do not already have a cloud account set up, you can get started by using the link below:
[Get Started on Oracle Cloud Infrastructure (OCI)](https://cloud.oracle.com/home)

### Link New Account

If you need to add a new registered account, click the tile labeled **Link New Account**. This will open the fields necessary to link a new cloud account.

![link new account](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_link-new-account.gif)

### Account Name

Enter the name of your cloud account here.

![account name](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_account-name.gif)

### Account Description

Give your account a description to help keep track of which cloud account it is or include any important details about the account.

![account description](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_account-description.gif)

### Tenancy OCID

Enter the tenant OCID of the cloud account. For help understanding what this ID is and how to retrieve it, read [this help article](https://docs.us-phoenix-1.oraclecloud.com/Content/API/Concepts/apisigningkey.htm#How) on Oracle's website.

![tenancy ocid](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_tenancy-ocid.gif)

### User OCID

Enter the user OCID of the cloud account. For help understanding what this ID is and how to retrieve it, read [this help article](https://docs.us-phoenix-1.oraclecloud.com/Content/API/Concepts/apisigningkey.htm#How) on Oracle's website.

![user ocid](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_user-ocid.gif)

### Compartment OCID

Enter the compartment OCID of the cloud account. For help understanding what this ID is and how to retrieve it, read [this help article](https://docs.us-phoenix-1.oraclecloud.com/Content/API/Concepts/apisigningkey.htm#How) on Oracle's website.

![compartment ocid](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_compartment-ocid.gif)

### Fingerprint

Enter the cloud account "fingerprint" here. For help understanding what this value is and how to retrieve it, read [this help article](https://docs.us-phoenix-1.oraclecloud.com/Content/API/Concepts/apisigningkey.htm#How) on Oracle's website.

![fingerprint](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_fingerprint.gif)

### Private Key Path

Enter the file path that leads to your account's private key here. For help understanding what this key is and how to retrieve it, read [this help article](https://docs.us-phoenix-1.oraclecloud.com/Content/API/Concepts/apisigningkey.htm#How) on Oracle's website.

![private key](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-lca_private-key.gif)

When you are done, click **Save** to add this cloud account to your list of available accounts. Once the account is selected, click the **Project Details** tab to continue.

## Project Details

In this section, you can select a project to manage this demo lab with.

**Note:** Projects help manage and maintain demo labs, which are deployed and built using [Terraform](https://www.terraform.io/intro/index.html) templates. To learn more about what Terraform templates are and how they work, please [visit this web page](https://www.terraform.io/intro/index.html). For examples of Terraform templates designed for demo labs, please contact a Qloudable support rep.

### Select Existing Project

If you have already created a project that you want to use to manage this demo lab, you can select it from the **Select an existing project** dropdown near the top of this section.

![select project](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_select-project.gif)

Otherwise, fill out the fields below to create a new project.

### Project Name

Give the project a unique name to stand out from your other projects.

![project name](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-name.gif)

### Project Description

Provide a description for the project and what it does.

![project description](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-description.gif)

### Fetch Project Details from:

Select either a GitHub account or an uploaded .zip file with which you will pull and maintain your project details.

#### GitHub Account

Clicking the GitHub account button creates the GitHub account forms.

![github project](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-details-from-github.gif)

**GitHub Account Name**

Enter the name of the GitHub account you will pull and manage your details from.

![github account name](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-details-github-account-name.gif)

**Select Repo**

Select the specific repository within the listed GitHub account.

![github select repo](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-details-github-select-repo.gif)

**Select Branch**

Select which branch of the listed repository you will pull and manage your details from.

![github select branch](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-details-github-select-branch.gif)

**Select Subfolder**

If applicable, select the subfolder to use within the listed branch.

![github select subfolder](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-details-github-select-subfolder.gif)

#### Upload Project Zip File

Clicking this option creates the **Upload Zip File** button, which prompts you to upload the zip file in question.

![upload zip](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-pd_project-details-upload-zip.gif)

When you are done, click the **Sharing Settings** tab to continue. 

## Sharing & Permissions

In this section, you can configure the user permissions and access levels for your demo lab. For example, you can allow unlimited deployments for certain users by adding them to a "Green List," and/or block certain users from deploying the demo lab by adding them to a "Red List".

### Everyone

Check this option if you want anyone to be able to view and deploy this demo lab via social media or link sharing.

![everyone share](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-sharing_everyone.gif)

### Collaborators

Alternatively, you can set specific collaborators that can see the demo lab, organized by User, Team, Organization, or domain name (email address). Enter the individual email address, or the email domain, and select **Add** to add users.

![collaborators share](https://github.com/qloudable/qloudable-help/blob/master/images/demo-lab-sharing_collaborators.gif)

When everything is done, click **Publish** to create and publish the demo lab.
