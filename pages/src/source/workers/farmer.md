---
type: worker
worker: farmer
layout: worker
---
{% capture content %}
The Farmer is the backbone of your food production. The Farmer will cultivate the crops you assign it through the [Field](../../source/buildings/farm) block (a scarecrow).

Before the Farmer can start, you need to craft the Field block. Place the Field block in the plot of land you want the Farmer to work on and right-click on it to access its GUI. Here you will place the crop you want for this specific field to be cultivated. The crops the Farmer will currently cultivate are wheat, carrots, potatoes, beets, melons, pumpkins, and most crops from other mods as long as they have normal growth behavior. (Sugarcane, cactus, and bamboo are produced by the [Planter](../../source/workers/planter).)

The Farmer will also craft seeds, carved pumpkins, hay bales, [composted dirt](../../source/items/compost), and coarse dirt. They will only make these items when they have been taught the recipes, receive a request for an item, and have the needed materials.

**Note:** The Farmer can only learn a set number of recipes based on their hut level. So:

| Hut Level | Recipes |
| --------- | ------- |
| 1         | 10      |
| 2         | 20      |
| 3         | 40      |
| 4         | 80      |
| 5         | 160     |

The higher a Farmer's Stamina level, the less time they will take between cycles of planting and harvesting. The higher their Athletics level, the less time they will take to plant/harvest each crop.
{% endcapture %}
{% capture infobox %}
{% include infobox/worker.html %}
{% endcapture %}
{% include page-infobox-wrapper.html content=content infobox=infobox %}