---
type: building
building: apiary
layout: building
---
{% capture content %}
The Apiary is where the Beekeeper works. The Beekeeper breeds bees and harvests honeycombs or honey bottles (you can
choose which on the second page of the Apiary's GUI).

The level of the Apiary determines the max number of hives the Beekeeper can take care of:

| Apiary Level | Max Number of Hives |
| ------------ | ------------------- |
| 1            | 1                   |
| 2            | 2                   |
| 3            | 4                   |
| 4            | 8                   |
| 5            | 16                  |

**Note:** If the Beekeeper is asking for hives but there are some nearby, make sure you've set the hives for them to
take care of with the hive tool. This tool is accessed from the second page of the Apiary GUI (see below).
{% endcapture %}
{% capture infobox %}
{% include infobox/building.html %}
{% endcapture %}
{% include page-infobox-wrapper.html content=content infobox=infobox %}

## Apiary GUI

{% include contentblock/building/main-gui.html header="When accessing the Apiary Hut block by right-clicking on it, you will see a GUI with different options. You start on the main tab:" image="../../assets/images/gui/apiarygui1.png" %}

{% include contentblock/building/stock-gui.html buildingname="Apiary" header="The second tab of the GUI is <strong>Minimum Stock</strong>. It has one button:" image="../../assets/images/gui/apiarygui2.png" %}

{% include contentblock/building/settings-gui.html key="apiary" header="The third tab of the GUI is <strong>Settings</strong>. It has two buttons:" image="../../assets/images/gui/apiarygui3.png" %}

{% include contentblock/building/other-gui.html header="The fourth tab of the GUI is <strong>Flowers</strong>." content="Here you designate what flowers you want the Beekeeper to request and use during breeding. By default, all flowers are turned off." image="../../assets/images/gui/apiarygui4.png" %}

{% include contentblock/building/other-gui.html header="The fifth tab of the GUI is <strong>Hive Tool</strong>." content="Click this button to get the hive tool, which is how you select which hives the Beekeeper will take care of. To select a hive, right-click on it with the hive tool. Right-click on a hive again to remove it." image="../../assets/images/gui/apiarygui5.png" %}