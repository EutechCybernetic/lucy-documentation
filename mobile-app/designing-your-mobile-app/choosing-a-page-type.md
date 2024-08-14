# Choosing a Page Type

## Page Types

A page type determines the content displayed when a tab is clicked in your mobile app's bottom navigation bar. These are the available page types.

<table><thead><tr><th width="306">Type</th><th>Description</th></tr></thead><tbody><tr><td><a href="choosing-a-page-type.md#id-1-section">Section</a></td><td><p>This type of page displays horizontal sections, each serving a unique purpose and enhancing the user experience.</p><p>These are the available sections: Custom UI Section, Icon Section Widget, Image Card List, Horizontal List of Cards, Currency Converter Widget, and Configurable Search Widget.</p></td></tr><tr><td><a href="choosing-a-page-type.md#id-2-widget">Widget</a></td><td>You can link a preconfigured widget to a specific tab to display it when clicked.</td></tr><tr><td><a href="choosing-a-page-type.md#id-3-custom-mobile-page">Custom Mobile Page</a></td><td>Custom Mobile Pages are unique to the mobile app and not available in the Lucy web app. Although the mobile app is set up through the Lucy web platform, these pages are specifically designed for mobile, e.g., Settings page.</td></tr></tbody></table>

## Choosing a Page Type

Select a page type when adding a new tab to your mobile app's bottom navigation bar.

{% content-ref url="adding-a-new-tab-to-the-bottom-navigation-bar.md" %}
[adding-a-new-tab-to-the-bottom-navigation-bar.md](adding-a-new-tab-to-the-bottom-navigation-bar.md)
{% endcontent-ref %}

<figure><img src="../../.gitbook/assets/Adding a new tab_2.png" alt=""><figcaption><p>Choosing a Type</p></figcaption></figure>

### 1) Section

The 'Section**'** page type lets you effortlessly add and configure horizontal sections on a mobile page using the Lucy web app. Just drag and drop them into place. Each section has a unique function to enhance the user experience.

You can add the same section multiple times if necessary.

There are multiple types of horizontal sections that you can add.

