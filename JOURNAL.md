---
title: "USB Hub"
author: "pizzalover125"
description: "A 6-port USB-C hub. "
created_at: "2025-07-26"
---

## 7/26/25
Today, I speedran this USB hub. I originally wanted an 8 port hub, but that would have required 3 daisy chained hub controllers, which would be terrible for speed. I settled for 6 (even though I could have fit in 6). I started off with the schematic. I used the chip from the USB Hub made by @msw in that one HC workshop. Around an hour later, I had this:
<img width="944" height="665" alt="image" src="https://github.com/user-attachments/assets/9a22b215-918f-4333-b935-8f1b76a5f0e3" />

I then began PCB layout. It took longer than expected, as I've never used this many tiny components. However, I think I did an excellent job that was well thought through. After around 45 minutes, I finished the layout. I then started routing. Routing was also pretty hard, but the thought-out layout made it a lot easier. After another 45 minutes, I had routed everything. Then, someone on the Slack told me to add ground pours. I had never done this before, but it wasn't too difficult. You just have to add a ground fill zone on both sides with structural vias that EasyEDA places for you. At the end, I finished!
<img width="501" height="576" alt="image" src="https://github.com/user-attachments/assets/7cb09a53-d37f-4c39-b96d-42369ae1cf03" />

This was one of my first full projects with EasyEDA. I'm not going to lie, EasyEDA isn't as bad as everybody makes it seem. It is a bit cluttered, but perfect for simple projects. It's also easier in some ways, such as not needing to import every footprint and symbol for every component (which sucks on KiCad). KiCad needs an LCSC plugin, which would make every thing 10 million times easier. 
