# Internal Air Quality Monitoring

**Internal Air Quality (IAQ)**

Internal Air Quality (IAQ) data refers to the information collected from monitoring various factors that affect the quality of indoor air. This data typically includes measurements of parameters such as temperature, humidity, carbon dioxide (CO2) levels, etc.

**Importance of Monitoring and Maintaining IAQ Data**

* **Health and Comfort:** Poor IAQ can lead to health issues such as respiratory problems, allergies, and headaches. By monitoring IAQ data, building occupants can be aware of the air they breath and take necessary precautions to mitigate potential health risks.
* **Productivity:** Good IAQ is linked to improved cognitive function and productivity. Monitoring IAQ data can help create a healthier and more comfortable indoor environment, leading to higher productivity levels among occupants.
* **Energy Efficiency:** Proper ventilation and control of indoor air pollutants can improve energy efficiency by reducing the need for excessive heating, cooling, and ventilation.
* **Regulatory Compliance**: Many jurisdictions have regulations and guidelines in place to ensure indoor air quality meets certain standards. Monitoring IAQ data helps ensure compliance with these regulations.
* **Building Maintenance:** IAQ data can also help identify issues with building systems, such as ventilation systems or building materials, that may need maintenance or replacement to improve indoor air quality.

## IAQ Analytics Add-on

IAQ Analytics add-on provides a set of widgets for monitoring internal air quality parameters in your workplace. This process involves three main steps:

1. Installing IAQ Analytics Add-on
2. Configuring IAQ Analytics Add-on
3. Creating Your Canvas/Dashboard

### 1. Installing IAQ Analytics Add-on

Installing the IAQ Analytics add-on is the first step to monitor indoor air quality in your workplace.

To install the IAQ Analytics Add-on:

1. On the Lucy app **homepage**, click the **Add-ons** tab. Add-ons page will be displayed.
2. Click **Install a new Add-on**.&#x20;
3. Pick the IAQ Analytics add-on from the list of add-ons.
4. Click **Install**. The add-on will be installed and will appear on the Add-ons page.

{% hint style="info" %}
You can skip the installation if you have done it earlier.
{% endhint %}

### 2. Configuring IAQ Analytics Add-on

This step involves setting up and connecting your IAQ devices to gather data. There are five sources from which IAQ data can be obtained.

* **API**: Setup API to send IAQ data
* **uHoo sensor:** If you have a Uhoo sensor, you can use uHoo API key to automatically configure it and start receiving sensor data.
* **Simulator:** Generates data for display on your IAQ related widgets, which is particularly useful when sensors are not available.
* **AWAIR Sensors:** If you have AWAIR sensors, you can use API key and Organization ID to automatically sync sensor data.
* **Buy from Spaceworx marketplace:** Buy third party products from Spaceworx Marketplace.

You can pick required source and configure it.

In the absence of real-time sensor data, we'll opt for simulated data. Let's select the simulator option and move forward.

1. On the app **homepage**, click the **Add-ons** tab. Add-ons page will open.
2. Click on the **IAQ Analytics** add-on. A configuration wizard will open to configure it.
3. Click **Let’s Start.**
4. Select the source to obtain IAQ data.
   1. Pick the **Simulator** option.
   2. Click **Next**. Now the data will be simulated, and you don't need to configure anything further.
   3. Click **Close**.

### 3. Creating Your Canvas/Dashboard

The last step is to build the canvas.

To create a canvas:

1. On the Lucy app **homepage,** click the **Gallery** tab.
2. Click the **+** button. A wizard will pop up to start creating a new Canvas.
3. Click **Next**.
4. Select a color theme for your Canvas if necessary.
5. Provide a suitable unique **Name** for the canvas.
6. Grant Access to the Canvas.
   1. Select a User Group (e.g., System Administrators) if you wish to grant access to specific groups.
   2. Skip the User Group selection if you intend to allow access for everyone.
7. Click **Next**. A new Canvas will be created and listed on the Gallery page.
8. &#x20;Click **Go to your Canvas now** button to launch it in a new window.
9.  Pick and add IAQ related widgets on to your canvas.

    1. Click + button. Widget Browser will open.
    2. Use the Search box to search and filter required widgets by typing widget’s name/partial name, _e.g., IAQ._
    3. We’ll select e.g., IAQ Heat map and IAQ Levels Display widgets.
    4. Click **Add Widgets.**
    5. The widgets will be added to the canvas. As soon as you add widgets to the canvas, it will show the simulated data on each widget.

    &#x20;
