# Designing a User Interface from a Database

This article shows how to design a form from a [database](../../databases/) to capture data.

The purpose of these forms is to facilitate data collection, streamline processes, and enhance communication between users and organizations. By capturing and storing data in a database, businesses and organizations can better manage and utilize the information for various purposes, such as providing services, making informed decisions, and improving user experiences.

_e.g., feedback forms_

{% hint style="success" %}
**Tip**: When designing a user interface to capture information using a Form, you can always start from scratch, yet it is generally advisable to start creating a form from a database.
{% endhint %}

## <mark style="color:blue;">Designing a User Interface from a Database</mark>

The process of designing a user interface from a database involves four main steps.

### <mark style="color:blue;">1. Creating a Database</mark>

As the first step, you need to have a database to create a form. Refer to the article below on how to create a new database to gain further insights.

{% content-ref url="../../databases/creating-and-editing-databases/" %}
[creating-and-editing-databases](../../databases/creating-and-editing-databases/)
{% endcontent-ref %}

### <mark style="color:blue;">2. Designing a Form from the Database</mark>

Follow the below steps to design a form from a database.

1. On the Lucy app **homepage**, go to the **My Work** tab on the left sidebar.
2. Search and click on the **folder** you want to open.
3. Go to **Databases** tab.
4. Search and select the desired **database**.
5. Hover over the database click **Edit** icon that displays.
6. Click **Create a form** to open the [widget designer](../working-with-the-widget-designer.md).
7. By default, the widget designer will be opened in its **Design** mode.
8. You can do required customization to the form in the **Design** mode.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s1.png" alt=""><figcaption><p>Widget designer</p></figcaption></figure>

{% hint style="success" %}
**Tip**: Once you load the widget designer, its default mode will be the **Design** Mode (design mode will be selected).

There are two modes in a widget designer page:&#x20;

1. **Design mode** - Used to design, edit and customize the widget.&#x20;
2. **Preview mode** - Used to view a live version of the widget.
{% endhint %}

### <mark style="color:blue;">3. Using Widget Designer to Customize the Form</mark>

Widget designer provides a user-friendly interface to design, edit, and customize your widgets, enabling users to customize their appearance, behavior, and content to suit their specific needs or preferences.

You can click on any section (**header, body, item/field** on the body) on the form and open **Properties** panel to customize the appearance of the form _e.g., change header background, font size._

<figure><img src="../../.gitbook/assets/_Working with Widget Designer_s3.png" alt="" width="375"><figcaption><p>Sections in a Form</p></figcaption></figure>

The following are some basic modifications you can do to the form in the widget designer's **Design** mode:

