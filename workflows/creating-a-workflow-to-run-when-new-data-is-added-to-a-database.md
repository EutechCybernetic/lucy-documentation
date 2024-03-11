# Creating a Workflow to Run When New Data is Added to a Database

Workflows are automated sequences of actions that connect different applications or services to streamline processes. A workflow typically starts with a trigger and then executes a series of actions in response to that trigger.

A workflow can be set up to trigger when new data is added to a specific database. In general, the system repeatedly monitors the database for new data entries. If new data entry is detected, the workflow is triggered, and a series of predefined actions are executed. These actions can include sending notifications, updating records, and more.

In this tutorial, we will create a simple workflow that automatically sends an email whenever new data is added to a database.

## Creating a Workflow to Run When New Data is Added to a Database

The process of creating a workflow to trigger when new data is added to a database is described in three main steps.

### 1. Creating the Database

As the initial step, we need to have a database created within the selected project/folder.

Find the article here to create a new database:



{% content-ref url="../databases/creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](../databases/creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}



Below is a image of the database we ‘ve created.

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S1.png" alt=""><figcaption><p>Database created</p></figcaption></figure>

### 2. Creating the Workflow

Upon creating the database, we can start creating the workflow using the Workflow editor.

To create the workflow that sends an email when new data is added to the database:

1. On the Lucy app **homepage**, click the **My Work** tab on the left.&#x20;
2. All the folders/projects you have created, as well as those created by others, will be listed.&#x20;
3. Click on the folder to open it.
4. If you cannot locate the folder in the list, type in the folder name under **Search Folders.** From the search results, click on the folder.
5. Inside the folder, click the **Workflows** tab.
6. Click the **+** icon. Workflow editor page will open.
7. Select a **trigger** from the trigger list to start the workflow.
   1. Click **How do you want to trigger your workflow?** box and select the required trigger.
   2.  Click **When someone submitted data to <\<Your Database Name>> Database** trigger.&#x20;

       _<mark style="color:blue;">Note: Upon creating the database, it will be populated in the Database trigger list. However, if you haven't created the database, it won't appear in the trigger list. If the respective folder contains multiple databases (e.g., 2 databases), there will be two database triggers listed under the trigger list.</mark>_
8. Select the block that defines the actions to execute when the workflow is triggered.
   1. Click the **+** icon.
   2. Filter and select blocks by category (e.g., Communications ) or type in the name of the block in the search box.
   3. Pick the **Send Email** block under **Communications**.
9. Configure the **properties** of the Send Email block.
   1. On the Send Email block, click the **arrow** icon to expand the **Properties** section.
   2. Enter the **Subject** of the email.
   3. In the **To** box, type in the recipient’s email address.
   4. In the **Body** box, type in the message to be sent.
   5. Include output from previous blocks (Data items/pills coming from previous blocks in the workflow) to required fields.
      1. Click on the field, _e.g., Body_. A pop-up with a list of data items coming from previous blocks will be displayed.
      2. Select required data from the pop-up to be added in the Body section of the email.
      3. Type the content in the respective field including the selected data items accordingly.
10. Enter a suitable **name** for the Workflow.
11. Click **Save**. Now you have completed creating the workflow. Next step is to test it.

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S2.png" alt=""><figcaption><p>Selecting a Trigger Block screen 1</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S3_1.png" alt=""><figcaption><p>Selecting a Trigger Block screen 2</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S4.png" alt=""><figcaption><p>Selecting an Action block</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S5_2.png" alt=""><figcaption><p>Configuring Properties of Send Email Block</p></figcaption></figure>

### 3. Adding Data to the Database

We’ll create a form to easily add data to the database.

1. On the Lucy app **homepage,** click the **My Work** tab on the left.
2. Search and click the required folder containing the database.
3. Inside your folder, click the **Databases** tab.
4. Search and select the database you’ve created.
5. Hover over it and click the **Edit** icon that displays. Widget designer page will open.
6. Click **Save Widget.**
7. On the pop-up window, click **Open Page** to open the form in a new window.
8. Fill in the form and click **Submit**. Data will be inserted into the database.

After a new data record is added to the database, our workflow will trigger, sending an email to the recipient.

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S6.png" alt=""><figcaption><p>Preview of the Form created to submit data to the database</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S7.png" alt=""><figcaption><p>Data added to the database</p></figcaption></figure>

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S8.png" alt=""><figcaption><p>Preview of the Email sent to the recipient's inbox</p></figcaption></figure>
