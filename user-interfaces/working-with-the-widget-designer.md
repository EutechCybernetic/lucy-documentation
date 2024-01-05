# Working with the Widget Designer

The Widget Designer provides a user-friendly interface for designing, editing, and customizing your widgets. This enable users to customize the appearance, behavior, and content of a widget to suit their preferences. Customization denotes adjusting colors, title, font sizes, data sources and more. .

Widgets are versatile components for displaying information on a dashboard, such as calendar events, weather updates, etc.

{% hint style="info" %}
**Note**: It is recommended to know the basics of creating projects/folders, [databases](../databases/creating-and-editing-databases/) and [user interfaces ](designing-a-user-interface/)before going through this article.
{% endhint %}

This article shows the basic functionalities of a widget designer.

## <mark style="color:blue;">Loading Widget Designer</mark>&#x20;

A widget designer can be opened and accessed in different scenarios.

### <mark style="color:blue;">1. When Designing a User Interface</mark>

A widget designer serves the purpose of designing and constructing a user interface, and there are multiple approaches to achieve this. Accessing the widget designer can be done through various methods when you intend to design and build a user interface.

#### <mark style="color:blue;">Ways to Design and Build a User Interface</mark>

{% content-ref url="designing-a-user-interface/designing-a-user-interface-to-visualize-information.md" %}
[designing-a-user-interface-to-visualize-information.md](designing-a-user-interface/designing-a-user-interface-to-visualize-information.md)
{% endcontent-ref %}

{% content-ref url="designing-a-user-interface/designing-a-user-interface-to-capture-information.md" %}
[designing-a-user-interface-to-capture-information.md](designing-a-user-interface/designing-a-user-interface-to-capture-information.md)
{% endcontent-ref %}

{% content-ref url="designing-a-user-interface/designing-a-user-interface-from-scratch.md" %}
[designing-a-user-interface-from-scratch.md](designing-a-user-interface/designing-a-user-interface-from-scratch.md)
{% endcontent-ref %}

{% content-ref url="designing-a-user-interface/designing-a-user-interface-from-a-database.md" %}
[designing-a-user-interface-from-a-database.md](designing-a-user-interface/designing-a-user-interface-from-a-database.md)
{% endcontent-ref %}

### <mark style="color:blue;">2. If You have Existing User Interfaces</mark>

If you have existing user interfaces inside your project, you can easily jump into the widget designer page.

1. On the app homepage, go to the **My Work** tab on the left sidebar.
2. Search and click on the **folder** you want to open.
3. Go to the **User Interfaces** tab.
4. Pick the user interface under User Interfaces tab.&#x20;
5. If there is a list of user interfaces, you can search for the required User Interface by typing its name under Search User Interfaces.
6. Hover over the desired user interface and click the **Edit** icon that appears.
7. The respective user interface will be opened on its widget designer page.



{% hint style="info" %}
Note: If no user interface is created under the **User Interfaces** tab, you will not see any user interface.
{% endhint %}

### <mark style="color:blue;">3. Loading from Databases Tab</mark>

Users can create Forms from a database to capture information. The respective form can be opened on a widget designer to create, edit and do further modifications.

1. On the app homepage, go to the **My Work** tab on the left.
2. Search and click on the **folder** you want to open.
3. Head to the **Databases** tab.
4. Pick the database you wish to open. If there is a list of databases, you can search for the required database by typing its name under Search Databases.
5. Hover over the required database and click **Edit** icon that appears.
6. Click **Create Form.**
7. The respective form will be opened on its widget designer page.

{% hint style="info" %}
Note: If no database is created under the **Databases** tab, you will not see any database.
{% endhint %}

## <mark style="color:blue;">Basic Features of a Widget Designer</mark>

Once you load a widget designer, its default mode will be the **Design** Mode.

There are two modes in a widget designer page:&#x20;

1. **Design mode** - Used to design, edit and customize the widget.&#x20;
2. **Preview mode** - Used to view a live version of the widget.

### <mark style="color:blue;">Features in the Widget Designer's Design Mode</mark>

The below screen displays the basic features of a widget designer in its Design Mode.

For the purpose of demonstrating the widget designer, we'll use a form widget as our example.



<figure><img src="../.gitbook/assets/LC_Working with Widget Designer_s1.png" alt=""><figcaption><p>Widget Designer's Design Mode</p></figcaption></figure>

