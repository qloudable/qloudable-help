# Create Stack Help
These instructions and tips are here to help you create a Stack solution offer. Stacks are packaged offers that include a solution template (e.g. Terraform) and product plans/tiers. Customers can buy/use Stacks to deploy cloud software in their own cloud tenants. Keep reading to get guidance and tips for completing a Stack offer, step-by-step.

Click the **Help** button in the Stack creation wizard to access this help text anytime. 

Click **Save as Draft** anytime to save this Stack as a draft and exit. Once you have completed all of the required fields and sections successfully, you will be able to add a plan, then submit it for publishing. 

**Note:** In order to publish a Stack, you are required to have set up a Payout account. We recommend doing this first. Go to **Settings > Payout** to set this up, if you have not done so already.

For further assistance, send an email to stack-support@qloudable.com.

## Primary Information
This intro section appears first, and is where you can input some basic details for your solution, and then choose to either continue with the creation wizard or save it for now as a draft to continue later. The fields required here are the same as what is found in the **Basic Details** Section (see below).

## Basic Details
In this section, you will provide the basic information about your Stack solution. Here is where you give it a title, add logos and screenshots, upload an architecture diagram, and list the components.

### Stack Category
Use this drop-down menu to select relevant technology and/or industry categories for your solution. If you don't see a category that represents your solution, please let us know via the support chat widget or email at stack-support@qloudable.com.

### Stack Name
Enter a title for this solution. Depending on the solution, appropriate titles are often based on the name of the product, verison, and/or intended use case. 

