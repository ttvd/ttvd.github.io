---
layout: post
title: Loading MagicaVoxel Voxel Vox files into Houdini
categories:
- blog
- voxel
- houdini
- volumes
- houdini plugin
- video
---

As some of you may know, I have been working on a small C voxel engine for a while. In order to create test assets I have been using the incredibly powerful [MagicaVoxel](https://ephtracy.github.io/) voxel editor.

At this point I am about to start experimenting with voxel key frame animations. For this, I have written a small [Houdini](http://www.sidefx.com/) [GEO node plugin](https://github.com/ttvd/houdini-geo-vox) to load MagicaVoxel .vox files as Houdini float 4 (rgba) volumes. It lets you load .vox files directly through the file SOP node.

<iframe src="https://player.vimeo.com/video/160024226" width="800" height="600" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p>

<br>

The code for GEO .vox node is available in [houdini-geo-vox](https://github.com/ttvd/houdini-geo-vox) repository.
