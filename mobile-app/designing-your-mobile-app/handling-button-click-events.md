# Handling Button Click Events

When customising your mobile app via the Lucy web app, you can control the actions triggered by button clicks. Here are the five types of actions available:

1. [Open a Web Page](handling-button-click-events.md#open-a-web-page)
2. [Open a Pre-built Widget](handling-button-click-events.md#open-a-pre-built-widget)
3. [Execute a Lucy Action](handling-button-click-events.md#execute-a-lucy-action)
4. [Open an Add-on](handling-button-click-events.md#open-an-add-on)
5. [Open a Mobile Screen](handling-button-click-events.md#open-a-mobile-screen)

{% hint style="info" %}
You will also encounter button click events when creating widgets, such as the Search widget.
{% endhint %}

### Action Editor Window

Use the Action Editor window to set actions for clickable elements like buttons and icons. It supports five types of actions: open a web page, launch a pre-built widget, execute a Lucy Action, open an add-on, and open a mobile screen.

<figure><img src="../../.gitbook/assets/Action Editor Window.png" alt="" width="563"><figcaption><p>Action Editor Window</p></figcaption></figure>



## Open a Web Page

You can configure a button to open a specific web page when clicked.

For example, when you click on the Help section in your mobile app's Settings page, it opens the Help page.&#x20;

To open a web page

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. On the mobile screen, click the Settings page icon in the bottom tab bar navigation. The Settings page will open on the mobile screen.
3. On the Settings page, click the required section (e.g., Help) to open the properties panel.
4. In the Properties panel, go to respective section and click **Edit Action**. The Action Editor window opens.
5. Navigate to the **Open URL** tab.
6. Enter the URL of the required web page.
7. Choose how you want to open the web page: New Tab or Current Tab.
8. Click **Done**.
9. Click **Save.**
10. Open the Settings page in your mobile app and click the specific section to launch the web page.

<figure><img src="../../.gitbook/assets/Launch a web page_1.png" alt=""><figcaption><p>Open a web page</p></figcaption></figure>

## Open a Pre-built Widget

For example, when you click on the Personal Details section in your mobile app's Settings page, it opens the corresponding user-created widget, a form to edit personal details.

[Click here](designing-the-settings-page.md#creating-the-widget) to learn how to create a simple widget.

To launch a pre-built widget

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. On the mobile screen, click the Settings page icon in the bottom tab bar navigation. The Settings page will open on the mobile screen.
3. On the Settings page, click the required section to open the properties panel.
4. In the Properties panel, go to respective section and click **Edit Action**. The Action Editor window opens.
5. Navigate to the **Open Widget** tab.
6. Select the required widget.
7. Enter Parameter names and values if necessary.
8. Click **Done**.
9. Click **Save.**
10. Open the Settings page in your mobile app and click the specific section to launch the respective widget.

<figure><img src="../../.gitbook/assets/Launch a Prebuilt Widget_1.png" alt=""><figcaption><p>Open a pre-built widget</p></figcaption></figure>

## Execute a Lucy Action

Set up a Lucy Action to trigger when a specific button is clicked, such as sending a notification after creating a work request.

## Open an Add-on

You can select an add-on to be opened when certain button is clicked in your mobile app.

For example, you can add an icon to your app home page to open the Weather add-on when clicked.

To open an add-on

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. Under **Sections**, drag and drop the **Icon Section Widget** to the mobile screen.
3. An icon section widget will be added and displayed on the mobile screen.
4. Click the ![](<../../.gitbook/assets/Add icon (1).png>)Add icon.
5. An icon will be added and displayed on the mobile screen. Click the newly added icon to launch its properties panel.
6. Pick an icon image, Background Colour, Icon Colour and a Label.
7. Click the **Edit Action** button to open the Action Editor window.
8. Go to Open Add-on tab.
9. Once the action is configured, click **Done.**
10. An icon will be added and displayed on the mobile screen.
11. Click the newly added icon to launch its properties panel.
12. Click the **Icon** field to pick a suitable icon from the Search Icons window.
13. Choose a **Background Colour.**
14. Choose a **Icon Colour.**
15. In the **Label** box, type a unique name for the icon.
16. Click the **Edit Action** button to launch the Action Editor window.
17. Navigate to the **Open Add-on** tab.
18. Select the required add-on, _e.g, Weather._
19. Click **Done**.
20. Click **Save** to save and apply the changes in the mobile app.
21. Open the home page in your mobile app and click the icon to launch the respective add-on.

## Open a Mobile Screen

You can set a button to open a predefined mobile screen. These screens are specific to the mobile app.

For example, choose a predefined mobile screen, like the Currency page, to display when you click on the Currency section in your mobile app's Settings page.

To open a mobile screen

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile app designer page displays.
2. On the mobile screen, click the Settings page icon in the bottom tab bar navigation. The Settings page will open on the mobile screen.
3. On the Settings page, click the required section to open the properties panel.
4. In the Properties panel, go to respective section and click **Edit Action**. The Action Editor window opens.
5. Navigate to the **Open Mobile Screen** tab.
6. Select the required mobile screen (e.g., Currency).
7. Click **Done**.
8. Click **Save** to save and apply the changes in the mobile app.
9. Open the Settings page in your mobile app and click the specific section to launch the respective mobile screen.

<figure><img src="../../.gitbook/assets/Launch a Mobile screen_1.png" alt=""><figcaption><p>Open a mobile screen</p></figcaption></figure>