### Publisher Name
Enter the name of the Publisher who owns this solution here (in most cases, this is you or your company's name).

### Short Description
Enter a short description for this solution (50 words maximum). This should be a very brief summary of your solution. This description is displayed on the previews for this solution on the web, as well as at the very top of the solution landing page, below the title.

### Long Description 
Enter a long description for your solution that provides a full summary of the solution and what it does (500 words maximum). This description is shown on the solution landing page, and should give customers a strong understanding of what the solution is about, what it deploys, and its purpose.

### Contact Email
This is the email address that will recieve a notification when an end user requests to contact the Publisher of this solution. We recommend adding a group email alias here, but it is ultimately up to you how to field contact requests from end users. Our support team might also contact you at this address occasionally for any issues that may arise.

### Error Email
This is the email address that will receive failure notifications and reports whenever a solution fails to deploy for whatever reason. We recommend using your support team's email alias or a lead engineer supporting this solution.

### Stack Icons
Stack icons are used to show the associated brands and technology with the Stack solution (e.g. company logo, software logo). Clicking the upload button will allow you to browse for files on your computer. Select 1-4 icons that can be used to represent the brands, products, or applications in this Stack solution.

**Note:** Image files will look best in .PNG format, with transparent backgrounds, and within 300 x 300 pixels.

### Preview Images
Preview images are screenshots or other images that give a preview of what the solution will look like once deployed. Clicking the upload button will allow you to browse for files on your computer. Select 1-4 images (*Warning:* small images may become stretched). Again, screenshots usually are best, but you can also include things like marketing graphics and diagrams here. These images will be displayed in a slideshow on the solution landing page.

### Architecture Diagram
This is where you add the architecture diagram image file for this solution. Make sure you use a clear and professional looking diagram so end users can understand the how the components in this solution are connected, and how they are deployed. Clicking the upload button will allow you to browse for files on your computer. Upload a .PNG file of decent size.

**Note:** Recommended size is 1000x700 pixels (WxH).

### User Manual
Upload a user manual document (AKA "deployment guide") for the solution here, or provide a web URL to the document. This document is used to provide guidance and information to end users about the deployment, including steps to walk through the solution, breakdowns of the components involved, support information, and more. Clicking the upload button will allow you to browse for files on your computer, or you can paste a web URL in the text box shown, then click "Add".

**Note:** Uploaded document files must be .PDF format.

### Additional Documents and Links
Upload document files or paste web URLs to additional documentation like datasheets, white papers, pricing guides, etc. This is for supplementary content relevant to the solution that customers might be interested in.

**Note:** Uploaded document files must be .PDF format.

### Videos
Upload video files or paste an embed URL to a video hosted on the web (e.g. YouTube) to add a video to the solution landing page. Some recommendations for videos include: product demos, webinars, deployment tutorials, and other videos relevant to this Stack solution. We recommend using a web URL here, as it will help with page load times.

To get an embed URL, go to your video hosted on the web and select the option to "Share" or "Embed." Then, copy the URL from the embed code. (**Example:** "https://www.youtube.com/embed/Ngva0OUP_UU")

### Stack Components
Add a list of the components included in this solution. Each line break (i.e. hit "Enter") in the text box shows as a bullet list item on the solution landing page. We recommend adding a list of all the core components in the deployment, such as virtual machines, load balancers, databases, etc.

### Deployment Steps
Add a list of steps for the end user to follow when deploying this solution. Each line break (i.e. hit "Enter) in the text box shows as a bullet list item on the solution landing page. If there are any specific actions users need to take when deploying this solution, make sure to include them here.

### Enable Template Change Requests
Enable this option to allow customers to send the Publisher a request (via email) to customize this solution template. This appears as a button at the top of the solution landing page. Click the button to enable this option for customers.

## Advanced Details
In this section, you will add and configure some advanced details for your Stack deployment offer.

### Allow Template Download
Enable this option to allow end users to download a copy of this Stack's solution template. Click the button to enable this option. End users will be able to click a link on the solution landing page to download a copy of the solution template file.

### Deployment Failure Message
Enter a brief, personalized message that will be displayed to end users if the solution deployment fails for whatever reason.

**Tip:** A recommended failure message to use is: "Sorry, the solution deployment has failed. Please try again later or contact us for support."

### Deployment Success Message
Enter a brief, personalized message that will be displayed to end users once the solution deployment completes successfully.

**Tip:** A recommended success message to use is: "Good news! The solution deployment was completed successfully. Please enjoy the solution, and contact us if you have any questions."

### Publisher EULA
Select the EULA (End User License Agreement) you would like to be associated with this solution deployment from the drop-down menu. If you don't see any options, then you may want to click "Save as Draft" and go add a new EULA to your account.

**Hint:** You can add EULAs to your account by navigating to "Settings" from the main dashboard.

## Project Details
In this section, you can select a project to assign to this Stack solution template. A project contains a solution template (i.e. Terraform) and any other required scripts.

**Note:** Projects help manage and maintain Stack solutions, and are deployed and built using [Terraform](https://www.terraform.io/intro/index.html) templates. To learn more about what Terraform templates are and how they work, please [visit this web page](https://www.terraform.io/intro/index.html). For examples of Terraform templates designed for Stack deployments, please contact stack-support@qloudable.com.

### Select Existing Project
If you have already created a project that you want to use to manage this solution, you can select it from the **Select an existing project** dropdown near the top of this section.

Otherwise, fill out the fields at the bottom of this section to create and save a new project.

### Variables
Once you have added a project, which contains a solution template, use this section to specify any particular input variables that you want to allow end users to customize, or customize them yourself. These variables are pulled from the solution template. You may need to click the expand arrow to show the variables.

## Create a new project:
The below fields are if you decide to create a new project.

### Project Name
Give the project a unique name that is relevant to this Stack deployment (e.g. include version numbers, etc.).

### Project Description
Provide a description for the project, and/or about the solution it manages.

### Fetch Project Details from:
Select either a GitHub account or an uploaded .zip file with which you will pull and maintain your project details.

**Note:** As of September 2018, the GitHub integration is still an upcoming feature. Sorry for any inconvenience.

#### Upload Project Zip File
Clicking this option shows the **Upload Zip File** button, which prompts you to browse files on your computer and upload the zip file containing your solution template.

## Link Cloud Account
This section is where you will link your existing cloud account to the Stack solution, if you want to give specific end users the option to use a sponsored cloud account instead of their own. If left blank, the end user will provide their own cloud account to deploy the Stack with (this is the most common approach).

You will see tiles representing all of your registered cloud services accounts (or none, if you have none). Click on the one that you want to use to host the Stack deployments. A green check mark will appear next to the account you have selected.

**Reminder:** Using your own cloud account is optional, so don't treat this as a requirement.

### Users
Add any specific users by email address who will have access to the sponsored cloud account (e.g. "user@companyemail.com"). Only the users listed here will get access to the sponsored account.

### Domain Access
Add any specific email domains who will have access to the sponsored cloud account (e.g. "companyemail.com"). Users who register with an email address matching this domain will be granted access to the sponsored account.

## Share
In this section, you can configure the user permissions and access levels for the solution. For example, you can allow unlimited deployments for certain users by adding them to a "Green List," and/or block certain users from deploying the solution by adding them to a "Red List".

### Everyone
Check this option if you want everyone to be able to view and deploy this solution. This is effectively the same as making the solution landing page public. 

### Collaborators
Alternatively, you can set specific collaborators who can access and deploy the solution, organized by User, Team, Organization, or domain name (email address). Enter the individual email address, or the email domain, and select **Add** to add users.

## Continue to Add Plan
Once you have completed all of the prior sections, click the **Continue to add plan** link in the bottom right corner of the Stack creation wizard.

In the following section, you can add one or more Plans for your Stack solution offer. "Plans" are bundled with the solution, and each Plan can contain different configurations or features, and can be set at various prices and billing intervals. With each deployment of the solution, a customer will need to purchase a plan. Plans can be free, or paid, and as a Publisher it is up to you what plans you offer for this solution.

## Add Plan(s)
In this section, add as many Plans as you need for this solution. You can add a name, description, and pricing details for each plan. You can add features to these plans in the next section.

Click **+ADD** once all the required fields are completed to add a Plan, Feature, or Add-On. Once added, they will appear in a list below their section. You can delete or edit them from this list.

### Name
Enter a name for the plan. This can include details about the configuration or use case.

**Examples:** "Free Plan", "Premium Option", "Multi-VM (10 nodes)", etc.

### Description
Enter a short description for this plan. This will be shown on the solution landing page and give customers a quick understanding of what this plan contains.

**Example:** "This plan is for advanced users, and contains a load balancer and larger VM sizes."

### Type
Select a payment type for this plan. The options are:
* **Free:** No payment is required for this plan.
* **Once:** Customers make a one-time payment to purchase this plan.
* **Recurring:** Customers pay a subscription for this plan. Frequency is determined after this step.

### Billing Interval
If you selected the "Recurring" Type for this plan, then you can select an interval here for when customers will need to pay. The two options are:
* **Monthly:** customers pay each month to use this plan.
* **Annually:** customers pay each year to use this plan.

### Amount ($)
Enter the price for the plan here. This is of course determined by many factors, including your internal pricing model and the billing interval you selected for this plan. (Price is in United States Dollars)

### Trial Period
If you would like to add a Trial Period to your plan, where customers can try the plan and all its features before purchasing, you may add the duration here (in days).

## Add Feature(s)
Each Plan comes with a set of Features. These can be deployed resources, functionalities, or even services your company provides -- like 24-hour support, for example. 

### Name
Enter a name for the feature. As mentioned before, this can be a type of cloud resource, a size/amount, a product feature, etc.

### Description
Enter a short description for this feature.

## Map Plan(s), feature(s), and Project Variable(s)
Once you have added some Plans and Features, a new dialogue box will appear with some check boxes shown. This chart is for Publishers to assign the Features to the appropriate Plan(s). For example, "Feature 1" might be available across all Plans, but "Feature 2" might only be available in your paid Plan. You can set those assignments here.

Below the checkboxes, you should also see a list of Project Variables. Thease are the variables pulled from the solution template added to the Stack solution offer. You can choose to customize the values of these variable for each respective Plan.

For example: Plan 1 may have the "vmSize" variable set to "A1" since it's for small use cases, and Plan 2 may have the "vmSize" variable set to "D4" since it's for heavier use cases.

Next to each variable listed is an "eye" icon. This is a button that can be enabled or disabled to control whether the customer can see these variables and their values when they deploy the solution. A blue open eye means that variable and its value will be shown to the customer(s). A gray crossed-out eye icon means that variable will be hidden from customers.

## Add Add-On(s)
Add-Ons are extra features or services that customers can add on to their purchase of your solution. These work similarly to Plans, but they are optional for the solution deployment.

### Name
Enter a name for the add-on.

### Description
Enter a short description for the add-on.

### Type
Select a payment type for this add-on. The options are:
* **Free:** No payment is required for this add-on.
* **Once:** Customers make a one-time payment to purchase this add-on.
* **Recurring:** Customers pay a subscription for this add-on. Frequency is determined after this step.

### Billing Interval
If you selected the "Recurring" Type for this add-on, then you can select an interval here for when customers will need to pay. The two options are:
* **Monthly:** customers pay each month to use this add-on.
* **Annually:** customers pay each year to use this add-on.

### Amount ($)
Enter the price for the add-on here. This is of course determined by many factors, including your internal pricing model and the billing interval you selected for this add-on. (Price is in United States Dollars)

## Publish
Once you are done with all the previous steps, you should be able to click **Publish** in the bottom right hand corner to submit your solution for publishing.

**Note:** You may see an error message that says you need to create a payout account before publishing your lab. In this event, click **Save as Draft** for the Stack and exit. A payout account is required for publishing a Stack, so there is a way for you to receive payouts from customer pruchases. Go to **Settings > Payout** to set up your payout account.

## Additional Help
If you have any other questions or need assistance, please contact Qloudable support with the chat widget or via email at stack-support@qloudable.com. Thank you!