[a) Custom UI Section](choosing-a-page-type.md#a-custom-ui-section)

[b) Icon Section Widget](choosing-a-page-type.md#b-icon-section-widget)

[c) Image Card List](choosing-a-page-type.md#c-image-card-list)

[d) Horizontal List of Cards](choosing-a-page-type.md#d-horizontal-list-of-cards)

[e) Currency Converter Widget](choosing-a-page-type.md#e-currency-converter-widget)

{% hint style="info" %}
To add horizontal sections, set the **Type** to 'Section' when adding a tab. Other types do not support horizontal sections.
{% endhint %}

#### a) Custom UI Section

Use the Custom UI Section to create a personalised user interface with JSON code.

To add and configure a Custom UI Section:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the bottom navigation bar.
3. In the bottom navigation bar, click the required tab.
4. <mark style="color:blue;">Note: Under</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure Tabs**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section, select the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Type**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">as 'Section'</mark><mark style="color:blue;">**.**</mark>
5. Go to the **Sections** tab on the left.
6. Drag and drop the '**Describe a custom interface with a special interface language'** section on to the desired area on the mobile screen.
7. A horizontal section named Custom UI will appear on the mobile screen.
8. Click the **Custom UI** section to open its properties panel.
9. In the **Custom UI (Mobile**) field, enter the JSON code of the UI you want to build.
10. Configure the **Data source.**
    1. Click the **Bind a Source** button.
    2. You can select an existing Lucy action or a database as the data source.
11. Click **Save** to apply the changes in the mobile app.



<figure><img src="../../.gitbook/assets/Adding a Custom UI section_2.png" alt="" width="430"><figcaption><p>Adding a Custom UI section</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Custom UI created_3.png" alt="" width="353"><figcaption><p>Custom UI created</p></figcaption></figure>

#### b) Icon Section Widget

You can include a set of icons using an Icon Section Widget. Configure each icon by setting its background colour, icon colour, name, and the action to be executed when clicked.

You can customise the widget by adding a title, changing colours, and adjusting size. Additionally, you can modify the icon shape (e.g., square, circle), background colour, text colour, etc.

{% hint style="info" %}
To customise the title section of the icon section widget, click the title section to launch its properties panel.

To customise the body section of the icon section widget, click the body section to launch its properties panel.
{% endhint %}

To add a Icon Section Widget:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the bottom navigation bar.
3. In the bottom navigation bar, click the required tab.
4. <mark style="color:blue;">Note: Under</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure Tabs**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section, select the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Type**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">as 'Section'</mark><mark style="color:blue;">**.**</mark>
5. Go to the **Sections** tab on the left.
6. Pick the **Icon Section Widget.** Drag and drop it onto the mobile screen.
7. An icon section widget will be added and displayed on the mobile screen.
8. Add a new icon
   1. Click the **Add** icon.
   2. An icon will be added and displayed on the mobile screen.
   3. Click the newly added icon to launch its properties panel.
   4. Click the **Icon** field to pick a suitable icon from the Search Icons window.
   5. Select a **Background Colour.**
   6. Choose an **Icon Colour.**
   7. In the **Label** box, type a unique name for the icon.
   8. [**Edit Action:** ](https://help.iviva.com/lucy/mobile-app/designing-your-mobile-app/handling-button-click-events)Click this button to open the [**Action Editor** window.](https://help.iviva.com/lucy/mobile-app/designing-your-mobile-app/handling-button-click-events#action-editor-window) This window has five tabs: Open URL, Open Widget, Execute Action, Open Add-on, and Open Mobile Screen. Use these tabs to set what happens when a specific icon is clicked.
      1. **Open URL:** You can configure a URL to be opened when the icon is clicked.
      2. **Open Widget:** Used to select a specific widget to be opened when the icon is clicked.
      3. **Execute Action**: Used to run a specific Lucy action when the icon is clicked. You can select a model, choose an appropriate action, and provide parameters. Additionally, configure the post-action behavior.
      4. **Open Add-on**: Used to configure a specific add-on to be opened when the icon is clicked.
      5. **Open Mobile Screen**: Used to select a predefined mobile screen to be opened when the the icon is clicked.
      6. After configuring the action, Click **Done**.
9. Click **Save** to apply the changes in the mobile app.

<figure><img src="../../.gitbook/assets/Icon Section Widget_1 (1).png" alt=""><figcaption><p>Icon Section Widget</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Icon Section Widget customised_1.png" alt=""><figcaption><p>Configured Icon Section Widget</p></figcaption></figure>



#### c) Image Card List

You can add and customise an image card list for specific mobile screens, offering various options for personalisation.

For example, you can customise the number of cards per row to be displayed. If a specific card reaches the end of a container, you can move the remaining cards to the next line.

In addition, you can customise the title and the body section properties in the Image Card List. To customise the title section, click the title section to launch properties panel. To customise the body section, click the body section to launch properties panel.

{% hint style="info" %}
To customise the title section of the image card list, click the title section to launch its properties panel.
{% endhint %}

To add a Image Card List:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the bottom navigation bar.
3. In the bottom navigation bar, click the required tab.
4. <mark style="color:blue;">Note: Under</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure Tabs**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section, select the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Type**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">as 'Section'</mark><mark style="color:blue;">**.**</mark>
5. Go to the **Sections** tab on the left.
6. Pick the **Image Card List.** Drag and drop it onto the mobile screen.
7. An image card list will be added and displayed on the mobile screen.
8. Click on the image card to launch its properties panel.
9. Do required customisations.
10. Add a new card to the Image Card List.
    1. In the image card list, click the add icon.
    2. A new card will be added to the image card list.
    3. Customise the new card as needed.
11. Click **Save** to apply changes in the mobile app.

<figure><img src="../../.gitbook/assets/Configuring Image Card properties_1.png" alt=""><figcaption><p>Configuring Image Card properties screen 1</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Configuring Image Card properties_2.png" alt=""><figcaption><p>Configuring Image Card properties screen 2</p></figcaption></figure>



<figure><img src="../../.gitbook/assets/Image Card List_1.jpg" alt="" width="563"><figcaption><p>An example designed using a Image Card List</p></figcaption></figure>



#### d) Horizontal List of Cards

A Horizontal List of Cards section is similar to an Image Card List, with the added functionality of swiping the cards to the left or right. You can also display buttons or text labels at the top or bottom.

It allows to bind a data source to the card list to display required details in the cards including the images.

To add a Horizontal List of Cards:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the bottom navigation bar.
3. In the bottom navigation bar, click the required tab.
4. <mark style="color:blue;">Note: Under</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure Tabs**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section, select the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Type**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">as 'Section'</mark><mark style="color:blue;">**.**</mark>
5. Go to the **Sections** tab on the left.
6. Pick the **Horizontal List of Cards.** Drag and drop it onto the mobile screen.
7. The newly added Horizontal List of Cards section will appear on the mobile screen.
8. Do required customisations.
9. Click **Save** to apply the changes in the mobile app.

<figure><img src="../../.gitbook/assets/Horizontal List of Cards.jpg" alt="" width="563"><figcaption><p>An example designed using the Horizontal List of Cards section</p></figcaption></figure>

#### e) Currency Converter Widget

To add a Currency Converter Widget:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the bottom navigation bar.
3. In the bottom navigation bar, click the required tab.
4. <mark style="color:blue;">Note: Under</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure Tabs**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section, select the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Type**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">as 'Section'</mark><mark style="color:blue;">**.**</mark>
5. Go to the **Sections** tab on the left.
6. Pick the **Currency Converter Widget.** Drag and drop it onto the mobile screen and it will appear on the mobile screen.
7. Click **Save** to apply the changes in the mobile app.
8. Open your mobile app and go to the required tab. The Currency Converter section will be displayed.
9. In the Currency Converter section, select the original currency (_e.g., USD)_ and enter the amount you want to convert.
10. Choose the currency you want to convert the original amount into (_e.g., SGD)_. The entered amount will be automatically displayed in the selected currency.

<figure><img src="../../.gitbook/assets/Currency Converter Widget_1.png" alt=""><figcaption><p>Currency Converter Widget</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Currency Converter Widget_2.png" alt="" width="530"><figcaption><p>Currency Converter Widget section displayed in mobile app</p></figcaption></figure>

### 2) Widget

You can link a preconfigured widget to a specific tab to display it when clicked.&#x20;

To link a widget to a specific tab:

1. On the Lucy web app homepage, go to the **Mobile App** tab. Mobile screen displays.
2. Click the bottom navigation bar.
3. In the bottom navigation bar, click the required tab.
4. <mark style="color:blue;">Note: Under</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Configure Tabs**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">section, select the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Type**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">as 'Widget'</mark><mark style="color:blue;">**.**</mark>
5. Click the **Select a Widget** button.
6. Pick the required widget from the list (widget names will appear in the list).&#x20;
7. Click **Save** to apply the changes. The selected widget will now display in your app under the required tab.

{% hint style="info" %}
When adding a tab, the type should be selected as 'Widget' to link a preconfigured widget to that tab.
{% endhint %}

Learn to build and link a widget to a tab. Find the article here to gain more insights:

{% content-ref url="launching-a-widget-on-tab-click.md" %}
[launching-a-widget-on-tab-click.md](launching-a-widget-on-tab-click.md)
{% endcontent-ref %}



The screen below displays a widget created using the Search widget template, linked to the Assets tab.

<figure><img src="../../.gitbook/assets/Widget example_1.png" alt="" width="353"><figcaption><p>Widget example</p></figcaption></figure>

### 3) Custom Mobile Page

Custom Mobile Pages, such as the Settings page, are unique to the mobile app and not available in the Lucy web app.

You can organise the settings page by configuring Section Groups and configuring related Sections within each group.

{% hint style="info" %}
When adding a tab, the **Type** should be selected as 'Custom Mobile Page'.
{% endhint %}

<figure><img src="../../.gitbook/assets/Settings screen_2.png" alt="" width="353"><figcaption><p>Settings page</p></figcaption></figure>

Here is an example for designing a page using the 'Custom Mobile Page' type.

{% content-ref url="designing-the-settings-page.md" %}
[designing-the-settings-page.md](designing-the-settings-page.md)
{% endcontent-ref %}
