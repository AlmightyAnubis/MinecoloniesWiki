---
type: worker
worker: smelter
layout: worker
---
{% capture content %}
The Smelter is a very important addition to help automate your colony. The Smelter will smelt ores into ingots for your colony's needs. The Smelter will require fuel to use in their furnace(s).

Smelters have a chance to double and even triple ores, depending on the Smeltery's level and the Smelter's Strength skill:

| Smeltery Level | Normal Output | % Chance of Doubling Output | % Chance of Tripling Output |
| :------------: | :-----------: | :-------------------------: | :-------------------------: |
|       1        |     100%      |       Strength Level        |             ---             |
|       2        |     100%      |      2x Strength Level      |             ---             |
|       3        |      ---      |            100%             |             ---             |
|       4        |      ---      |            100%             |       Strength Level        |
|       5        |      ---      |            100%             |      2x Strength Level      |

The higher a Smelter's Athletics level, the faster their furnaces will smelt.

In 1.18, the Smelter instead applies Fortune to the ores they smelt. The Fortune level they apply is 1 less than the Smeltery's level.  See the [Minecraft wiki](https://minecraft.fandom.com/wiki/Fortune#Ore) for details on Fortune.  Fortune IV (not on the table) will average 2.67 ores per ore.  This bonus doesn't apply to raw iron, copper, and gold chunks that the colony is given by the player, as it only applies to ores. 
{% endcapture %}
{% capture infobox %}
{% include infobox/worker.html %}
{% endcapture %}
{% include page-infobox-wrapper.html content=content infobox=infobox %}