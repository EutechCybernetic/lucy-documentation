# Designing a User Interface to Visualise Information

Designing user interfaces to visualise data is a powerful way to derive meaningful insights. Depending on the data and the user's goals, designers choose appropriate visualisation types, which can include charts, graphs, maps and more.

&#x20;This article shows how to design a user interface to visualise your data and explains the two distinct approaches to do that:

1. [Visualising Data by Selecting a Data source](designing-a-user-interface-to-visualise-information.md#id-1.-visualising-data-by-selecting-a-data-source)
2. [Starting from Scratch by Selecting a Template](designing-a-user-interface-to-visualise-information.md#id-2.-starting-from-scratch-by-selecting-a-template)

{% hint style="info" %}
**Note**: Before you go ahead with any of these methods, ensure that a data source (database/workflow) is ready in the system.
{% endhint %}

## <mark style="color:blue;">1. Visualising Data by Selecting a Data source</mark>

Before designing a user interface for data visualisation, the first step is to select a data source. This could involve choosing a workflow or a database to obtain the data that will be visualised.

To illustrate the concept, we'll design a user interface that displays the maximum sales for each product line with the status 'Shipped' and we'll choose a database as the data source.

### <mark style="color:blue;">a) Selecting a Data source</mark>

To select a data source:

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. Search and select the **folder** you wish to open.
3. Go to the **User Interfaces** tab.
4. Click on the **Add** button.
5. Choose the **Visualise Data** option.
6. Select the **data source**. You can either select a workflow or a database as the data source.
7.  For instance, let’s select an existing database.

    1. To select an existing database, head to the **Databases** tab. All the databases created in the system will be listed categorised by its folder.
    2. Choose and click on the required **database**. Alternatively, you can use the search box to search and filter databases.
    3. A preview displaying the available fields of the chosen database will be listed.
    4. To confirm the selection, click **Select this source** .
    5. A table preview of the selected database will be displayed.



<figure><img src="../../.gitbook/assets/Preview of your data_s2.png" alt=""><figcaption><p>A preview of your data</p></figcaption></figure>

### <mark style="color:blue;">b) Preparing Data to be Visualised</mark>

You can determine the specific data to display on the widget by utilising features like data filtering and aggregation. We'll apply a filter to isolate product lines with a 'Shipped' status and then display the maximum sales for each respective product line from the previously selected database.

#### <mark style="color:blue;">Filtering Data</mark>

Filtering data is used to extract a subset of data that meets specific criteria or conditions. It helps in narrowing down the dataset to focus on a particular subset of interest.

1. On the table preview, click **Filter Data.**
2. Click **Add** button to add a new filter condition.&#x20;
3. You can add multiple conditions to filter your data.
   1. To add multiple filter conditions, click **Add** button _e.g., To have two filter conditions, click the Add button twice._&#x20;
   2. To filter data by selecting one condition or any other condition, click **Either** button.
   3. To filter data by selecting all the conditions added, click **All** button.
4. Select appropriate fields, operation and values for the respective condition (s).
5. After applying the condition (s), click **Done**.
6. Based on the conditions applied, the data will be filtered and listed.

<figure><img src="../../.gitbook/assets/Filtering data_s2.png" alt=""><figcaption><p>Filtering data</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Filtered data_s3 (3).png" alt=""><figcaption><p>Filtered data</p></figcaption></figure>

#### <mark style="color:blue;">Adding Group of Conditions</mark>

When dealing with complex datasets, a single condition may not be sufficient. Grouping conditions enables you to create more sophisticated filters, combining multiple criteria to obtain the desired subset of data.

{% hint style="info" %}
For our example, adding group of conditions is not needed.
{% endhint %}

1. On the table preview, click **Filter Data.**
2. Click the **Filter** button to add a new group of conditions. Tip: Repeat step 2 to add more group of conditions.
3. Within the newly added group of conditions, click **Add** button to add a new filter condition inside it. Tip: Repeat step 3 to add more conditions under respective group of conditions.
4. Within a group of conditions, you can include multiple group of conditions. Click the **Filter** button inside a group of conditions to add multiple group of conditions inside the respective group.
5. To filter data by selecting one condition or any other condition, click **Either** button.
6. To filter data by selecting all the conditions added, click **All** button.
7. After applying the conditions, click **Done**.
8. Based on the conditions applied, the data will be filtered and listed.

{% hint style="success" %}
Within a group of conditions, you can include multiple conditions.
{% endhint %}

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s3.png" alt=""><figcaption><p>Adding a group of conditions to filter data</p></figcaption></figure>

#### <mark style="color:blue;">Aggregating Data</mark>

Aggregating data is used to summarise and condense data into a more compact form, often achieved by mathematical or statistical operations (_e.g., Aggregating data to find the maximum sales for each product line)._

1. On the table preview, click **Aggregate Data**.&#x20;
2. Select appropriate filters to aggregate data.
3. Click **Done**. Based on the aggregation, the data will be aggregated and listed.
4. If you are happy with the aggregation, click **Looks good.**

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s5.png" alt=""><figcaption><p>Aggregating data screen 1 </p></figcaption></figure>

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s6.png" alt=""><figcaption><p>Aggregating data screen 2</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s7.png" alt=""><figcaption><p>A Preview of aggregated data</p></figcaption></figure>

### <mark style="color:blue;">c) Selecting a Template</mark>

After selecting a data source and preparing data as needed, you can select a template to begin customisation. Based on the data selected, the system will display a list of matching templates that work with those data.

For example, we'll select the Bar/Line chart template from the available template list.

1. Select the desired type of **Template** to display data _e.g., Bar/Line chart._
2. Click **Edit this template**. The respective template will be displayed on widget designer page.
3. By default, **Design** mode will be selected on the widget designer page.



{% hint style="info" %}
There are two mode for a widget designer page:

1\) Design mode - Used to design, edit, and customise the widget.

2\) Preview mode - Used to view a live version of the widget.
{% endhint %}

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s8.png" alt=""><figcaption><p>Widget Designer</p></figcaption></figure>

