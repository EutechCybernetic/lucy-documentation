# Designing the Settings Page

This tutorial explains how to design the Settings page in your mobile app. By default, you will have a Settings page and you can customise it as necessary.

{% hint style="info" %}
Your mobile app comes with a default homepage and settings page that you can customise to suit your preferences.
{% endhint %}

Let's customise the Settings page of your mobile app using the Lucy web app.

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. On the mobile screen, click the bottom navigation bar to open the properties panel on the right.
3. In the **Configure Tabs** section of the properties panel, locate the Settings tab.
4. Enter an appropriate **Name** for the new tab _(e.g., Profile)_.
5. **Icon:** To change the tab icon, click the icon and select an appropriate one from the Search Icons window.
6. **Type**: Choose the required page type to open when the respective tab is clicked, _e.g., Custom Mobile Page._
7. On the mobile screen, select the Settings Page from the list. A new section labeled 'Click here to configure sections in settings page' will appear on the mobile screen. Click the section.
8. **Setting Group:** A settings group helps to group related sections. Add a setting group.
   1. In the properties panel, Click the **Add Settings Group** button.
   2. Enter a suitable name for the setting group, _e.g., Account._
   3. Add multiple settings groups as necessary.
9.  **Section:** A section is a smaller grouping of settings within a setting group. It focuses on a specific aspect of the setting group.&#x20;

    **Example:** In the **Account** setting group, you can have sections like:

    * Personal Details
    * Currency
    * Language
    * Notifications

    Add a new section.

    1. In the properties panel, Click the **Add Tab** button.
    2. Enter a suitable name for the section, _e.g., Personal Details._
    3. In the **Icon** field, pick a icon for the section.
    4. Pick the required Setting Group, _e.g., Account._
    5. Set the page to open when the section is clicked.
       1. Click the **Edit Action** button to open the [**Action Editor** window.](handling-button-click-events.md#action-editor-window) This window has five tabs: Open URL, Open Widget, Execute Action, Open Add-on, and Open Mobile Screen. Use these tabs to set what happens when a specific section is clicked.
          1. **Open URL:** You can configure a URL to be opened when specific section is clicked.
          2. **Open Widget:** Used to select a specific widget to be opened when specific section is clicked.
          3. **Execute Action**: Used to run a specific Lucy action. You can select a model, choose an appropriate action, and provide parameters. Additionally, configure the post-action behavior.
          4. **Open Add-on**: Used to configure a specific add-on to be opened when specific section is clicked.
          5. **Open Mobile Screen**: Used to select a predefined mobile screen to be opened when the specific section is clicked.
    6. After configuring the action, click **Done**.
    7. Add more setting groups and sections.
10. Click **Save** to apply the changes in the mobile app.
11. Open the mobile app to view the changes.

<figure><img src="../../.gitbook/assets/Creating Settings page_1-1.png" alt=""><figcaption><p>Designing the settings page</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Settings Page_1.png" alt="" width="353"><figcaption><p>A example of a Settings page</p></figcaption></figure>

## Launching a Page When a Section is Clicked

After designing the structure of the Settings page, link each section to its relevant page. You can set a section to open a webpage, open an existing add-on, open a widget, execute a Lucy action, or open a certain mobile screen.

For example, let's set the Personal Details section of the Settings page to launch a widget for displaying and editing users' personal details.

### Creating the Widget

We'll use the 'Object View' widget template to create the widget.

Follow these steps to create the widget.

1. On the app homepage, go to the **My Work** tab.
2. Search and click the required folder and open it.
3. Go to the **User Interfaces** tab.
4. Click the **+** button.
5. Choose the **Start from Scratch** option.
6. Pick the desired type of **Widget Template,** _e.g., Object View._
7. Click **Edit this Template** to open it on its widget designer page.
8. Give a name for the widget.
   1. Go to the **General** tab on the right.
   2. In the **Name** box, type in a suitable name.
9. Customise the properties of the widget.
   1. Customise the header section.
      1. Click the header section of the widget to open its properties panel on the right.
      2. In the properties panel, go to the **Title** section.
      3. **Text** field: Enter a suitable title for the widget. Pick a colour and adjust its size as necessary.
   2. Set to add a profile picture.
      1. Under the Fields tab on the left, drag and drop the Profile Picture field on to the blue highlighted area.
      2. Provide a name for the field and Click Done.
      3. Customise the profile picture field as necessary from the properties panel.
   3. Add a field to add the name.
      1. Under the Fields tab on the left, drag and drop the Name Input field on to the blue highlighted area.
      2. Name the field and Click Done.
      3. Use the Properties panel to customise the field as necessary.
   4. Add a field to add the Email address.
      1. Under the Fields tab on the left, drag and drop the Email Input field on to the blue highlighted area.
      2. Name the field and Click Done.
      3. Use the Properties panel to customise the field as necessary.
   5. Add a field to set Gender.
      1. Under the Fields tab on the left, drag and drop the Toggle Input field on to the blue highlighted area.
      2. Name the field and Click Done.
      3. Click on the respective field to open its properties panel.
      4. Under the Options section, click the Add New Option button.
      5. A text field will be displayed. Type the gender in the provided text field _e.g., Male._
      6. Click on the icon image to pick a appropriate icon.
      7. Repeat the steps 5-4 to 5-6 to add more options.
   6. Set a field to pick the nationality.
      1. Under the Fields tab on the left, drag and drop the Toggle Input field on to the blue highlighted area.
      2. Name the field and Click Done.
      3. Click the field to open its properties panel on the right.
      4. Bind a data source to the widget to fetch data.
         1. Under the Options section, select the **Get Options from a Data source** option. Bind a Source button will be displayed.
         2. Click **Bind a Source.** You can pick a lucy action or a database as the data source.
         3. Bind a database.
            1. Go to the **Databases** tab.&#x20;
            2. Search and select the required database.
            3. Click **Select this Source** button. A preview of your data will be displayed in a table.
            4. Format the data if necessary. If you are satisfied with the data preview, click **Looks Good.** The selected database will be displayed.
            5. **Label Field:** Select name as the label.
      5. Under the Dropdown section, in the **Value** field, type in the nationality to be displayed to user. Remove the text in the Placeholder and Default Text fields.
   7. Set a field to enter age.
      1. Under the Fields tab on the left, drag and drop the Number Input field on to the blue highlighted area.
      2. Name the field and Click Done.
      3. In the properties panel, go to the Number Input section.
      4. **Value**: Type in the age to be displayed to user.&#x20;
      5. Type in the **Min Value** and the **Max Value** for the age input.
   8. Set a field to enter mobile number.
      1. Under the Fields tab on the left, drag and drop the Phone No Input field on to the blue highlighted area.
      2. Name the field and Click Done.
      3. In the properties panel, go to the Text Input section.
      4. Default Country: Type in the country name to set as the default country. Once set, it will display the country code along with the flag.
10. Click the **Preview** button to preview the design.
11. Once you are happy with the design, click **Save Widget.**

#### **Adding Horizontal Containers**

Use horizontal containers to store fields horizontally when designing your widget.

Steps to Add a Horizontal Container

1. On the app homepage, go to the **My Work** tab.
2. Search and click the required folder and open it.
3. Go to the **User Interfaces** tab.
4. Click the **+** button.
5. Choose the **Start from Scratch** option.
6. Pick the desired type of **Widget Template,** _e.g., Object View._
7. Click **Edit this Template** to open it on its widget designer page.
8. Give a name for the widget.
   1. Go to the **General** tab on the right.
   2. In the **Name** box, type in a suitable name.
9. Add a horizontal container.
   1. Under the Fields tab on the left, drag and drop the **Horizontal Container** field on to the blue highlighted area.
   2. Pick a field and drag and drop it to the right or left column of the horizontal container.
   3. Continue adding more fields to each column.
10. Click the **Preview** button to preview the design.
11. Once you are happy with the design, click **Save Widget.**\


<figure><img src="../../.gitbook/assets/Horizontal Container_3.png" alt=""><figcaption><p>Horizontal Container example</p></figcaption></figure>

### Linking the Widget

After building the widget, link it to the required section (_e.g., Personal Details) o_n the settings page.

Steps to Link the Widget

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. On the mobile screen, click the Settings tab to open the settings page.
3. Click the designed area with the sections and section groups to open its properties panel.
4. &#x20;In the properties panel, go to the Personal Details section.
5. Click **Edit Action.**
6. Go to the **Open Widget** tab.
7. Pick the designed widget and click **Done.**
8. Click **Save** to apply the changes. The selected widget will now display in your mobile app under the required tab.
9. Open the mobile app's settings page and click the required section.

<figure><img src="../../.gitbook/assets/Launch a Prebuilt Widget_1.png" alt=""><figcaption><p>Launching the predesigned widget</p></figcaption></figure>



For more information on connecting a section to a page, find the article here:

{% content-ref url="handling-button-click-events.md" %}
[handling-button-click-events.md](handling-button-click-events.md)
{% endcontent-ref %}
