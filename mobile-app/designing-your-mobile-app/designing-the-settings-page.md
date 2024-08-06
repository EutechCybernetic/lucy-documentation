# Designing the Settings Page

This tutorial explains how to design the Settings page in your mobile app. The Settings page is an example of a Custom Mobile Page screen type.

To design the Settings Page

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. On the mobile screen, click the bottom section to open the properties panel on the right.
3. In the **Configure Tabs** section of the properties panel, click the **Add Tab** button.
4. A new tab will be added along with an icon in the bottom tab bar navigation.
5. Enter an appropriate **Name** for the new tab _(e.g., Profile)_.
6. To change the tab icon, click the icon and select an appropriate one from the Search Icons window.
7. **Type**: Choose Custom Mobile Page as the screen type.
8. **Enter custom UI or select one:** On the mobile screen, select the Settings Page from the list.
9. A new section labeled 'Click here to configure sections in settings page' will appear on the mobile screen. Click the section.
10. **Setting Group:** A setting group is a broad category that encompasses related settings. It serves as a container for multiple sections. Add a Setting Group.
    1. In the properties panel, Click the **Add Settings Group** button.
    2. Enter a suitable name for the setting group, _e.g., Account._
    3. Add multiple settings groups.
11. **Section:** A section is a smaller grouping of settings within a setting group. It focuses on a specific aspect of the setting group.&#x20;

    _**Example:** Within the **Account** setting group, you might have sections like:_

    * _Personal Details_
    * _Currency_
    * _Language_
    * _Notifications_

    Add a new section.

    1. In the properties panel, Click the **Add Tab** button.
    2. Enter a suitable name for the section, _e.g., Personal Details._
    3. In the Icon field, pick a icon for the section.
    4. Pick the required Setting Group.
    5. **Edit Action:** Used to define the action to be executed when specific section is clicked. Define an action.
       1. Click the **Edit Action** button to open the Action Editor window. Action Editor window provides five tabs: Open URL, Open Widget, Execute Action, Open Add-on and Open Mobile Screen.
       2. **Open URL:** You can configure a URL to be opened when specific section is clicked.
       3. **Open Widget:** Used to select a specific widget to be opened when specific section is clicked.
       4. **Execute Action**: Used to run a specific Lucy action. You can select a model, choose an appropriate action, and provide parameters. Additionally, configure the post-action behavior.
       5. **Open Add-on**: Used to configure a specific add-on to be opened when specific section is clicked.
       6. **Open Mobile Screen**: Used to select a predefined mobile screen to be opened when the specific section is clicked.
       7. After configuring the action, click **Done**.
    6. Add more sections.
12. Click **Save** to apply the changes in the mobile app.
13. Open the mobile app to view changes.

<figure><img src="../../.gitbook/assets/Creating Settings page_1-1.png" alt=""><figcaption><p>Designing the settings page</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Settings Page_1.png" alt="" width="353"><figcaption><p>Designed settings page</p></figcaption></figure>