### <mark style="color:blue;">d) Customising the Widget</mark>

A Bar/Line chart can be customised to meet the user's needs by adjusting its appearance, changing the way data is presented (e.g., selecting different chart types), customising legends, axis labels and other elements to provide context and improve the understanding of the presented information.

There are 3 main types of charts: **line charts, bar charts, and area charts**.

You can choose either a single chart type or multiple chart types to display on the same chart. For example, you can have both a bar chart and a line chart on a single chart.



<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s9.png" alt=""><figcaption><p>Chart Types</p></figcaption></figure>

#### <mark style="color:blue;">Selecting a Single Chart Type</mark>

1. Click on the chart on the widget designer page, its **Properties** panel will open.
2. On the properties panel, go to **Chart Elements** section and click the **Plus** icon.
3. By default, the bar chart will be selected and displayed on the chart.
4. To select a different chart type, select the appropriate chart type _e.g., Line chart._
   1. The current chart type will be replaced with the newly selected chart type and the new chart will be displayed on the widget.

#### <mark style="color:blue;">Selecting Multiple Chart Types</mark>

You can include multiple chart types within the same chart. For instance, if your primary chart is a line chart, you can add a bar chart, and both chart types will be displayed together.&#x20;

1. After you have applied a chart as described under [<mark style="color:blue;">Selecting a Single Chart Type,</mark> ](designing-a-user-interface-to-visualise-information.md#selecting-a-single-chart-type)you can select multiple if necessary.
2. On the properties panel, go to **Chart Elements** section.
3. Click **Plus** icon next to Chart Elements.
4. Select the appropriate chart type _e.g., Bar chart._

{% hint style="info" %}
**Note**: You need to have a data source bound to every chart type added.
{% endhint %}

#### <mark style="color:blue;">Adding</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**X-axis and Value Fields**</mark>

1. Click on the **Bar/Line chart** on the widget designer page, its **Properties** panel will be displayed.
2. Head to **X-axis Label** section. In the **X-axis Field** list, select group option.
3. Go to **Chart Elements** section. In the **Value Field** list, select the value option.
4. Go to **Appearance** section, enable **Show Y-axis** option to display the y-axis on the chart.



{% hint style="success" %}
**Tip**: The **group** column and the **value** column are taken from the data prepared to be displayed on the chart (See [Preview of your data](designing-a-user-interface-to-visualise-information.md#previewing-your-widget) visualised on a chart image).
{% endhint %}

#### <mark style="color:blue;">Customising the Appearance of the Chart</mark>

To change the appearance of the chart:

1. Click on the **Bar/Line chart** on the widget designer page, its **Properties** panel will be displayed.
2. Go to **Appearance** section. Do required changes to the appearance of the chart.



<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s10.png" alt=""><figcaption><p>Customising the Appearance of the Chart</p></figcaption></figure>

#### <mark style="color:blue;">Adding a Chart Title</mark>&#x20;

To add a chart title:

1. Click on the widget's **Header** section, and its **Properties** panel will be displayed.
2. Go to the **Title** section.
3. In the **Text** field, enter a suitable title for the chart. The chart title will dynamically update in real-time as you type.

&#x20;The below image shows a preview of your designed chart in the Preview mode. (See how to [preview your data ](designing-a-user-interface-to-visualise-information.md#previewing-your-widget)visualised on a chart image).

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s8_1.png" alt=""><figcaption><p>Chart Preview</p></figcaption></figure>

## <mark style="color:blue;">2. Starting from Scratch by Selecting a Template</mark>

This method initiates the user interface design process for data visualisation by selecting a template and subsequently binding a data source at a later stage.

As the data source, you can choose either a database or a workflow for the data for visualisation.

To design a user interface from scratch:

1. On the app **homepage**, go to the **My Work** tab on the left sidebar.
2. Search and select the **folder**.
3. Go to the **User Interfaces** tab.
4. Click **Add**.
5. Pick **Start from Scratch** option.
6. Select the desired type of Template to display data _e.g., Radial Gauge._
7. Click **Edit this template**. The respective template will be displayed on the widget designer page.
8. By default, **Design** mode will be selected on the widget designer page.

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s11.png" alt=""><figcaption><p>Widget Designer</p></figcaption></figure>

### <mark style="color:blue;">a) Binding a Data source</mark>

Once you've chosen the appropriate template, you can then decide which data source to associate with the widget. A data source provides the raw data that the widget visualises. Without a data source, there's no information to present visually.

To bind a data source to the widget:

1. On the widget designer page, click **Data source is required** option.
2. Click **Bind a Source.**
3. As the data source, you can either select a workflow or a database to obtain data to be visualised.
4. For instance, let’s select an existing database.
   1. To select an existing database, head to the **Databases** tab. All the databases created in the system will be listed categorised by its folder.
   2. Choose and click on the required **database**. Alternatively, you can use the search box to search and filter databases.
   3. A preview displaying the available fields of the chosen database will be listed.
   4. To confirm the selection, click **Select this source** .
   5. A table preview of the selected database will be displayed.

### <mark style="color:blue;">b) Preparing Data to be Visualised</mark>

Next, step is to customise data to be visualised on the widget.

#### <mark style="color:blue;">Aggregating Data</mark>

For instance, let's use aggregation to summarise data to display minimum temperature in a radial gauge.

1. On the table preview, click **Aggregate Data.**
2. Select appropriate aggregation and the columns required for the aggregation.
3. After applying the aggregation, click **Done**.
4. If you are happy with the aggregation, click **Looks good**.&#x20;

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s12.png" alt=""><figcaption><p>Filtering Data</p></figcaption></figure>

### <mark style="color:blue;">c) Customising the Widget</mark>

This involves modifying various visual and functional aspects of the widget to suit specific needs and preferences, such as setting minimum and maximum values of the scale.&#x20;

To set properties of the radial gauge:

1. On the widget designer page, click on the **Radial Gauge.** The **Properties** panel will be displayed.
2. On the properties panel, set properties as required.

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s13_1.png" alt=""><figcaption><p>Setting Properties of the Gauge</p></figcaption></figure>



{% hint style="info" %}
It is necessary to specify the Field of the data source to be bound and generally, it is a single field. In data binding, it is the **Value** field.

To set the Field:

1. Click on the **Radial Gauge.** The **Properties** panel will be displayed.
2. Head to Gauge section.
3. Choose the Field.
{% endhint %}

#### <mark style="color:blue;">Customising the Appearance and Styling</mark>

Customising the appearance and style of a radial gauge widget involves making visual adjustments to its elements, including colours, scales, labels, and other design aspects.

1. On the widget designer page, click on the **Radial Gauge**, The **Properties** panel will be opened on the right.
2. On the properties panel, go to **Colours** section.
3. Customise the visual aesthetics of the radial gauge according to your preferences.
4. After setting the properties, provide a appropriate **Name** for the widget under **General** tab.

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s14.png" alt=""><figcaption><p>Customising Colours of the Radial Gauge</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s15.png" alt=""><figcaption><p>Customising the Styling Properties of the Radial Gauge</p></figcaption></figure>

#### <mark style="color:blue;">Customising the Properties of the Widget's Header Section</mark>

To customise the properties of the widget’s header section:

1. On the widget designer page, click on the widget’s header section to open its Properties panel.
2. Go to the Container section to pick a background colour for the header or you can select a background image.
3. In the Text field, enter the Title of the widget.
4. Select a colour for the title.
5. Type in the font size of the title. Instead, you can use the up and down arrows to increase or decrease the font size.

The below image shows a preview of your designed gauge in the Preview mode. (See how to [preview your data](designing-a-user-interface-to-visualise-information.md#previewing-your-widget) on the gauge).

<figure><img src="../../.gitbook/assets/LC_Designing a user interface to visualize information_s16.png" alt=""><figcaption><p>Radial Gauge in the Preview Mode</p></figcaption></figure>

## <mark style="color:blue;">Previewing Your Widget</mark>

Preview mode can be used to view a live preview of the appearance and the behavior of the widget.&#x20;

1. On the widget designer page, click **Preview** button to change the mode to **Preview**.
2. The widget will be displayed in the preview mode.

## <mark style="color:blue;">Saving Your Widget</mark>

After you have done required customisations, you can save the widget for future reference.

1. On the widget designer page, click **Save Widget.**
2. Under General tab, enter a **Name** for the widget (adding a name is mandatory).
3. Add a Description if necessary.
4. Click **Save** Widget.

The system stores all your saved widgets under the User Interfaces tab of the respective folder.

## <mark style="color:blue;">Sharing Your Widget</mark>

After you have designed a widget, you can share it with others. Find out more in the article below.

{% content-ref url="../sharing-a-user-interface.md" %}
[sharing-a-user-interface.md](../sharing-a-user-interface.md)
{% endcontent-ref %}

