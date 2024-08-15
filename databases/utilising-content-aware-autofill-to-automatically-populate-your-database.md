# Utilising Content-aware Autofill to Automatically Populate Your Database

This article explains how to automatically populate data into your database using Content-aware Autofill.

**Content-aware Autofill** is a powerful feature that uses AI (Artificial Intelligence) to automatically fill in data in a database based on existing columns. All that's required is the provision of some examples for the initial rows, and subsequently, this feature will fill in columns automatically when new data is inserted.

For instance, let’s create a database to capture employee feedback and use this feature to automatically classify the feedback as good or bad and autofill the result in the database. We will have the Name, Email, Comment and Mood as our database fields.

Utilising Content-aware Autofill for database population involves several key steps.

1. [Create Your Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-1.-create-your-database)
2. [Add Data to Your Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-2.-add-data-to-your-database)
3. [Enable Content-aware Autofill in Your Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-3.-enable-content-aware-autofill-in-your-database)
4. [Viewing Your Updated Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#viewing-your-updated-database)

## <mark style="color:blue;">1. Create Your Database</mark>

As the initial step, you need to have a database created in the system.&#x20;

Find the article below to create a new database.

{% content-ref url="creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}

## <mark style="color:blue;">2. Add Data to Your Database</mark>

The next step is to add some sample data entries to your database. Let’s create a form to easily add data.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** we previously created.
7. Hover over the database and click **Edit** icon that appears.
8. Click **Create a Form.**
9. In the Mood field, click **Delete** icon (We will need this field later).
10. Click **Save Widget**.
11. Click **Open Page** to open the form in a new window.
12. Fill in the form details and click **Submit**.
13. Refresh the page to add more examples.
14. Open the database you've created.
    1. To open the database, go to the **My Work** tab on the left sidebar on the app homepage.
    2. Search and click on the **folder** you want to open.
    3. Head to the **Databases** tab.
    4. Search and click on the database.&#x20;
    5. Fill in the **Mood** column for each example added (enter **Good** or **Bad** appropriately for each example).

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S1.png" alt=""><figcaption><p>Feedback Form </p></figcaption></figure>



<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S2.png" alt="" width="392"><figcaption><p>Filling the Form</p></figcaption></figure>

This is how your examples will be visible in the database.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S3.png" alt=""><figcaption><p>Data entries added to the Database</p></figcaption></figure>

## <mark style="color:blue;">3. Enable Content-aware Autofill in Your Database</mark>

The last step is to enable Content-aware Autofill in your database.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** created.
7. Hover over the database and click **Edit** icon to open its edit mode.
8. Enable the **Content Aware Auto Fill** option.
9. Choose the field you want to look at from the **Choose Raw Text Field** list. In this example, it is the Comment field.
10. Select the **No of Example rows** to be checked.
11. **Columns To AutoFill (Optional)**: This option is used to select the field you wish to fill in. In this example, it is the Mood field.
12. Click **Done**.
13. Click **Update Database** to save changes.

Now add few more examples to the database from the form interface and view the database to see the changes.

## <mark style="color:blue;">Viewing Your Updated Database</mark>

Let's view the database to see the changes.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** to view it.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S4.png" alt=""><figcaption><p>Viewing the updated Database</p></figcaption></figure>
