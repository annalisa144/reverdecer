---
title: How to get wifi from over 1 kilometer away
date: '2018-09-01 01:00:00'
image: phillip_wall_.jpg
layout: post
---

# Step 1: Find a company or friend with a fast internet connection

For us this is our uncle's lab that is about 1.2 km from El Terreno.

# Step 2: Find line-of-site between locations

The signal will be degraded or even blocked completely by trees, walls, hills, etc. Istall so that the radios can "see" each other without obstructions. Usually this means putting them on top of a roof or tower.

# Step 3: Install two directional antennas and point them at each other

Directional antennas are needed because they have a much better range than the omnidirectional antenna. They also need to be aimed at each other. For this setup I chose the [Ubiquiti LiteBeam AC](https://www.amazon.com/gp/product/B06Y2JH7PV/ref=as_li_tl?ie=UTF8&tag=annalisa144-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B06Y2JH7PV&linkId=ccd61c7a76bb59335bfcbff6e241f3d1) because of it's directional antenna design,  good value, and positive experiance with the brand in the past.

The LiteBeam that is at the location with existing internet is set up as the "Access point," and the LiteBeam at the remote location set up as a "Station."

[![](/images/antenna_alignment_tool_.jpg)](/images/antenna_alignment_tool.jpg)

The administration webpage of the LiteBeam has an Antenna Alignment Tool.  Rotate the antenna left and right and up and down until the position that gives the best signal is found.  I had to go back and forth between the two radio sites a few times to adjust each antenna's position to get the best results.

# Step 4: Set up a WiFi Access Point
At this point I had to plug my laptop into the LiteBream with a ethernet cable. To be able to connect all our laptops and smartphones wirelessly I installed a [TP-Link access point](https://www.amazon.com/gp/product/B00E98O7GC/ref=as_li_tl?ie=UTF8&tag=annalisa144-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B00E98O7GC&linkId=c3d50ade10305afa91ebfd40ed49928a).

We've been completely satisfied with our internet speed and reliability using this system.
