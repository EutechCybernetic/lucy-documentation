# Designing the Settings Page

This tutorial explains how to design the Settings page in your mobile app.

To design the Settings Page

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

