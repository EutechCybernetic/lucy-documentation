# Creating a Workflow to Run When an Email is Received

Automating tasks can greatly improve workflow efficiency. One effective approach is setting up a workflow that initiates when an email is received.

In this article, we will see how to set up a workflow automation to take incoming emails and send it to a database.

Here are the basic steps of creating a workflow to run when an email is received.

1. Setting Up Email Forwarding
2. Creating the Workflow
3. Testing the Workflow

## 1) Setting Up Email Forwarding

Generally, we cannot directly listen to incoming emails. However, we can configure forwarding of incoming emails to another address. Once we have a forwarding email address in place, we can set up email forwarding.&#x20;

{% hint style="info" %}
The forwarding email address should follow this format: your name.organization name@inbox.lucyhq.com. For example, _collins.eutech@inbox.lucyhq.com._

Ensure it ends with '**.organization name@inbox.lucyhq.com'.**
{% endhint %}

Steps to Set up Email Forwarding

1. Log in to your Gmail account that you want to forward emails from.
2. In the top right, click **Settings** and click **See all settings.**
3. Click the **Forwarding and POP/IMAP** tab.
4. In the "Forwarding" section, click **Add a forwarding address**.
5. Enter the email address you want to forward emails to _e.g., collins.eutech@inbox.lucyhq.com._
6. Click **Next**. Complete the Google verification process.&#x20;
7. Click **Proceed** and Click **OK**.
8. A confirmation link will be sent to the email address that you want to forward emails from. Click the link in that message.
9. Click **Confirm.**
10. Go back to the settings page for the Gmail account you want to forward messages from, and refresh your browser.
11. Click the **Forwarding and POP/IMAP** tab.
12. In the "Forwarding" section, select **Forward a copy of incoming mail to** and it will automatically pick your forwarding email address.
13. Choose what you want to happen with the Gmail copy of your emails. We recommend **Keep Gmail's copy in the Inbox.**
14. Click **Save Changes.**

## 2) Creating the Workflow

Next, let's create the workflow.

1. On the Lucy app **homepage**, click the **My Work** tab on the left.&#x20;
2. All the folders you have created, as well as those created by others, will be listed.&#x20;
3. Click on the desired folder.
4. Inside the folder, click the **Workflows** tab.
5. Click the **+** icon. Workflow editor page will open.
6. Select the email trigger and configure it.
   1. Click the **How do you want to trigger your workflow?** box.
   2. Pick **When someone send a email** trigger from the list.
   3. Enter the email address that you want to forward emails to, e.g., _collins.eutech@inbox.lucyhq.com._
   4. Click **Use this email address.** The trigger block will be added and displayed on the workflow editor page.
7. Add the block that defines the action to execute when the workflow is triggered.
   1. Click the **+** icon of the trigger block.
   2. Click on the **Databases and Analytics** category and pick **Insert into Database** block. The selected block will be added and displayed.
   3. Click the **arrow** icon ![](<../.gitbook/assets/image (11).png>)to open **Insert into Database** block's properties section.
      1. Select the Database you wish to insert data you receive.
      2. Once the database is selected, its fields will be displayed.
      3. Add Pills to the required fields. Pills originate from previous blocks added in the workflow, and you can use them in input fields.
         1. Click on a field and a list of pills will appear in a pop-up window. Select required pills from the pop-up to be added in the field.
         2. Customise each field as necessary.
8. Provide a suitable **name** for the workflow in the text box on the top left.
9. Click **Save**.



## 3) Testing the Workflow









{% hint style="info" %}
All your saved workflows will be listed under the **Workflows** tab within the respective folder.
{% endhint %}
