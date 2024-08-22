# Creating a Workflow to Run When an Email is Received

Automating tasks can greatly improve workflow efficiency. One effective approach is setting up a workflow that initiates when an email is received.

In this article, we will see how to create a workflow to run when an email is received using an example.

Here are the basic steps of creating a workflow to run when an email is received.

1. Setting Up Email Forwarding
2. Creating the Workflow
3. Testing the Workflow

## 1) Setting Up Email Forwarding

Generally, we cannot directly listen to incoming emails. However, we can configure forwarding of incoming emails to another address. Once we have a forwarding email address in place, we can set up email forwarding.&#x20;

{% hint style="info" %}
Before setting up email forwarding, ensure you have created a forwarding email address in this format '<\<Your organization name>>**@inbox.lucyhq.com**' (e.g., collins\_k.eutech@inbox.lucyhq.com).
{% endhint %}



Steps to Set up Email Forwarding

1. Log in to your Gmail account that you want to forward emails from.
2. In the top right, click **Settings** and click **See all settings.**
3. Click the **Forwarding and POP/IMAP** tab.
4. In the "Forwarding" section, click **Add a forwarding address**.
5. Enter the email address you want to forward emails to _e.g., collins\_k.eutech@inbox.lucyhq.com._
6. Click **Next**. Complete the Google verification process.&#x20;
7. Click **Proceed** and Click **OK**.
8. A confirmation link will be sent to the email address that you want to forward emails from. Click the link in that message.
9. Go back to the settings page for the Gmail account you want to forward messages from, and refresh your browser.
10. Click the **Forwarding and POP/IMAP** tab.
11. In the "Forwarding" section, select **Forward a copy of incoming mail to.**
12. Choose what you want to happen with the Gmail copy of your emails. We recommend Keep Gmail's copy in the Inbox.
13. Click **Save Changes.**

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
   3. Enter the email address that you want to forward emails to.
   4. Click **Use this email address.** The trigger block will be added and displayed on the workflow editor page.
7. Add the block that defines the action to execute when the workflow is triggered.
   1. Click the **+** icon of the trigger block.
   2. Select the required action block.



## 3) Testing the Workflow









{% hint style="info" %}
All your saved workflows will be listed under the **Workflows** tab within the respective folder.
{% endhint %}
