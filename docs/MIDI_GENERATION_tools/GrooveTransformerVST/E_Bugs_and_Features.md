---
title: Bugs & Planned Features
description: A list of known bugs and planned future features for GrooveTransformer VST.
permalink: /GrooveTransformer/Bugs&features/
parent: GrooveTransformer
has_children: true
nav_order: 34
layout: supplement_page
---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

Below is a compilation of known bugs and features we plan to implement. 

{: .highlight}
> To report a bug, request a feature or any other inquiry, please use the appropriate channels specified [here]({{site.BaseURL}}/GrooveTransformer/Contact/)

## Version 0.0.1 

**Preset Management:**

- [ ] When loading a pattern, some of the sliders and buttons are correctly loaded on the GUI, but the plugin doesn't use their latest value unless they are manually clicked. 
- [ ] Deleting a preset is not implemented yet (although the control is available on the GUI)
- [ ] When a preset is over-written by mistake, it can not be undone! should be able to prompt user if they are sure to over-write!!
- [ ] In general, better preset management should be implemented!

**Autonomous Features:**
 
- [ ] Other adaptive algorithms should be implemented

**Rhythm Detection from Audio:**

- [ ] At this moment, audio detection only works with a 44.1kHz sample rate. So if you want to work with audio, make sure your host or the standalone app is set to this sample rate. We will implement a resampling algorithm to allow the plugin to work with any sample rate!