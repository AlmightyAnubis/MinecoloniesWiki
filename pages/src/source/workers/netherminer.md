---
type: worker
worker: netherminer
layout: worker
---
{% capture content %}
Being a Nether Miner is a dangerous job! The Nether Miner travels into the Nether and mines resources found there.  

The Nether Miner requires significant supplies. They require the following items, the level of the items based on the level of their hut (check the [worker](../systems/worker) system page). The food they require can be configured in the hut GUI.  

| Items required                |
| ----------------------------- |
| armor                         |
| axe                           |
| pickaxe                       |
| shovel                        |
| sword                         |
| flint & steel                 |
| food                          |
| 64 cobblestone (gets used up) |
| 32 torches (gets used up)     |
| 16 ladders (gets used up)     |

Once they have their tools & items, they will activate the nether portal and travel to the nether.  The nether is dangerous! They will fight mobs they encounter there, and it is possible for them to die on the trip. Their Adaptability skill will affect their survival chances. If they survive, they will return with loot. What they return with depends on the hut level and their Strength level.  

The Nether Miner can also craft lava buckets.

Note: The portal in the Nether Mine will transport players to the Nether. However, the Nether Miner does not actually travel into the Nether, nor do they actually mine any blocks in the Nether.
{% endcapture %}
{% capture infobox %}
{% include infobox/worker.html %}
{% endcapture %}
{% include page-infobox-wrapper.html content=content infobox=infobox %}