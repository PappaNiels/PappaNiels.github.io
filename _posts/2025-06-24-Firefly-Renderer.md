---
layout: post
title:  "Firefly renderer"
date:   2025-06-24 19:00:13 +0100
categories: posts
---

During my second year at Breda University of Applied Sciences, I had an assignment to create a 3D renderer in 8 weeks with a team. This renderer was created with 5 other graphics programmers. We had a couple of requirements. We needed to stick to the API of the engine template that was given to us, and we had to support two platforms. We had to support Windows using Microsofts DirectX 12 API and we had to support the Playstation 5. Because we also had two teams that were going to use the renderer in their game engine, we also had the challenge of integrating our renderer into their engine. Luckily, everything turned out well. So well, that we made a game with the FPS engine that used our renderer (which has been altered for our needs). The link to the itch.io page of the game can be found [here](https://buas.itch.io/nakon).
Below are some screenshots and the feature list on how we achieved such.

### Features

**I worked on these features:**
- Complete platform independed renderer
- Deferred rendering 
- Skeletal animation
- SSAO
- Render layers

**Other features:**
- Font rendering
- Bloom
- Shadows for directional lights
- Decals
- IBL

### Screenshots & Videos

<figure>
    <img src="../../../../assets/firefly/deferred-point-lights.png"
         alt="Frustum drawn out to show how we capture the depth"
         height=400
         width=450>
    <figcaption><i>Deferred lighting on sponza.</i></figcaption>
</figure>

<figure>
    <img src="../../../../assets/firefly/sponza-final.png"
         alt="Frustum drawn out to show how we capture the depth"
         height=400
         width=450>
    <figcaption><i>Deferred lighting on sponza with IBL and shadows.</i></figcaption>
</figure>

<video width="750" height="480" controls>
  <source src="../../../../assets/firefly/skeletal-animation.mp4" type="video/mp4">
</video>

[![]()](../../../../assets/firefly/ui-demo.mp4)

<video width="750" height="480" controls>
  <source src="../../../../assets/firefly/ui-demo.mp4" type="video/mp4">
</video>

[![]()](../../../../assets/firefly/ui-demo.mp4)