# Automating Form Submission with Slack Notification

You can create a workflow to automate sending a Slack notification when a user submits a form. The notification is sent to the user with the linked slack account.

By automating form submissions, businesses can save time, improve efficiency, and ensure consistent data quality.

{% hint style="info" %}
Familiarity with creating [folders ](../folders/creating-a-new-folder.md)and [databases ](../databases/creating-and-editing-databases/)is recommended to accelerate your learning process.
{% endhint %}

{% hint style="info" %}
Folders serve as containers designed to store and organize your work, such as notes, databases, user interfaces, and workflows.
{% endhint %}

Here are steps to create a workflow to automate sending a Slack notification when a user submits a form.

1. [Creating a Form](automating-form-submission-with-slack-notification.md#id-1-creating-a-form)
2. [Configuring the Automation](automating-form-submission-with-slack-notification.md#id-2-configuring-the-automation)
3. [Testing the Automation](automating-form-submission-with-slack-notification.md#id-3-testing-the-automation)

### 1) Creating a Form

To get started, we'll need a form to collect user feedback. If you haven't already created one, refer to this article for guidance on designing and building a form that effectively captures the information you need.

{% content-ref url="../user-interfaces/designing-a-user-interface/designing-a-user-interface-to-capture-user-feedback.md" %}
[designing-a-user-interface-to-capture-user-feedback.md](../user-interfaces/designing-a-user-interface/designing-a-user-interface-to-capture-user-feedback.md)
{% endcontent-ref %}

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption><p>Creating a form to capture user feedback</p></figcaption></figure>

When designing a form, you can always start from scratch, yet it is generally advisable to start creating a form from a database.

### 2) Creating the Automation

After creating the form, follow these steps to create an automation to send a Slack notification when a user submit a form in Lucy.&#x20;

1. On the Lucy app **homepage**, go to the **My Work** tab.
2. A list of folders appear. Locate and select the folder containing your form user interface.
3. Go to the **User Interfaces** tab.
4. Locate your form. Mouse hover over it and click the **Edit** icon that appears.
5. Your form will open on the widget designer page.
6. Click the **Share** button on the top right and go to the Automations section.
7. Click the **When someone submits data, post a message on Slack** option.
8. Link your Slack account.
   1. Click **Link your account.**
   2. Complete the authentication process.
9. Enter a channel name.
10. Click **Create Automation.**

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption><p>Creating the automation</p></figcaption></figure>

### 3) Testing the Automation

Now, let's test the automation by submitting the form.

1. On the Lucy app **homepage**, go to the **My Work** tab.
2. A list of folders appear. Locate and select the required folder to open it.
3. Go to the **User Interfaces** tab.
4. Locate your User Interface.
5. Click on the user interface to open it in a new window.
6. Fill out the form details and click **Submit**.
7. After a while, you will receive a message on Slack.



<figure><img src="../.gitbook/assets/image (36).png" alt="" width="426"><figcaption><p>Submitting form details</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption><p>Receive a message on Slack</p></figcaption></figure>
