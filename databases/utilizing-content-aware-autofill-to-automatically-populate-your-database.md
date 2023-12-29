# Utilizing Content-aware Autofill to Automatically Populate Your Database

This article explains how to automatically populate data into your database using Content-aware Autofill.

**Content-aware Autofill** is a powerful feature that uses AI (Artificial Intelligence) to automatically fill in data in a database based on existing columns. All that's required is the provision of some examples for the initial rows, and subsequently, this feature will fill in columns automatically when new data is inserted.

For instance, let’s create a database to capture employee feedback and use this feature to automatically classify the feedback as good or bad and autofill the result in the database. We will have the Name, Email, Comment and Mood as our database fields.

Utilizing Content-aware Autofill for database population involves several key steps.

1. Create Your Database
2. Add Examples to Your database
3. Enable Content-aware Autofill in Your Database

## <mark style="color:blue;">1. Create Your Database</mark>

As the initial step, you need to have a database created in the system.&#x20;

Find the article below to create a new database.

{% content-ref url="creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}

## <mark style="color:blue;">2. Add Examples to Your Database</mark>

The next step is to add some sample data entries to your database. Let’s create a form to easily add data.

1. On the app homepage, go to the **My Work** tab on the left sidebar.
2. Search and click on the **folder** you want to open.
3. Head to the **Databases** tab.
4. Search and click on the **database** we previously created.
5. Hover over the database and click **Edit** icon that appears.
6. Click **Create a Form.**
7. On the Mood field, click **Delete** icon (We will need this field later).
8. Click **Save Widget**.
9. Click **Open Page** to open the form in a new window.
10. Fill in the form details and click **Submit**.
11. Refresh the page to add more examples.
12. Enter **Good** or **Bad** appropriately for each example in the **Mood** column.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S1.png" alt=""><figcaption><p>Feedback form designed</p></figcaption></figure>



<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S2.png" alt="" width="392"><figcaption><p>Filling the form</p></figcaption></figure>

This is how your examples will be visible in the database.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S3.png" alt=""><figcaption><p>Data entries added to the database</p></figcaption></figure>

## <mark style="color:blue;">3. Enable Content-aware Autofill in Your Database</mark>

The last step is to enable Content-aware Autofill in your database.

1. On the app homepage, go to the **My Work** tab on the left sidebar.
2. Search and click on the **folder** you want to open.
3. Head to the **Databases** tab.
4. Search and click on the **database** created.
5. Hover over the database and click **Edit** icon to open its edit mode.
6. Enable the **Content Aware Auto Fill** option.
7. Choose the field you want to look at from the **Choose Raw Text Field** list. In this example, it is the Comment field.
8. Select the **No of Example rows** to be checked.
9. Select the field you wish to fill in based on the previously selected Field. In this example, it is the Mood field.
10. Click **Done**.
11. Click **Update Database** to save changes.

Now add few more examples to the database from the form interface and view the database to see the changes.

## <mark style="color:blue;">Viewing Your Updated Database</mark>

Let's view the database to see the changes.

1. On the app homepage, go to the **My Work** tab on the left sidebar.
2. Search and click on the **folder** you want to open.
3. Head to the **Databases** tab.
4. Search and click on the **database** to view it.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S4.png" alt=""><figcaption><p>Viewing the updated database</p></figcaption></figure>
