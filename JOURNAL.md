---
title: "MagFire"
author: "Know Scratcher"
description: "A portable magnetic cannon."
created_at: "2025-05-29"
---

# May 29th: Learn how to use CAD software.

I found a CAD software called FreeCAD, and I spend some time learning it through [a Youtube tutorial video](https://www.youtube.com/watch?v=jULWgMV9_TM&ab_channel=CADCAMLessons) and reading the docs.
![youtube tutorial](https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/learn_tut.png)

![design](https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/learn_design.png)

**Total time spent: 3h**

# May 30th: Learn how to design a PCB.

Really, like I learn PCB design the first time, and I'm really hoping I could get used to it.
So, I watch a [tutorial](https://www.youtube.com/watch?v=3E5REDAQk_A&ab_channel=ElectronicswithEmrys) on youtube and on [hackpack guide](https://hackpad.hackclub.com/guide). Using KiCad is actually easier then I thought.

here's a sample uploaded to jlcpcb.com
![jlc](https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/test_upload_pcb.png)

Overall, it's still pretty fun to try all these thing that I could have never try living in this environment. Hope the project could go off without a hitch.

**Total time spent: 2h**

# June 1st: Do some research

So today I watched a [video](https://www.youtube.com/watch?v=eH6ensqVQTw&ab_channel=%E4%BD%91%E4%BE%86%E4%BA%86) that kinda make some ideas for me, but the main thing is that it uses a 450v 650uF capacitor, and I definitely have to worry about that cus I don't really work with full "circuiting" much, so I'm thinking whether the PCB I might design later will burn out of something.

Then I took out my physics book and start turning the pages and noticed that I don't understand any equation at all.
![physics book](https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/20250601physics_book.jpg)

Therefore instead of working with equations (which I might ask for my physics teacher for some help), I ask Gemini for help on impulse circuit and how to charge the capacitor.

Then it gave me this.(which doesn't work)
![gemini circuit](https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/20250601gemini.png)

Well, it sure doesn't work when I open [Falstad circuit](https://www.falstad.com/circuit/circuitjs.html).
So I just try to design my own, and to my surprise, I think I did a great job.
![circuit](https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/20250601circuit.png)

**Total time spent: 2h**

# June 2nd: Draw a draft design for the cannon

So I drew a draft design on my notebook and did some calculation to make sure I won't violate any local laws.

The funny thing is, I forgot to bring the notebook home, so the image will be updated tomorrow. lol

<img src="https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/20250602draft.jpg" height="400" alt="draft">

**Total time spent: 2h**

# June 3rd: Went to a local store to look up the items

I went to a local electronic store to see if I can find anything that might be on the design, mostly because I need some ideas to continue my design. By the way, I collected some data for the BOM.

<img src="https://raw.githubusercontent.com/KnowScratcher/MagFire/refs/heads/main/img/20250605bom.jpg" height="400" alt="the kinda bom like thing">

I then found a [youtube video](https://www.youtube.com/watch?v=vmDZY8jU7f4&ab_channel=LeviJanssen) that looks super cool after returning, but it uses a inductor boost, which doesn't work at all.

Then I go with my original plan, find a voltage transformer and a capacitor to store the electric energy, then use a coil to make the magnetic force to push the iron ball out.

I found a [voltage transformer](https://shopee.tw/-%E7%92%B0%E5%B3%B6%E7%A7%91%E6%8A%80-DC-DC%E9%AB%98%E5%A3%93%E5%8D%87%E5%A3%93%E6%A8%A1%E5%A1%8AZVS-%E9%9B%BB%E5%AE%B9%E5%85%85%E9%9B%BB%E9%9B%BB%E7%A3%81%E7%82%AE45-390V-780V%E5%8F%AF%E8%AA%BF5A-i.280233910.5746752217?sp_atk=b6119ab3-18fe-4849-a5ef-aec26a2a666e&xptdk=b6119ab3-18fe-4849-a5ef-aec26a2a666e) on a famous online shopping site locally. It's looking super convincing to me so, probably I'll give it a go.