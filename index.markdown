---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: noisehost
instagram:
  na_zakatnom_nebe: CnVJTlUgB57
  reka: Cnt62m2ANNL
youtube:
  reka: DD_8eGjq03k
---

# What is Lorem Ipsum?
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

{% include socials.html %}

---

# Photos

{% include image-gallery.html folder="assets/promo" %}

---

# Music

<div width="fit-content">
<iframe 
  style="border: 0; width: 100%;" 
  src="https://bandcamp.com/EmbeddedPlayer/album=464641135/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/transparent=true/" seamless>
  <a href="https://noisehost.bandcamp.com/album/-">пена by noisehost</a>
</iframe>
<iframe 
  style="border: 0; width: 100%;" 
  src="https://bandcamp.com/EmbeddedPlayer/track=3080292966/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/transparent=true/" seamless>
  <a href="https://noisehost.bandcamp.com/track/--5">река by noisehost</a>
</iframe>
</div>
---

# Videos

{% include youtube_player.html id=page.youtube.reka %}

{% include instagram_player.html id=page.instagram.na_zakatnom_nebe %}