<table><thead><tr><th width="40" data-type="number"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>1</td><td>Used to switch between <strong>Design</strong> mode and <strong>Preview</strong> Mode. </td><td></td></tr><tr><td>2</td><td>Opens a window to share the widget with others and perform other functionalities <em>e.g., Add widget to a canvas.</em></td><td></td></tr><tr><td>3</td><td>Used to save changes done to the widget.</td><td></td></tr><tr><td>4</td><td><p>Used to configure general settings related to the widget. </p><p><em>e.g., change the background of the entire page, add a name for the widget.</em></p></td><td></td></tr><tr><td>5</td><td>Displays the respective widget (<em>e.g., form)</em> on the widget designer page.</td><td></td></tr><tr><td>6</td><td>Displays some additional settings that is enabled in the Design mode.</td><td></td></tr><tr><td>7</td><td>Used to select appropriate fields and add it to the widget. Once a field is added to the widget, users can configure its properties.</td><td></td></tr><tr><td>8</td><td>Used to direct back to <strong>User Interfaces</strong> tab.</td><td></td></tr></tbody></table>

#### Additional Operations in a Widget Designer's Design mode



<figure><img src="../.gitbook/assets/LC_Working with Widget Designer_s2.png" alt=""><figcaption><p>Additional Operations in a widget designer's Design mode</p></figcaption></figure>

<table><thead><tr><th width="40"></th><th></th></tr></thead><tbody><tr><td>1</td><td><p>By default, the <strong>padlock</strong> icon is locked to restrict moving the widget around the widget designer page. Click the padlock icon to unlock it and to move the widget around the page.</p><p>Further, users can unlock the padlock to resize the interface.</p><p><em>Note: Forms do not support resizing feature. However, it is available for the other widgets.</em></p></td></tr><tr><td>2</td><td>Used to switch between the Form screen and the Thank You screen of the form. When the widget designer is loaded, the form interface will be displayed by default. Users can do required customizations to each screen by switching between the two screens.</td></tr><tr><td>3</td><td>Used to restore any actions that were previously undone using an undo. </td></tr><tr><td>4</td><td>Used to reverse the change previously done (undo the change). </td></tr><tr><td>5</td><td>Used to Zoom in the widget to appear it larger.</td></tr><tr><td>6</td><td> Used to Zoom out the widget to appear it smaller.</td></tr></tbody></table>

#### Form Widget

A form has three sections: a header, body, and Item/Field. Users can modify each section individually from the Properties tab.



<figure><img src="../.gitbook/assets/_Working with Widget Designer_s3.png" alt="" width="375"><figcaption><p>Sections in a form</p></figcaption></figure>

#### Configuring Properties of the Widget's Header Section

Users can customize the appearance of the widget’s header section on the widget designer page. _e.g., Add a title for the header section._&#x20;

Find out more on configuring header properties in [this ](designing-a-user-interface/designing-a-user-interface-from-a-database.md)article.

#### Configuring Properties of the Widget's Body Section

Users can customize the properties of widget’s body section and the properties of each individual field/item on the widget’s body section using the widget designer.

Find out more on configuring widget’s body section properties in [this ](designing-a-user-interface/designing-a-user-interface-from-a-database.md)article.

### Widget Designer's Preview Mode

The **Preview** mode is used to preview a live session of the widget.&#x20;

To access widget designer's Preview mode:

1. On the widget designer page, click **Preview** mode.
2. A live version of the respective widget will be opened in the preview mode.

<figure><img src="../.gitbook/assets/_Working with Widget Designer_s4.png" alt=""><figcaption><p>Widget Designer's Preview Mode</p></figcaption></figure>

## <mark style="color:blue;">Binding a Data source to a Widget from Widget Designer Page</mark>&#x20;

Some widgets require linking a data source to them. The purpose of this binding is to establish a connection between the data source (which contains the underlying data) and the widget that is responsible for displaying data.

This connection ensures that changes in the data source are automatically reflected in the widget, and vice versa, facilitating real-time synchronization between the data and the user interface.

For instance, a widget can be created to display specific information. To make this widget display the information, it's necessary to establish a connection by binding a data source to it.

Find more details on binding a data source to a widget from here:

{% content-ref url="designing-a-user-interface/designing-a-user-interface-to-visualize-information.md" %}
[designing-a-user-interface-to-visualize-information.md](designing-a-user-interface/designing-a-user-interface-to-visualize-information.md)
{% endcontent-ref %}
