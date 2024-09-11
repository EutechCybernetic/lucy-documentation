# Creating a Workflow to Run When New Data is Added into a Database

Workflows are automated sequences of actions that connect different applications or services to streamline processes. A workflow typically starts with a trigger and then executes a series of actions in response to that trigger.

A workflow can be set up to trigger when new data is added into a specific database. In general, the system repeatedly monitors the database for new data entries. If new data entry is detected, the workflow is triggered, and a series of predefined actions are executed. These actions can include sending notifications, updating records, and more.

In this tutorial, we will create a simple workflow that automatically sends an email whenever new data is added into a database.

The process of creating a workflow to trigger when new data is added into a database is described in three main steps.

### 1. Creating the Database

As the initial step, we need to have a database created within the selected folder.

Let's manually create our database.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. Click on the required folder to open it.
4. If you cannot locate the folder in the list, type in the folder name under **Search Folders.** From the search results, click on the desired folder to open it.
5. Go to the **Databases** tab.
6. Click **+** button and pick **Create Manually** option.
7. Enter a meaningful **name** for your database.
8. Click **Continue**.
9. Click **Skip this step** to manually enter database fields.
10. Add required database fields.
    1. In the **Field Name** box, type in the name of the field, _e.g., Complaint._
    2. When you enter the field name, the system will automatically determine its type, such as '_Text'._ Change the type if necessary.
    3. To add more fields, click **Add New Field.**
11. After adding database fields, click **Go to next Step.**
12. Click **Create New Database**. An empty database will be created and listed under Databases tab of the respective folder.

Below is a image of the database we have created.

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S1_1.png" alt=""><figcaption><p>Database preview</p></figcaption></figure>

### 2. Creating the Workflow

Upon creating the database, we can start creating the workflow using the Workflow editor. Design your workflow by starting from a trigger block and connecting action blocks to it.

To create the workflow that sends an email when new data is added to the database:

1. On the Lucy app **homepage**, click the **My Work** tab on the left.&#x20;
2. All the folders you have created, as well as those created by others, will be listed.&#x20;
3. Click on the folder to open it.
4. If you cannot locate the folder in the list, type in the folder name under **Search Folders.** From the search results, click on the folder.
5. Inside the folder, click the **Workflows** tab.
6. Click the **+** icon. Workflow editor page will open.
7. Select the database trigger from the trigger list to start the workflow.
   1. Click the **How do you want to trigger your workflow?** box.
   2.  Click **When someone submitted data to <\<Your Database Name>> Database** trigger.&#x20;

       _<mark style="color:blue;">Note: Upon creating the database, it will be populated in the Database trigger list. However, if you haven't created the database, it won't appear in the trigger list. If the respective folder contains multiple databases (e.g., two databases), there will be two database triggers listed under the trigger list.</mark>_
   3. The selected trigger will display on the workflow editor page.
8. Select the block that defines the action to execute when the workflow is triggered.
   1. Click the **+** icon of the selected trigger.
   2. Filter and select blocks by category (e.g., Communications ) or type in the block name in the search box.
   3. Pick the required block, _e.g., Send Email._
9. Configure the properties of the Send Email block.
   1. On the Send Email block, click the **arrow** icon ![](<../.gitbook/assets/image (11).png>)to open its **Properties** section.
   2. Enter the **Subject** of the email. Use Pills to customise the subject as necessary. These pills are used in input fields and originate from previous blocks in your workflow.
   3. In the **To** box, type in the recipient’s email address.
   4. In the **Body** box, type the message to be sent. Use Pills and format the message as necessary.
      1. To add pills, click on the Body box. A list of pills will appear in a pop-up window.
      2. Select required pills from the pop-up to be added in the Body section of the email.
10. Enter a suitable **name** for the Workflow.
11. Click **Save**.

{% hint style="info" %}
You can find all your saved workflows under the **Workflows** tab within the respective folder.
{% endhint %}

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S2.png" alt=""><figcaption><p>Selecting a Trigger Block screen 1</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S3_1.png" alt=""><figcaption><p>Selecting a Trigger Block screen 2</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S4.png" alt=""><figcaption><p>Selecting an Action block</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S5_2.png" alt=""><figcaption><p>Configuring Properties of Send Email Block</p></figcaption></figure>

### 3. Testing/Executing the Workflow

The last step is to test the workflow by adding a data record into the database.

1. On the Lucy app **homepage**, click the **My Work** tab on the left.&#x20;
2. All the folders you have created, as well as those created by others, will be listed.&#x20;
3. Click on the folder to open it.
4. Within the folder, navigate to the **Workflows** tab.
5. Locate and click on your workflow to open it on the Workflow editor page.
6. Click the ![](<../.gitbook/assets/image (5).png>)Run button. Execute Workflow form opens.
7. Complete the form and click **Execute.** This will execute the workflow and insert the data into the database.
8. Open your database to preview the changes. When a new record is added to the database, our workflow will send an email to the recipient.

{% hint style="success" %}
You can add data records through the database as well. (Navigate to the Databases tab in the folder and select the required database to open it.)
{% endhint %}

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S6_1.png" alt=""><figcaption><p>Execute Workflow form</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S7.png" alt=""><figcaption><p>New data record added</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S8.png" alt=""><figcaption><p>Preview of the Email sent to the recipient's inbox</p></figcaption></figure>

Watch the video below on creating a workflow to run when new data is added to a database from the ground up to gain a better understanding.

{% embed url="https://drive.google.com/file/d/15765XXjtkG7AqIJIsEFbHXCUVwk5OlDx/view?usp=sharing" %}
