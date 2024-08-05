# Linking a Widget to a Tab

This article covers building a widget and linking it to a specific tab in your mobile app. Learn how to link a preconfigured widget to a specific tab for display upon clicking.

First, we'll build our widget using the Search Widget Template. This template lets you configure multiple tabs, each connected to a data source to display specific information. The data source can originate from either the MongoDB collection or Lucy Actions. After selecting a data source, you can even customise the information shown under each tab by mapping UI elements to the selected data source values.



{% hint style="info" %}
Before following this tutorial, ensure you are familiar with [creating folders](../../../folders/creating-a-new-folder.md), [databases](../../../databases/creating-and-editing-databases/), and Lucy Actions.
{% endhint %}

## Building the Widget

In this example, we will use an existing database as the data source.

To build a widget:

1. On the app homepage, go to the **My Work** tab.
2. Search and click the required folder and open it.
3. Go to the **User Interfaces** tab.
4. Click the **+** button.
5. Choose the **Start from Scratch** option.
6. Pick the desired type of **Widget Template,** _e.g., Search Widget._
7. Click **Edit this Template** to open the template on its widget designer page.
8. Give a name for the widget.
   1. Go to **General** tab on the right.
   2. In the **Name** box, type in a suitable name.
9. Customise the properties of the widget.
   1. Click the header section of the widget. Its properties panel will open.
   2. Pick a background colour for the header section or you can select a background image.
   3. Select a background image.
      1. In the background image field, click the **Search** icon.
      2. Select a background image from the gallery.
      3. **Upload your image** button: You can also upload your own image by clicking this button.
      4. The selected background will be applied to the header.
   4. Change the Background Position and the Background Size if necessary.
   5. Add and Configure Tabs in the widget.
      1. Under **Search Tabs** section, in the Tab 1 box, type a appropriate name for the first tab.
      2. Click the **Add Column** button to add more tabs.
      3. If you do not wish to add tabs, deselect the Show Tabs option under Display Options.![](<../../../.gitbook/assets/image (7).png>)
   6. Bind a data source to each tab to display information:
      1. In the widget, navigate to the required tab and click the **Bind a Source** button.
      2. Choose either an existing Lucy Action or a database_. For example, let's bind a database._
      3. Go to the **Databases** tab.
      4. Search and select the required database.
      5. Click **Select this Source.**
      6. Format the data as required, _e.g., filtering data_
      7. Click **Looks Good**. Now the selected database will be displayed under Source field and will be linked to the respective tab.
   7. Map the database properties/values to required UI elements.
      1. Add a database value to the Image Field.
         1. In the properties panel, go to Image section and select the Image Type as Image.
         2. In the Image Field, a JSON expression will be displayed. Remove the code and pick the required value from the Available Values pop up window. The Available Values pop up window lists all the values retrieved from the selected database.
         3. The selected value will be applied and displayed in the Image Field. ![](<../../../.gitbook/assets/image (2).png>)
      2. Add a database value to the Title Field.
         1. In the properties panel, go to the Title section.
         2. In the Title Field, a JSON expression will be displayed. Remove the code and pick the required value from the Available Values pop up window. The Available Values pop up window lists all the values retrieved from the selected database.
         3. The selected value will be applied and displayed in the Title Field. ![](<../../../.gitbook/assets/image (3).png>)
      3. Add a database value to the Sub Title Field.
         1. In the properties panel, go to the  Sub Title section.
         2. In the Sub Title Field, a JSON expression will be displayed. Remove the code and pick the required value from the Available Values pop up window. The Available Values pop up window lists all the values retrieved from the selected database.
         3. The selected value will be applied and displayed in the Sub Title Field. ![](<../../../.gitbook/assets/image (4).png>)
      4. Configure the top labels and bottom labels if necessary.
         1. In the properties panel, go to the Top Label section.
         2. Click Add New Item.&#x20;
         3. In the Text field, Remove the 'My label' text.
         4. Select the suitable database value from the  Available Values pop up window or you can just enter a label.
         5. Click the Icon field and pick an appropriate icon for the label.
         6. Pick a icon colour.
         7. Select how you want to display the label (Normal or Pill).
         8. Add more labels as necessary.
         9. In the properties panel, go to the Bottom Label section. Repeat steps 4-1 to 4-8 to add bottom labels.
      5. Customise the UI elements as necessary, such as changing the title colour, size, etc.
10. Click **Save Widget** to save the changes. Now your widget will be saved under the User Interfaces tab within the folder.

<figure><img src="../../../.gitbook/assets/Search Widget template_1.png" alt=""><figcaption><p>Search Widget Template opened on the Widget Designer page</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Search Widget template_3.png" alt=""><figcaption><p>A preview of the designed widget</p></figcaption></figure>

## Linking the Widget to a Tab in Your Mobile App

After building our widget, let's link it to a tab in the mobile app.

Click here to learn more about adding and configuring a tab in your mobile app.

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the Bottom Tab Bar Navigation.
3. In the Bottom Tab Bar Navigation, click the required tab.
4. Under **Configure Tabs** section, locate the tab you want to link the widget.
5. Select the **Type** as **Widget.**
6. Click the **Select a Widget** button on the mobile screen.
7. Pick the required widget from the list (widget names will appear in the list).&#x20;
8. Click **Save** to apply the changes. The selected widget will now display in your mobile app under the required tab.

<figure><img src="../../../.gitbook/assets/Widget example_2.jpeg" alt="" width="375"><figcaption><p>A preview of the designed widget displayed in the mobile app</p></figcaption></figure>

