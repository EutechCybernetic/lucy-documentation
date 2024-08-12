# Designing the Settings Page

This tutorial explains how to design the Settings page in your mobile app.

## Designing the Settings Page

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. On the mobile screen, click the bottom section to open the properties panel on the right.
3. In the **Configure Tabs** section of the properties panel, locate the Settings tab.
4. Enter an appropriate **Name** for the new tab _(e.g., Profile)_.
5. **Icon:** To change the tab icon, click the icon and select an appropriate one from the Search Icons window.
6. **Type**: Choose the required page type, _e.g., Custom Mobile Page._
7. On the mobile screen, select the Settings Page from the list. A new section labeled 'Click here to configure sections in settings page' will appear on the mobile screen. Click the section.
8. **Setting Group:** A setting group is a broad category that encompasses related settings. It serves as a container for multiple sections. Add a setting group.
   1. In the properties panel, Click the **Add Settings Group** button.
   2. Enter a suitable name for the setting group, _e.g., Account._
   3. Add multiple settings groups as necessary.
9.  **Section:** A section is a smaller grouping of settings within a setting group. It focuses on a specific aspect of the setting group.&#x20;

    **Example:** Within the **Account** setting group, you might have sections like:

    * Personal Details
    * Currency
    * Language
    * Notifications

    Add a new section.

    1. In the properties panel, Click the **Add Tab** button.
    2. Enter a suitable name for the section, _e.g., Personal Details._
    3. In the Icon field, pick a icon for the section.
    4. Pick the required Setting Group.
    5. [**Edit Action:** ](handling-button-click-events.md)Click this button to open the [**Action Editor** window.](handling-button-click-events.md#action-editor-window) This window has five tabs: Open URL, Open Widget, Execute Action, Open Add-on, and Open Mobile Screen. Use these tabs to set what happens when a specific section is clicked.
       1. **Open URL:** You can configure a URL to be opened when specific section is clicked.
       2. **Open Widget:** Used to select a specific widget to be opened when specific section is clicked.
       3. **Execute Action**: Used to run a specific Lucy action. You can select a model, choose an appropriate action, and provide parameters. Additionally, configure the post-action behavior.
       4. **Open Add-on**: Used to configure a specific add-on to be opened when specific section is clicked.
       5. **Open Mobile Screen**: Used to select a predefined mobile screen to be opened when the specific section is clicked.
       6. After configuring the action, click **Done**.
    6. Add more sections.
10. Click **Save** to apply the changes in the mobile app.
11. Open the mobile app to view changes.

<figure><img src="../../.gitbook/assets/Creating Settings page_1-1.png" alt=""><figcaption><p>Designing the settings page</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Settings Page_1.png" alt="" width="353"><figcaption><p>A example of a Settings page</p></figcaption></figure>

## Setting the Page to Open When a Section is Clicked

After designing the structure of the Settings page, link each section to its relevant page. You can set a section to open a webpage, an add-on, a widget, a Lucy action, or a mobile screen.

For example, let's set the Personal Details section to launch a widget displaying the user's personal details.

### Creating the Widget

We'll use the 'Object View' widget template to create a widget that shows user's personal details. Follow these steps to create the widget.

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
      3. Enter a suitable title for the widget. Pick a colour and adjust its size as necessary.
   2. Add a profile picture field.
      1. Under Fields tab on the left, drag and drop the Profile Picture field on to the widget's body section.
   3. Add
10. Click the **Preview** button to preview the design.
11. Once you are happy with the design, click **Save Widget.**

### Linking the Widget to the Respective Section
