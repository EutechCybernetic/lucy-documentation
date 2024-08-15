# Utilising Content-Aware Autofill to Automatically Populate Your Database

This article explains how to automatically populate data into your database using Content-aware Autofill.

**Content-aware Autofill** is a powerful feature that uses AI (Artificial Intelligence) to automatically fill in data in a database based on existing columns. All that's required is the provision of some examples for the initial rows, and subsequently, this feature will fill in columns automatically when new data is inserted.

For instance, let’s create a database to capture employee feedback and use this feature to automatically classify the feedback as good or bad and autofill the result in the database. We will have the Name, Email, Comment and Mood as our database fields.

Utilising Content-aware Autofill for database population involves several key steps.

1. [Create Your Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-1.-create-your-database)
2. [Add Data to Your Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-2.-add-data-to-your-database)
3. [Enable Content-aware Autofill in Your Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-3.-enable-content-aware-autofill-in-your-database)
4. [Testing the Content-Aware Autofill Feature](utilising-content-aware-autofill-to-automatically-populate-your-database.md#id-4.-testing-the-content-aware-autofill-feature)
5. [Viewing Your Updated Database](utilising-content-aware-autofill-to-automatically-populate-your-database.md#viewing-your-updated-database)

## <mark style="color:blue;">1. Create Your Database</mark>

As the initial step, you need to have a database created in the system.&#x20;

Find the article below to create a new database.

{% content-ref url="creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}

<figure><img src="../.gitbook/assets/Database example_1.png" alt=""><figcaption><p>Database example</p></figcaption></figure>

## <mark style="color:blue;">2. Add Data to Your Database</mark>

Next, create a form to easily add sample data to your database.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** we previously created.
7. Hover over the database and click **Edit** icon that appears.
8. Click **Create a Form.**
9. Under the **General** tab on the right, provide a name for the widget.
10. Click **Save Widget**.
11. Click **Open Page** to open the form in a new window.
12. Fill in the form details and click **Submit**.
13. Refresh the page to add more data.
14. Open the database to view data.
    1. Within your folder, go to the **Databases** tab.
    2. Search and click on the required database. Entered data will be displayed.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S1.png" alt=""><figcaption><p>Feedback Form </p></figcaption></figure>

## <mark style="color:blue;">3. Enable Content-Aware Autofill in Your Database</mark>

After creating your database and adding sample data, enable the Content-aware Autofill feature in your database.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** created.
7. Hover over the database and click the **Edit** icon to open its edit mode.
8. Enable the **Content Aware Autofill** option.
9. Choose the field you want to look at from the **Choose Raw Text Field** list. In this example, it is the 'Comment' field.
10. Select the **No of Example Rows** to be checked.
11. **Columns to AutoFill (Optional)**: This option is used to select the field you wish to fill in. In this example, it is the 'Mood' field.
12. Click **Done**.
13. Click **Update Database** to save changes.

## 4. Testing the Content-Aware Autofill Feature

Now, add more examples using the form interface to test the Content-Aware Autofill Feature.

To add more data

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. Click on the folder you wish to open.
3. Head to the **User Interfaces** tab.
4. Find the form user interface we previously designed and hover your cursor over it.
5. Click the **Edit** icon that appears. This will launch your form on the widget designer page.
6. Click the **Delete** icon of the corresponding field (e.g., Mood) to remove it from the widget.
7. Click **Save Widget.**
8. Open the form to add data.
   1. Click **Share** and click **Open Widget** button. Your form will open in a new window.
   2. Enter the form details and click **Submit**.
   3. Refresh the page to add more data.
9. Click **Share** and click **Open Widget** button.

## <mark style="color:blue;">5. Viewing Your Updated Database</mark>

Let's view the database to see the changes.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** to view it.
7. The 'Mood' field will be autofilled based on the data you entered.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S4.png" alt=""><figcaption><p>A preview of the updated database</p></figcaption></figure>