* [Setting a Background Color/Image](designing-a-user-interface-from-a-database.md#setting-a-background-color-image)
* [Setting a Background Image Size](designing-a-user-interface-from-a-database.md#setting-a-background-image-size)
* [Setting the Alignment of the Background Image](designing-a-user-interface-from-a-database.md#setting-the-alignment-of-the-background-image)
* [Adding a Header Title](designing-a-user-interface-from-a-database.md#adding-a-header-title)
* [Setting the Properties of the Item(s)/Field(s) on the Body Section](designing-a-user-interface-from-a-database.md#setting-the-properties-of-the-item-s-field-s-on-the-body-section)
* [Adding Fields to the Form](designing-a-user-interface-from-a-database.md#adding-fields-to-the-form)
* [Adding a Background Image to the Entire Page](designing-a-user-interface-from-a-database.md#adding-a-background-image-to-the-entire-page)

#### <mark style="color:blue;">Setting a Background Color/Image</mark>

&#x20;To add a background color to form header/body:

1. On the **Design** mode of the widget designer, click on the _e.g., Header_ section.
2. Properties panel will be opened.
3. Under the **Container** section, pick a **background color**. The background color will be applied to the respective section of the form.
4. Alternatively, you can pick a background image.
5. To add a background image:
   * Click the **Search** button related to background image field.
   * It will prompt a image gallery to select a background image or to upload your own image.
   * To select an image from the gallery, pick a background image from the gallery.
   * To upload your own image, click **Upload your image** button in the image gallery.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s3.png" alt=""><figcaption><p>Adding a Background Color/Background Image</p></figcaption></figure>

#### <mark style="color:blue;">Setting a Background Image Size</mark>

After selecting a background image, you can select appropriate background image size for the header/body sections of the form.

The following are the background image sizes you can configure for the header/body sections of the form:

* **Original Size -** Default size of the background image will be applied to the selected header/ body
* **Fill Area** - Background image will fill the entire area of the header/body
* **Fit into Area** - Entire image will be visible within the header/body without any part being cropped

To select a background image size:

1. Click on the form's e.g., header section. Its **Properties** panel will be opened.
2. Under the Container section, pick a suitable **Background Size** _e.g., Fill Area._ The background size will be applied to the respective section of the form.

#### <mark style="color:blue;">Setting the Alignment of the Background Image</mark>

Selecting the alignment of the background image of the form header/body section denotes adjusting the way the background image of the form header/body is placed.

To select the background image alignment:

1. Click on the form's e.g., header section. Its **Properties** panel will be opened.
2. On the Properties panel, go to **Container** section.
3. In the **Background Position True** field, you'll find a diagram displaying various background image positions represented by circles. Choose an appropriate **circle** that corresponds to where you'd like to position the background image within the widget's header/body section.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s4.png" alt=""><figcaption><p>Background Position/Alignment</p></figcaption></figure>

#### <mark style="color:blue;">Adding a Header Title</mark>

To add header title and set title properties:

1. Click on the form's **header** section. Its **Properties** panel will be opened.
2. On the Properties panel, go to **Title** section.
3. Add the header title and customize header title properties to suit your specific preferences.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s5.png" alt=""><figcaption><p>Adding Header Title and setting its Properties</p></figcaption></figure>

#### <mark style="color:blue;">Setting the Properties of the Item(s)/Field(s) on the Body Section</mark>

Users can customize field(s) or item(s) on the body section of the form as follows:

1. Click on the required **field** or **item** on the body section. Its **Properties** panel will be opened.
2. Set required properties of the item accordingly.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s6.png" alt=""><figcaption><p>Setting Item Properties</p></figcaption></figure>

To change the position of a field:

1. Click on the required **field/item** on the body section. Its **Properties** panel will be opened.
2. On the body section, click on the **field** you wish to change the position.
3. Drag the field up or down to the location where you'd like the field to be within the form's body section.

{% hint style="info" %}
**Note**: The position of a field can be changed only within the Body section of the form; in other words, you cannot drag and place it on the Header section.
{% endhint %}

#### <mark style="color:blue;">Adding Fields to the Form</mark>

Besides the fields available on the form, users have the flexibility to incorporate additional fields as needed.

To add fields to the form:

1. On the widget designer, go the the **Fields** panel on the left.
2. On the Fields panel, the fields that capture data of different input types will be listed, such as Drop-down list, checkbox, number input etc.&#x20;
3. Select the required field _e.g., Dropdown list_ and drag and drop it onto the body section of the form.
4. Give a **Name** for the newly added field _e.g., Location._
5. Click **Done**_._

Further, you can customize the properties of each field according to your preference.



**Setting properties of a Drop-down List**

Users can customize a drop-down list by adding multiple different options to it. You have the choice to add options manually or import options from an external source.

To manually add options to a drop-down list on the form, follow these steps:

1. Click on the **drop-down**.
2. On the **Properties** panel, go to **Options** section.
3. Click **Add New Option** button. A text box will appear, allowing you to enter the name of the new option.
4. Type in the desired option name.
5. Repeat steps 3-4 to add more options to the drop-down.

#### Setting Internal Values for Options in a Drop-down List

Besides the default label (a name given to identify a option in the list) of a option which is visible to users, you can configure a internal value which is not visible to users for each option in the list. Alternatively, you can set the same label as the internal values.

To set internal values for options:

1. After adding your options, deselect **Use label as Value** option (By default, this option will be selected).
2. This will enable a text box for each option to enter the **internal value** which is not visible to users.
3. Enter the **internal value** for each option.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s7.png" alt=""><figcaption><p>Setting Options and Internal Values</p></figcaption></figure>

#### Delete a Field from the Form

To remove a field from the form:

1\.     On the widget designer, click on the desired **field** to delete.

2\.     Click **Delete** icon. The field will be removed from the form.

#### Adding a Background Image to the Entire Page

To add a background to the entire page:

1. On the widget designer, go to **General** tab on the right.
2. Go to **Share** section and click **Search** icon of the **Page Background Image** field.
3. Select a background image from the gallery or upload a image of your own for the entire page.
4. Go to **Preview** mode to preview the background image.

### <mark style="color:blue;">4. Using Widget Designer to Customize the Thank you Screen</mark>

Using the widget designer, you have the capability to customize the appearance of the thank you screen of a form, enabling them to see their personalized thank you screen upon submitting the form.

1. On the widget designer page (Design mode), click the **Form** toggle button on the bottom bar.
2. The view will be changed to **Thank you** screen.&#x20;

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s9.png" alt=""><figcaption><p>Thank you Screen</p></figcaption></figure>

#### <mark style="color:blue;">Setting the Properties of the Thank you Screen's Header Section</mark>

1. Click on the **header** section of the Thank You screen. Its **Properties** panel will be displayed on the right.
2. Do required changes to the header section from the Properties panel.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s10.png" alt=""><figcaption><p>Setting the Properties of the Thank you Screen's Header</p></figcaption></figure>

#### <mark style="color:blue;">Setting the Properties of the Thank you Screen's Body Section</mark>

1. Click on the **body** section of the Thank You screen. Its **Properties** panel will be displayed on the right.
2. Do required changes to the body section from the Properties panel.

<figure><img src="../../.gitbook/assets/LC_Design a user interface from a database_s11.png" alt=""><figcaption><p>Setting the Properties of the Thank you Screen's Body Section</p></figcaption></figure>

### <mark style="color:blue;">5. Previewing the Form</mark>

Preview mode can be used to view a live preview of the appearance and the behavior of the form.&#x20;

1. On the widget designer page, click **Preview** button to change the mode to **Preview**.
2. The widget will be loaded in the preview mode.

### <mark style="color:blue;">6. Saving the Form</mark>

After you have done required customizations, you can save the form for future reference.

1. On the widget designer page, click **Save Widget.**
2. Enter a **Name** for the widget (adding a name is mandatory).
   * Go to **General** tab and enter the name.
3. Click **Save Widget**.

### <mark style="color:blue;">7. Sharing the Form with Others</mark>

After designing the form, you can share it with others. To learn more about this, refer to the article linked below.

{% content-ref url="../sharing-a-user-interface.md" %}
[sharing-a-user-interface.md](../sharing-a-user-interface.md)
{% endcontent-ref %}

