---
type: worker
worker: concretemixer
layout: worker
---
{% capture content %}
The Concrete Mixer is a part of your colony's production line. The Concrete Mixer will craft all types of concrete powder and place them in flowing water (built in to their hut), then mine the resulting concrete. The Concrete Mixer will only make concrete and concrete powder when they receive a request for a block and have the needed materials. (All their recipes are pretaught.)

A Concrete Mixer's Stamina level affects the amount of time it takes for them to harvest the concrete. Their Dexterity level affects the time it takes for them to craft the concrete powder.
{% endcapture %}
{% capture infobox %}
{% include infobox/worker.html %}
{% endcapture %}
{% include page-infobox-wrapper.html content=content infobox=infobox %}