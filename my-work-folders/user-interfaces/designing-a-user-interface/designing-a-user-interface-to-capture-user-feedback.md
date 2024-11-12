# Designing a User Interface to Capture User Feedback

This article shows how to design a form to capture user feedback using an existing database.

The purpose of these forms is to simplify data collection, streamline processes, and enhance communication between users and organizations. By capturing and storing data in a database, businesses and organizations can better manage and utilise the information for diverse purposes, including providing services, making informed decisions, and improving user experiences. For instance, consider feedback forms.

{% hint style="success" %}
**Tip**: When creating a form to capture information, you can always start from scratch, yet it is generally advisable to start creating a form from a database.
{% endhint %}

## <mark style="color:blue;">Creating a User Interface to Capture User Feedback</mark>

The process of creating a user interface to capture user feedback involves four main steps.

### <mark style="color:blue;">1. Creating a Database</mark>

As the initial step, you should have a database in place before creating a form.&#x20;

Below is an image showing a database (e.g., Complaints) created to record complaints raised by customers.

<figure><img src="../../../.gitbook/assets/image (61).png" alt=""><figcaption><p>Example of a database</p></figcaption></figure>

For detailed instructions on creating a new database, refer to the article below for further insights.

{% content-ref url="../../databases/creating-and-editing-databases/" %}
[creating-and-editing-databases](../../databases/creating-and-editing-databases/)
{% endcontent-ref %}

### <mark style="color:blue;">2. Creating a Form from the Database</mark>

Follow the below steps to design a form from a database.

1. On the Lucy app **homepage**, go to the **My Work** tab on the left sidebar.
2. Search and click on the **folder** you want to open.
3. Go to the **Databases** tab.
4. Search and select the desired **database**.
5. Hover over the database click the **Edit** icon that displays.
6. Click **Create a form** to open the form on the widget designer page.
7. By default, the widget designer will be opened in its **Design** mode.
8. You can do required customisation to the form in the **Design** mode.

<figure><img src="../../../.gitbook/assets/LC_Design a user interface from a database_s1.png" alt=""><figcaption><p>Widget Designer</p></figcaption></figure>

{% hint style="success" %}
**Tip**: Once you open the widget designer, its default mode will be the **Design** Mode (design mode will be selected).

There are two modes in a widget designer page:&#x20;

1. **Design mode** - Used to design, edit, and customise the widget
2. **Preview mode** - Used to view a live version of the widget
{% endhint %}

### <mark style="color:blue;">3. Using Widget Designer to Customise the Form</mark>

The Widget Designer offers a user-friendly interface for creating and customising your widgets. This functionality empowers users to tailor the appearance, behavior, and content of their widgets to meet specific needs.

To customise the form's appearance, including elements such as the header, body, or individual items/fields within the body, simply click on the desired section. This action opens the Properties panel, allowing you to make adjustments like changing the header background.

<figure><img src="../../../.gitbook/assets/_Working with Widget Designer_s3.png" alt="" width="375"><figcaption><p>Sections in a Form</p></figcaption></figure>

In the Widget Designer's Design mode, you can make several basic modifications to the form, such as:

