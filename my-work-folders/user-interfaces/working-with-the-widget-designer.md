# Working with the Widget Designer

The Widget Designer offers a user-friendly, no-code interface for designing and customising user interfaces.

This allows you to tailor the appearance, behavior, and content of a user interface to your specific needs. Customisation options include changing colors, titles, font sizes, connecting data sources, and more.

This article shows the basic functionalities of a widget designer.

{% hint style="info" %}
**Note**: Familiarity with [creating folders,](../) [databases](../databases/creating-and-editing-databases/), and [user interfaces ](designing-a-user-interface/)is recommended before proceeding with this article.
{% endhint %}

### Opening the Widget Designer

There are three primary ways to [create a user interface](designing-a-user-interface/):

1. [Visualise Data:](designing-a-user-interface/designing-a-user-interface-to-visualise-information.md) Design charts and graphs to display information visually.
2. [Record Data:](designing-a-user-interface/designing-a-user-interface-to-capture-user-feedback.md) Create forms to collect user input.
3. [Start from Scratch: ](designing-a-user-interface/designing-a-user-interface-from-scratch.md)Design user interfaces from the ground up.

You can use any of these methods to open the desired user interface on the Widget Designer page.

For example, let's use the Record Data option and open a form on the widget designer page.

1. On the app **homepage**, go to **My Work** module on the left.
2. Search and select the required folder. Click on the folder to open it.
3. Navigate to the **User Interfaces** tab.&#x20;
4. Click the **Plus** icon and select the **Record Data** option.
5. Choose a data source. For the data source, you can select an existing Lucy action or a database.

## <mark style="color:blue;">Basic Functionalities of Widget Designer</mark>

Whenever you open the widget designer, its default mode will be the **Design** mode.

The widget designer has two modes:&#x20;

1. **Design** - Used to design and customise certain widget.&#x20;
2. **Preview** - Allows you to see how your widget will appear to your users, providing a live version to visualise any changes you've made.&#x20;

You can switch between the two modes as needed.

### <mark style="color:blue;">Features in the Widget Designer's Design Mode</mark>

The screen below displays the basic features of a widget designer in **Design** Mode. To illustrate the widget designer's capabilities, we will use a form user interface.

<figure><img src="../../.gitbook/assets/LC_Working with Widget Designer_s1.png" alt=""><figcaption><p>Widget Designer's Design Mode</p></figcaption></figure>

<table><thead><tr><th width="40" data-type="number"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>1</td><td>Used to switch between <strong>Design</strong> mode and <strong>Preview</strong> Mode. </td><td></td></tr><tr><td>2</td><td>Opens a window to share the widget with others and perform other functionalities <em>e.g., Add widget to a canvas.</em></td><td></td></tr><tr><td>3</td><td>Used to save changes done to the widget.</td><td></td></tr><tr><td>4</td><td><p>Used to configure general settings related to the widget. </p><p><em>e.g., change the background of the entire page, add a name for the widget.</em></p></td><td></td></tr><tr><td>5</td><td>Displays the respective widget (<em>e.g., form)</em> on the widget designer page.</td><td></td></tr><tr><td>6</td><td>Displays some additional settings that is enabled in the <strong>Design</strong> mode.</td><td></td></tr><tr><td>7</td><td>Used to select appropriate fields and add it to the widget. Once a field is added to the widget, users can configure its properties.</td><td></td></tr><tr><td>8</td><td>Used to direct back to the <strong>User Interfaces</strong> tab of the selected project/folder.</td><td></td></tr></tbody></table>

#### <mark style="color:blue;">Additional Features in a Widget Designer's Design Mode</mark>

The following are some additional features available in the widget designer's design mode.

<figure><img src="../../.gitbook/assets/LC_Working with Widget Designer_s2.png" alt=""><figcaption><p>Additional Operations in a Widget Designer's Design Mode</p></figcaption></figure>

<table><thead><tr><th width="40"></th><th></th></tr></thead><tbody><tr><td>1</td><td><p>By default, the <strong>padlock</strong> icon is locked to restrict moving the widget around the widget designer page. Click the padlock icon to unlock it and move the widget around the page.</p><p>Further, users can unlock the padlock to resize the interface.</p><p><em>Note: Forms do not support resizing feature. However, it is available for the other widgets.</em></p></td></tr><tr><td>2</td><td>Used to switch between the Form screen and the Thank You screen of the form. When the widget designer is loaded, the form interface will be displayed by default. Users can do required customisations to each screen by switching between the two screens.</td></tr><tr><td>3</td><td>Used to restore any actions that were previously undone using an undo. </td></tr><tr><td>4</td><td>Used to reverse the change previously done (undo the change). </td></tr><tr><td>5</td><td>Used to Zoom in the widget.</td></tr><tr><td>6</td><td>Used to Zoom out the widget.</td></tr></tbody></table>

#### <mark style="color:blue;">Form Widget</mark>

A form consists of three sections: a header, a body, and an item/field. Users can modify each section individually through the **Properties** tab.



<figure><img src="../../.gitbook/assets/_Working with Widget Designer_s3.png" alt="" width="375"><figcaption><p>Sections in a Form</p></figcaption></figure>

#### <mark style="color:blue;">Configuring Properties of the Widget's Header Section</mark>

Users can customise the appearance of the widget’s header section on the widget designer page. _e.g., Add a title for the header section._&#x20;

Find out more on configuring header properties in [this ](designing-a-user-interface/designing-a-user-interface-to-capture-user-feedback.md)article.

#### <mark style="color:blue;">Configuring Properties of the Widget's Body Section</mark>

Users can customise the properties of widget’s body section and the properties of each individual field/item on the widget’s body section using the widget designer.

Find out more on configuring widget’s body section properties in [this ](designing-a-user-interface/designing-a-user-interface-to-capture-user-feedback.md)article.

### <mark style="color:blue;">Widget Designer's Preview Mode</mark>

The **Preview** mode is used to preview a live session of the widget.&#x20;

To access widget designer's Preview mode:

1. On the widget designer page, click **Preview** mode.
2. A live version of the respective widget will be opened in the preview mode.

<figure><img src="../../.gitbook/assets/_Working with Widget Designer_s4.png" alt=""><figcaption><p>Widget Designer's Preview Mode</p></figcaption></figure>

## <mark style="color:blue;">Binding a Data source to a Widget from Widget Designer Page</mark>&#x20;

Some widgets require linking a data source to them. The purpose of this binding is to establish a connection between the data source (which contains the underlying data) and the widget that is responsible for displaying data. This connection ensures that changes in the data source are automatically reflected in the widget, and vice versa, facilitating real-time synchronisation between the data and the user interface.

_e.g., A bar chart displaying sales figures for different products over a month._

Refer to this tutorial to learn how to bind a data source to a widget.

{% content-ref url="designing-a-user-interface/designing-a-user-interface-to-visualise-information.md" %}
[designing-a-user-interface-to-visualise-information.md](designing-a-user-interface/designing-a-user-interface-to-visualise-information.md)
{% endcontent-ref %}

Here is a short video on how you can use the widget designer to visualise information using the donut chart widget.

{% embed url="https://drive.google.com/file/d/1XAcYWbE-gx8TXYliYiWFN84-28yhWTpw/view?usp=sharing" %}
