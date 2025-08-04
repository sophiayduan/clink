---
title: "Clink"
author: "Sophia"
description: "A small eink display clock"
created: "2025-07-31"
---

**Running hour total: 16h**

# July 31st: done

**Total time spent: 9h**

Last night I decided I wanted an eink clock and today was my last chance to make one, so I sat down and got TONS of work done. 

It's a eink display with wifi connectivity and a rotary encoder for manual control. It draws power from a LiPo battery but can also use USB-C (code uploaded through it too)
Based on my previous project I was familiar with the ESP-12F and its wifi capabilities so I chose for it to be my mcu for Clink. 

I recently jailbroke my kindle and become more interested in e-ink displays, I thought it'd be a good fit for Clink as I don't want it to emit light (so I can't see it in the dark).

<img width="1114" height="785" alt="image" src="https://github.com/user-attachments/assets/cbdfafea-d1dc-48ca-a466-b19d50386e3b" />

I cadded this plain case, it was really rushed and I didn't realize that the rotary encoder has no way of being reached (I'm writing this in retrospect). 
Definitely not my proudest work, at all.

<img width="453" height="734" alt="image" src="https://github.com/user-attachments/assets/097640df-f90d-46eb-a1e7-1075677bf4c9" />
<img width="435" height="655" alt="image" src="https://github.com/user-attachments/assets/996a223d-3cb9-4e5f-b448-574bee1aab50" />

# August 1st: New look

**Total time spent: 4h**

Yesterday, I rushed a terrible CAD model and today my goal was to fix it. Once I began I realized it was really difficult and impractial to mount the PCB in a way that the rotary encoder could be used. 

I remade my PCB to better fit my case. The biggest change was making the rotary encoder come out from the side with my USB-C.
<img width="700" alt="image" src="https://github.com/user-attachments/assets/584fdcc3-5296-4001-9d2b-0c59e753f434" />

I really enjoyed routing a pcb that had few components and didn't have rigid requirements unlike my [3D printer tracker](https://github.com/sophiayduan/Endev-board).

For the case I opted for a retro vibe: 

<img width="650" alt="image" src="https://github.com/user-attachments/assets/861992a5-5591-4572-9cb6-99f105f70f2d" />

# August 3rd: Polish

**Total time spent: 3h**

Created a quick design in Canva just so I can have a nice render: 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/254fc969-e77d-4d7d-a8b2-9f3679796720" />

It was my first time using decals in fusion, it was pretty neat. 

Then I modified the CAD to allow the PCB to be screwed on from the bottom of the case (moved a mounting hole to make the placement nicer). I just recently updated fusion and I can't seem to insert fastners anymore (hence why there are no screws nor bolts in the cad).

The rotary encoder knob is currently floating in midair as I'm buying the rotary encoder from aliexpress and so I'm not sure of its dimensions (i'll just modify the cad once I receive the part). 

This wasn't very efficient cadding, especially how I did the chamfers and fillets, but it got the job done.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/31cd8ae3-8d2e-4e8c-a860-743e3bae4715" />


Here is the final render:

<img width="700" alt="render" src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/b21b218f5ce1a157c9686fbcfeec3123eacc6e43_untitled_v14.png">
