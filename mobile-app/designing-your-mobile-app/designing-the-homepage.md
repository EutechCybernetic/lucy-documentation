# Designing the Homepage

The mobile app's homepage is fully customisable. You can configure the app bar by changing its colour, and height, and adding and configuring header icon buttons. If you prefer not to have header icon buttons and want larger icons, you can modify your homepage accordingly. Additionally, you can determine and configure the content displayed on the homepage.



{% hint style="info" %}
Your mobile app comes with a default homepage and a settings page that you can customise to suit your preferences.
{% endhint %}

## Configuring the Home Tab

The default home tab in the mobile app can be customised by changing its icon, name, and type.

To configure the home tab

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays. displays.
2. Click the bottom navigation bar to open its properties panel.
3. Go to the **Home** tab properties section.
4. Edit the **Name and Icon.**
5. [**Type**](designing-the-homepage.md#selecting-a-page-type)**:** Choose the required page type to open when the respective tab is clicked, _e.g., Section._
6. Click **Save**.

{% hint style="info" %}
By default, the Home tab type is set to 'Sections'. You can change the type as necessary.
{% endhint %}

### **Selecting a Page Type**

In your mobile app, tabs are the icons located at the bottom of the page that allow you to quickly switch between different pages.

A page type determines the content displayed when a tab is clicked.

Available Page Types

* Sections
* Widget
* Custom Mobile Page

Simply put, a tab can be configured to display a list of sections, a widget or a custom mobile page built using Flutter based on the selected type.

For detailed instructions on configuring the page type, read this article.

{% content-ref url="choosing-a-page-type.md" %}
[choosing-a-page-type.md](choosing-a-page-type.md)
{% endcontent-ref %}

## Configuring the App Bar Settings

Personalise your app bar's appearance by choosing a different color or uploading a background image, adding a company logo, including a title etc.&#x20;

To configure the app bar settings:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. Under the **General** tab on the right, go to the **Home Page** tab.
3. Customise the settings as necessary.
4. Click **Save** to apply the changes in the mobile app.
5. Open the mobile app to view changes.

These are the settings related to the app bar of your mobile app.

<figure><img src="../../.gitbook/assets/Configuring the App Bar Settings_s2.png" alt="" width="563"><figcaption><p>Configuring the App Bar Settings</p></figcaption></figure>



## Adding and Configuring Header Icon Buttons

In your mobile app homepage, you can add header icon buttons to appear under app bar title. Header Icon Buttons are located at the top of a mobile app's homepage, within the app's header.&#x20;

To add a header icon button:

1. On the Lucy web app home page, go to the **Mobile App** tab. Mobile app designer page displays.
2. Under the **General** tab on the right, go to the **Home Page** tab.
3. Go to the Header Icon Buttons section and click **Add Button.**
4. In the **Name** box, provide a suitable name for the button.
5. Click the **Icon** field to pick a icon from the gallery.
6. Configure the button to open the required page when clicked. For example, set it to open a pre-built widget.
   1. Click the **Edit Action** button to open the [**Action Editor** window.](handling-button-click-events.md#action-editor-window) This window has five tabs: Open URL, Open Widget, Execute Action, Open Add-on, and Open Mobile Screen. Use these tabs to set what happens when a specific button is clicked.
      1. **Open URL:** You can configure a URL to be opened when the button is clicked.
      2. **Open Widget:** Used to select a specific widget to be opened when the button is clicked.
      3. **Execute Action**: Used to run a specific Lucy action when the button is clicked. You can select a model, choose an appropriate action, and provide parameters. Additionally, configure the post-action behavior.
      4. **Open Add-on**: Used to configure a specific add-on to be opened when the button is clicked.
      5. **Open Mobile Screen**: Used to select a predefined mobile screen to be opened when the the button is clicked.
7. After the configuration, Click **Done**.
8. Click **Save** to apply the changes in the mobile app.
9. Open the mobile app to view changes.

<figure><img src="../../.gitbook/assets/Header Icon Buttons_0.png" alt=""><figcaption><p>Adding a header icon button screen 1</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Header Icon Buttons_1-1.png" alt=""><figcaption><p>Adding a header icon button screen 2</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/App Bar elements_3.png" alt=""><figcaption><p>Designed app bar</p></figcaption></figure>

### **Adding Icons to the Content Section of the Homepage**

When designing your mobile app homepage, you have the flexibility to add icons directly to the content section of the page without placing them in the app bar. This will allow you to create a visually appealing and interactive homepage with icons that link to specific content or features.

#### Icon Section Widget

Use an Icon Section Widget to add a collection of icons to your page. Customise each icon's background color, icon color, name, and the page that opens when clicked.

{% hint style="info" %}
When setting up the homepage tab, make sure to select the Type as '**Section**'. This allows you to add an Icon section widget to the required page.
{% endhint %}

To add an Icon Section Widget to a page:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. Click the bottom navigation bar.
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
9. Click **Save**. Open the home page in the mobile app to view your updates.

<figure><img src="../../.gitbook/assets/Icon Section Widget.png" alt=""><figcaption><p>Set of Icons configured</p></figcaption></figure>

## Customising the Navigation Bar

Customise the bottom navigation bar of your mobile app by selecting a background colour, button colour and active button colours to match your design preferences.

Steps to Customise the Navigation Bar

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. Under the **General** tab on the right, click the **Home Page** tab.
3. Select a Navigation Bar Background Colour, Navigation Bar Button Colour, and Navigation Bar Active Button Colour as necessary.
4. Click **Save.** Open your mobile app to view the updates.



