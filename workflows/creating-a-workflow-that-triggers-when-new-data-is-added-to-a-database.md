# Creating a Workflow that Triggers When New Data is Added to a Database

Workflows are automated sequences of actions that connect different applications or services to streamline processes. A workflow typically starts with a trigger and then executes a series of actions in response to that trigger.

A workflow can be set up to trigger when new data is added to a specific database. In general, the system repeatedly monitors the database for new data entries. If new data entry is detected, the workflow is triggered, and a series of predefined actions are executed. These actions can include sending notifications, updating records, and more.

In this tutorial, we will create a simple workflow that automatically sends an email whenever new data is added to a database.

## Creating a Workflow to Run When New Data is Added to a Database

The process of creating a workflow to trigger when new data is added to a database is described in three main steps.

### Creating the Database

As the initial step, we need to have a database created within the selected project/folder.

Find the article here to create a new database:



{% content-ref url="../databases/creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](../databases/creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}



Below is a image of the database we ‘ve created.

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S1.png" alt=""><figcaption><p>Database Preview</p></figcaption></figure>

### Creating the Workflow

Upon creating the database, we can start creating the workflow using the Workflow editor.

To create the workflow that sends an email when new data is added to the database:

1. On Lucy app **homepage**, click on the **My Work** tab on the left.&#x20;
2. Search and click on the required folder containing the database.
3. Inside the folder, click the **Workflows** tab.
4. Click the **+** icon. Workflow editor page will open.
5. Select a trigger to start the workflow.
   1. Click **How do you want to trigger your workflow?** box to select the required trigger.
   2.  Click **When someone submitted data to <\<Your Database Name>> Database** option.&#x20;

       _<mark style="color:blue;">Note: You need to create the database to be populated under Database triggers. If the respective folder contains multiple databases (e.g., 2 databases), there will be two database triggers listed.</mark>_
6. Select the block that defines the actions to execute when the workflow is triggered:
   1. Click the **+** icon.
   2. Filter and select blocks by category (e.g., Communications ) or type in the name of the block in the search box.
   3. Pick the **Send Email** block under **Communications**.
7. Configure the **properties** of the Send Email block.
