![sky island banner](https://debug-blog.jolchawa.site/projects/houdini-sky-islands/sky_island_banner.png)
![sky island banner](https://i.pinimg.com/originals/2d/1e/8b/2d1e8b2d9f918d0f8a4cf19ac2210ce6.gif)

**Tags:** Procedural Mesh  
**Software:** Houdini, Unreal Engine
**Project Total Time:** 2 weeks

---
# The Problem
When working on my latest seasonal shaders, I found it difficult to display how they worked without stress testing them on a variety of topology. Using Legend of Zelda; Tears of the Kingdom as my greatest inspiration, I took to making a sky island generator that can easily procedurally create a variety of islands quickly with seed values.

# How I Made It
To create this tool I used Houdini for its logic of procedural generation based on a cube shape. The shape is then built up into more rounded formations with harder rocks, the inner most sections are masked to spawn actors. The final HDA is loaded into 3D software such as Unreal Engine to take full advantage of its actor placement based on static mesh references. 
[Link to my blog post on how I made it](https://debug-blog.jolchawa.site/blog/sky-island-generator/)

# Final Result

![sky island banner][https://debug-blog.jolchawa.site/projects/houdini-sky-islands/island_making.gif]


---
You can download the otl to use the file, don't forget to change the references once within Unreal engine. You can consult the documentation pdf for more info.