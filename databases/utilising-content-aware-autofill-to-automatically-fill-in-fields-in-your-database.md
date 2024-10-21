# Utilising Content-aware Autofill to Automatically Fill in Fields in Your Database

This article explains how to automatically fill in your database fields using the content-aware autofill feature in Lucy.

**Content-aware Autofill** is a powerful feature that uses AI (Artificial Intelligence) to automatically fill in data in a database based on existing columns. Simply provide initial row examples, and subsequently, this feature will fill columns automatically when new data is added or updated.

For instance, let’s create a database to capture employee feedback and use this feature to automatically classify the feedback as 'Good' or 'Bad' and autofill the result in the database.&#x20;

Utilising Content-aware Autofill for database population involves several key steps.

1. [Creating Your Database](utilising-content-aware-autofill-to-automatically-fill-in-fields-in-your-database.md#id-2.-adding-data-into-your-database)
2. [Adding Data into Your Database](utilising-content-aware-autofill-to-automatically-fill-in-fields-in-your-database.md#id-2.-adding-data-into-your-database)
3. [Enabling the Content-aware Autofill in Your Database](utilising-content-aware-autofill-to-automatically-fill-in-fields-in-your-database.md#id-3.-enabling-the-content-aware-autofill-in-your-database)
4. [Testing the Content-Aware Autofill Feature](utilising-content-aware-autofill-to-automatically-fill-in-fields-in-your-database.md#id-4.-testing-the-content-aware-autofill-feature)
5. [Viewing Your Updated Database](utilising-content-aware-autofill-to-automatically-fill-in-fields-in-your-database.md#viewing-your-updated-database)

## <mark style="color:blue;">1. Creating Your Database</mark>

As the initial step, you need to have a database created in the system.&#x20;

Find the article below to create a new database.

{% content-ref url="creating-and-editing-databases/creating-a-database-manually.md" %}
[creating-a-database-manually.md](creating-and-editing-databases/creating-a-database-manually.md)
{% endcontent-ref %}

<figure><img src="../.gitbook/assets/Database example_1.png" alt=""><figcaption><p>Database example</p></figcaption></figure>

## <mark style="color:blue;">2. Adding Data into Your Database</mark>

Next, create a form to easily add sample data into your database.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** we previously created.
7. Hover over the database and click **Edit** icon that appears.
8. Click **Create a Form.**
9. Under the **General** tab on the right, provide a name for the form.
10. Click the **Delete** icon of the corresponding field (e.g., Mood) to remove it from the form.
11. Click **Save Widget**.
12. Click **Open Page** to open the form in a new window.
13. Fill in the form details and click **Submit**.
14. Refresh the page to add more data.
15. Open the database to view and fill in data in the required column.
    1. Within your folder, go to the **Databases** tab.
    2. Search and click on the required database. Entered data will be displayed.
    3. Click the **Edit** button to enter the edit mode in the database.
    4. Fill in the data in the required column _e.g., Mood._

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S1.png" alt=""><figcaption><p>Feedback Form </p></figcaption></figure>

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S2.png" alt="" width="392"><figcaption><p>Entering form details</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S3.png" alt=""><figcaption><p>Previewing the data</p></figcaption></figure>

## <mark style="color:blue;">3. Enabling the Content-Aware Autofill in Your Database</mark>

After creating your database and adding sample data, enable the Content-aware Autofill feature to learn from the given data and automatically populate relevant columns.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. All the folders you have created, as well as those created by others, will be listed.
3. If you cannot locate the folder in the list, type in the folder name under **Search Folders.**
4. Click on the folder you wish to open.
5. Head to the **Databases** tab.
6. Search and click on the **database** created.
7. Hover over the database and click the **Edit** icon to open its edit mode.
8. Enable the **Content Aware Autofill** option.
9. Choose the field you want to look at from the **Choose Raw Text Field** list. In this example, it is the 'Comment' field.
10. Select the **No of Example Rows** you want the autofill feature to use for training.
11. **Columns to AutoFill (Optional)**: Select the field you wish to automatically fill in. In this example, it is the 'Mood' field.
12. Click **Done**.
13. Click **Update Database** to save changes.

## 4. Testing the Content-Aware Autofill Feature

Now, add more examples using the form interface to test the Content-Aware Autofill Feature.

{% hint style="info" %}
You can also add data directly within the specific database.
{% endhint %}

Testing the Content-Aware Autofill Feature

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. Click on the folder you wish to open.
3. Head to the **User Interfaces** tab.
4. Find the form user interface and click on it.
5. The form will be launched in a new page.
6. Enter the form details and click **Submit**.
7. Refresh the page to add more data.

## <mark style="color:blue;">5. Viewing Your Updated Database</mark>

Let's view the database to see the changes.

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. Click on the folder you wish to open.
3. Head to the **Databases** tab.
4. Search and click on the **database** to view it.
5. The 'Mood' field will be auto filled based on the data you entered.

<figure><img src="../.gitbook/assets/Content-aware Autofill to Automatically Populate Your Database_S4.png" alt=""><figcaption><p>A preview of the updated database</p></figcaption></figure>

Watch this video to learn how to automatically fill in your database fields using the content-aware autofill feature in Lucy.

{% embed url="https://drive.google.com/file/d/1wAziJi3li2xhJnA0eb2vSGZ9FNdWOZNM/view?usp=drive_link" %}
