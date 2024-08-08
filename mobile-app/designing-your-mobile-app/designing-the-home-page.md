# Designing the Home Page

The mobile app's home page is fully customisable. You can configure the app bar by changing its colour, and height, and adding and configuring header icon buttons. If you prefer not to have header icon buttons and want larger icons, you can modify your homepage accordingly. Additionally, you can determine and configure the content displayed on the home page.

Let's customise the home page of your mobile app using the Lucy web app.

## Configuring the App Bar Settings

To configure the app bar settings:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app builder screen displays.
2. Under the **General** tab on the right, go to the **Home Page** tab.
3. Customise the settings as necessary.
4. Click **Save** to apply the changes in the mobile app.
5. Open the mobile app to view changes.

These are the settings related to the app bar of your mobile app.

<figure><img src="../../.gitbook/assets/App Home page settings_1_3.png" alt="" width="563"><figcaption><p>Customise the settings of app home page</p></figcaption></figure>

### Adding and Configuring Header Icon Buttons

In your mobile app, you can add header icon buttons in the app bar via the lucy web app. These buttons will be added under the app bar title.

To add a header icon button:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app builder screen displays.
2. Under the **General** tab on the right, go to the **Home Page** tab.
3. Go to the Header Icon Buttons section and click **Add Button.**
4. In the **Name** box, provide a suitable name for the button.
5. Click the **Icon** field to pick a icon from the gallery.
6. [**Edit Action:** ](handling-button-click-events.md)Click this button to open the [**Action Editor** window.](handling-button-click-events.md#action-editor-window) This window has five tabs: Open URL, Open Widget, Execute Action, Open Add-on, and Open Mobile Screen. Use these tabs to set what happens when a specific header icon is clicked.
   1. **Open URL:** You can configure a URL to be opened when the header icon is clicked.
   2. **Open Widget:** Used to select a specific widget to be opened when the header icon is clicked.
   3. **Execute Action**: Used to run a specific Lucy action when the header icon is clicked. You can select a model, choose an appropriate action, and provide parameters. Additionally, configure the post-action behavior.
   4. **Open Add-on**: Used to configure a specific add-on to be opened when the header icon is clicked.
   5. **Open Mobile Screen**: Used to select a predefined mobile screen to be opened when the the header icon is clicked.
7. After configuring the action, Click **Done**.
8. Click **Save** to apply the changes in the mobile app.
9. Open the mobile app to view changes.

<figure><img src="../../.gitbook/assets/Header Icon Buttons_0.png" alt=""><figcaption><p>Adding a header icon button screen 1</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Header Icon Buttons_1-1.png" alt=""><figcaption><p>Adding a header icon button screen 2</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/App Bar elements_3.png" alt=""><figcaption><p>Designed app bar</p></figcaption></figure>

### **Displaying Larger Icons**

When designing your mobile app homepage, you can add icons to the home page content without placing them in the App bar.

To add and display larger icons:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the Bottom Tab Bar Navigation.
3. In the bottom tab bar navigation, click the required tab to access your home page.
4. Under **Configure Tabs** section, pick the **Type** as 'Section'.
5. Go to the **Sections** tab on the left. Pick the **Icon Section Widget.**
6. Drag and drop it onto the mobile screen.
7. An icon section widget will be added and displayed on the mobile screen.
8. Add a new icon
   1. Click the Add icon![](<../../.gitbook/assets/Add icon (1).png>).
   2. An icon will be added and displayed on the mobile screen.
   3. Click the newly added icon to launch its properties panel.
   4. Click the **Icon** field to pick a suitable icon from the Search Icons window.
   5. Select a **Background Colour.**
   6. Choose an **Icon Colour.**
   7. In the **Label** box, type a unique name for the icon.
   8. [**Edit Action:** ](handling-button-click-events.md)Click this button to open the [**Action Editor** window.](handling-button-click-events.md#action-editor-window) This window has five tabs: Open URL, Open Widget, Execute Action, Open Add-on, and Open Mobile Screen. Use these tabs to set what happens when the icon is clicked.
   9. Once the action is configured, click **Done.**
9. Click **Save** to apply the changes. Open the home page in the mobile app to view your updates.

<figure><img src="../../.gitbook/assets/Icon Section Widget.png" alt=""><figcaption><p>Set of Icons configured</p></figcaption></figure>

## Configuring the Home Tab

When configuring the Home tab of your mobile app in Lucy web app, you can add a unique name, select an icon and pick a screen type for your Mobile app home page. There are available screen types.

| Type               | Description                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Section            | <p>This type of screen lets you add horizontal sections to your mobile screen. You can drag and drop the required section to the mobile screen. Each section serves a unique purpose and enhances the user experience.</p><p></p><p>These are the available sections: Custom UI Section, Icon Section Widget, Image Card List, Horizontal List of Cards, Currency Converter Widget, and Configurable Search Widget.</p> |
| Widget             | You can link a preconfigured widget to a specific tab to display it when clicked.                                                                                                                                                                                                                                                                                                                                       |
| Custom Mobile Page | Custom Mobile Pages are unique to the mobile app and not available in the Lucy web app. Although the mobile app is set up through the Lucy web platform, these pages are specifically designed for mobile, e.g., Settings page.                                                                                                                                                                                         |

To configure the home tab:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the Bottom Tab Bar Navigation.
3. In the bottom tab bar navigation, click the required tab to access your home page.
4. Under **Configure Tabs** section configure the following,&#x20;
   1. **Name**: Enter a unique name for the home tab.
   2. **Icon**: Click the **Icon** field and pick an icon from the Search Icons window.
   3. **Type**: Pick the required screen type.
5. Click **Save.**

For detailed instructions on configuring the screen type, read this article.

[Configuring the Screen Type](adding-and-configuring-tabs-in-the-bottom-tab-bar-navigation/#screen-types)

