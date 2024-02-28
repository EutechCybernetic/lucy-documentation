# Creating a Workflow that triggers when New Data is added to a Database

Workflows are automated sequences of actions that connect different applications or services to streamline processes. A workflow typically starts with a trigger and then executes a series of actions in response to that trigger.

A workflow can be set up to trigger when new data is added to a specific database. In general, the system repeatedly monitors the database for new data entries. If new data entry is detected, the workflow is triggered, and a series of predefined actions are executed. These actions can include sending notifications, updating records, and more.

In this tutorial, we will create a simple workflow that automatically sends an email whenever new data is added to a database.

## Creating a Workflow to Run When New Data is Added to a Database

The process of creating a workflow to trigger when new data is added to a database is described in three main steps.

### Creating a Database

As the initial step, we need to have a database created within the selected project/folder.

Find the article here to create a new database:



{% content-ref url="../databases/creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](../databases/creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}



Below is a image of the database we ‘ve created.

<figure><img src="../.gitbook/assets/CreatingAWorkfloWhen NewDataIsaddedToADatabase_S1.png" alt=""><figcaption><p>Database Preview</p></figcaption></figure>

### Creating the Workflow