* [Adding a Background Colour/Image](designing-a-user-interface-to-capture-user-feedback.md#adding-a-background-colour-image)
* [Selecting a Background Image Size](designing-a-user-interface-to-capture-user-feedback.md#selecting-a-background-image-size)
* [Aligning the Background Image](designing-a-user-interface-to-capture-user-feedback.md#aligning-the-background-image)
* [Setting Header Title Properties](designing-a-user-interface-to-capture-user-feedback.md#setting-header-title-properties)
* [Setting the Properties of the Form Fields](designing-a-user-interface-to-capture-user-feedback.md#setting-the-properties-of-the-form-fields)
* [Adding Fields to the Form](designing-a-user-interface-to-capture-user-feedback.md#adding-fields-to-the-form)
* [Adding a Background Image for the Entire Page](designing-a-user-interface-to-capture-user-feedback.md#adding-a-background-image-to-the-entire-page)
* [Rearranging the Order of the Fields](designing-a-user-interface-to-capture-user-feedback.md#rearranging-the-order-of-the-fields)

#### <mark style="color:blue;">Adding a Background Colour/Image</mark>

&#x20;To add a background colour to the form header/body:

1. In the **Design** mode of the widget designer, click on a specific section, for example, the form's header section.
2. The Properties panel will be opened on the right.
3. Head to **Container** section and pick a **Background Colour**. The selected background colour will be applied to the form's header.
4. Instead, you can pick a background image if needed.
5. To add a background image:
   1. Click the **Search** button of the **Background Image** field.
   2. It will prompt a image gallery window to select a background image.
   3. Pick a background image from the gallery.
   4. Alternatively, you can upload your own image.
   5. To upload your own image:
      1. Click **Upload your image** button on the image gallery window.
      2. Drag your image onto the marked area or click on the area to select the image and upload it.

<figure><img src="../../../.gitbook/assets/Adding a Background ColourImage_s2.png" alt=""><figcaption><p>Adding a Background Colour/Image</p></figcaption></figure>

#### <mark style="color:blue;">Selecting a Background Image Size</mark>

After selecting a background image, you can choose the appropriate size for the header/body sections of the form.

The following are the background image sizes you can select:

* **Original Size -** The default size of the background image will be applied to the selected header/ body.
* **Fill Area** - The background image will fill the entire area of the header/body.
* **Fit into Area** - The entire image will be visible within the header/body without any part being cropped.

To select a background image size:

1. In the **Design** mode of the widget designer, click on a specific section, for example, the form's header section.
2. The Properties panel will be opened on the right.
3. Under the Container section, pick a suitable **Background Size** _e.g., Fill Area._ The selected background size will be applied to the respective section of the form.

#### <mark style="color:blue;">Aligning the Background Image</mark>

Selecting the alignment of the background image of the form header/body section denotes adjusting the way the background image of the form header/body is placed.

To select the background image alignment:

1. In the **Design** mode of the widget designer, click on a specific section, for example, the form's header section.
2. The Properties panel will be opened on the right.
3. On the Properties panel, go to the **Container** section.
4. In the **Background Position True** field, you'll find a diagram displaying multiple background image positions represented by circles. Choose an appropriate **circle** that corresponds to where you'd like to position the background image within the widget's header section.

<figure><img src="../../../.gitbook/assets/LC_Design a user interface from a database_s4.png" alt=""><figcaption><p>Aligning the Background Image</p></figcaption></figure>

#### <mark style="color:blue;">Setting Header Title Properties</mark>

To header title properties:

1. In the **Design** mode of the widget designer, click on the form's header section.
2. The Properties panel will be opened on the right.
3. On the Properties panel, go to the **Title** section. Modify the header title and customise header title properties to suit your specific preferences.
   1. To modify the header title, go to the Text field and type in the desired title.
   2. To change the colour of the title, select a colour from the displayed options or choose one from the colour palette.
   3. To change the font size of the header, type in the required size in the Size field.

<figure><img src="../../../.gitbook/assets/Setting Header Title Properties_s2.png" alt=""><figcaption><p>Setting Header Title properties</p></figcaption></figure>

#### <mark style="color:blue;">Setting the Properties of the Form Fields</mark>&#x20;

Users can customise fields of the form as follows:

1. In the **Design** mode of the widget designer, click on the form's body section.
2. Click on the desired **field** within the body section, and its **Properties** panel will display on the right.
3. Adjust the necessary properties of the field accordingly.

<figure><img src="../../../.gitbook/assets/Setting the Properties of the Form Fields_s2.png" alt=""><figcaption><p>Setting the Properties of the Form Fields</p></figcaption></figure>

To change the position of a field:

1. In the **Design** mode of the widget designer, click on the form's body section.&#x20;
2. Its **Properties** panel will be opened.
3. Within the body section, click on the field you wish to reposition.
4. Drag the field up or down to the desired location where you'd like it to be within the form's body section.

{% hint style="info" %}
**Note**: The position of a field can be changed only within the Body section of the form; in other words, you cannot drag and place it on the Header section.
{% endhint %}

#### <mark style="color:blue;">Adding Fields to the Form</mark>

Besides the fields available on the form, users have the flexibility to include additional fields to the form.

To add fields:

1. In the **Design** mode of the widget designer, go the the **Fields** tab on the left.
2. The fields that capture data of different input types will be listed, such as Drop-down list, checkbox, number input, etc.&#x20;
3. Select the desired field (_e.g., Dropdown list),_ and drag and drop it onto the body section of the form.
4. Provide a **Name** for the newly added field _e.g., Location._
5. Click **Done**_._

Further, you can customise the properties of each field according to your preference.

**Setting properties of a Drop-down List**

Users can customise a drop-down list by adding multiple different options to it. You have the choice to add options manually or import options from an external source.

To manually add options to a drop-down list on the form, follow these steps:

1. In the **Design** mode of the widget designer, click on the desired **drop-down**.
2. On the **Properties** panel, go to **Options** section.
3. Click **Add New Option** button. A text box will appear, allowing you to enter the name of the new option.
4. Type in a suitable option name.
5. Repeat steps 3-4 to add more options to the drop-down.

#### Setting Internal Values for Options in a Drop-down List

Besides the default label (a name given to identify a option in the list) of a option which is visible to users, you can configure a internal value which is not visible to users for each option in the list. Alternatively, you can set the same label as the internal values.

To set internal values for options:

1. After adding your options, deselect **Use label as value** option (By default, this option will be selected).
2. Upon deselecting the **Use label as value** option, a text box will be enabled for each option, allowing you to enter the **internal value.** This internal value is not visible to users.
3. Enter the **internal value** for each option.

<figure><img src="../../../.gitbook/assets/LC_Design a user interface from a database_s7.png" alt=""><figcaption><p>Setting Options and Internal Values</p></figcaption></figure>

#### Delete a Field from the Form

To remove a field from the form:

1\.     On the widget designer, click on the desired **field** to delete.

2\.     Click **Delete** icon. The field will be removed from the form.

#### <mark style="color:blue;">Adding a Background Image to the Entire Page</mark>

To add a background to the entire page:

1. On the widget designer, go to the **General** tab on the right.
2. Head to the **Share** section.
3. You can select a background image from the gallery or upload a image of your own for the entire page.
4. To select a  background image from the gallery:
   1. Click the **Search** button of the **Page Background Image** field.
   2. It will prompt a image gallery window to select a background image.
   3. Pick a background image from the gallery.
   4. Alternatively, you can upload your own image.
   5. To upload your own image:
      1. Click **Upload your image** button on the gallery.
      2. Drag your image onto the marked area or click on the area to select the image and upload it.

#### Rearranging the Order of the Fields

Fields in the form can be rearranged by dragging and dropping them to the required position in the form. This allows you to customize the layout and flow of your form to better suit your needs and the user experience.

1. In the **Design** mode of the widget designer, select the field to be moved.
2. Drag and drop the field to the required position in the form.

### <mark style="color:blue;">4. Using Widget Designer to Customise the Thank you Screen</mark>

The Thank you screen is displayed after a user submits the respective form. Using the widget designer, you have the capability to customise the appearance of the thank you screen of a form, enabling to see your personalised thank you screen upon submitting the form.

1. On the widget designer page (Design mode), click the **Form** toggle button on the bottom bar.
2. The view will be changed to **Thank you** screen.&#x20;

<figure><img src="../../../.gitbook/assets/LC_Design a user interface from a database_s9.png" alt=""><figcaption><p>Thank you screen</p></figcaption></figure>

#### <mark style="color:blue;">Setting the Thank you Screen's Header Properties</mark>

To set the Thank you Screen's Header Properties:

1. Click on the **header** section of the Thank You screen. Its **Properties** panel will be displayed on the right.
2. Do required changes to the header section from the Properties panel.

<figure><img src="../../../.gitbook/assets/Setting the Thank you Screen&#x27;s Header Properties_s3.png" alt=""><figcaption><p>Setting the Thank you Screen's Header Properties</p></figcaption></figure>

#### <mark style="color:blue;">Setting the Thank you Screen's Body Properties</mark>&#x20;

1. Click on the **body** section of the Thank You screen. Its **Properties** panel will be displayed on the right.
2. Do required changes to the body section from the Properties panel.

<figure><img src="../../../.gitbook/assets/Setting the Thank you Screen&#x27;s Body Properties_s2.png" alt=""><figcaption><p>Setting the Thank you Screen's Body Properties</p></figcaption></figure>

### <mark style="color:blue;">5. Previewing the Form</mark>

Preview mode can be used to view a live preview of the appearance and the behavior of the form.&#x20;

To preview your form:

1. On the widget designer page, click **Preview** button to change the mode to **Preview**.
2. The widget will be loaded in the preview mode.

#### Preview the Form in a New Window

To preview the form in a new window:

1. On the widget designer page, click the **Share** button at the top right.
2. Click **Open Page.**
3. Your form will launch a new window.

### <mark style="color:blue;">6. Saving the Form</mark>

After you have done required customisations, you can save the form for future reference.

1. On the widget designer page, click **Save Widget.**
2. Enter a **Name** for the widget (adding a name is mandatory).
   1. Go to **General** tab and enter the name.
3. Click **Save Widget**.

### <mark style="color:blue;">7. Sharing the Form with Others</mark>

After creating the form, you can share it with others. To learn more about this, refer to the article linked below.

{% content-ref url="../sharing-a-user-interface.md" %}
[sharing-a-user-interface.md](../sharing-a-user-interface.md)
{% endcontent-ref %}

Here is a short video on how to create a form to populate data in a database.

{% embed url="https://drive.google.com/file/d/1aBCYfS5Y29DJLe-C_FDnmCG6jyh0X5x2/view?usp=drive_link" %}
