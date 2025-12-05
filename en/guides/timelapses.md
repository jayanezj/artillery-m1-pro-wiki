---
title: Timelapses
description: Guide to configure our Timelapses
published: true
date: 2025-12-05T20:04:56.151Z
tags:
editor: markdown
dateCreated: 2025-12-05T19:50:40.491Z
---

# 📸 What is a *Timelapse* in 3D Printing?

A **timelapse** is an accelerated recording technique that allows you to **show in just a few seconds or minutes** the entire manufacturing process of a part that, in reality, may take hours. It is one of the most visually striking resources in the world of 3D printing, used both for documentation and for artistic or educational content.

## 🧩 How does a timelapse work?

The idea is simple:  
Instead of recording a traditional video, the camera **captures a photo at a set time interval** (or at a specific event, such as “every time a layer finishes”). Later, all of these images are combined to form a high-speed video.

In this way:

- An **8-hour** print → becomes a **8–20 second** video.
- The progress of the piece is shown smoothly, dynamically, and visually.

## 🎥 Types of timelapses we can use on our Artillery M1 Pro

### 1. **Interval Timelapse – Hyperlapse –**
The camera takes a photo every *X* seconds.  
It’s simple, but it can show sudden or unpredictable toolhead movements, because the photos are taken while the printer is working.

- ✔️ Easy to configure.
- ❌ The toolhead may “cross” in front of the print.

> This is the type of Timelapse performed with the Stock Firmware. It can also be used with the community Firmware.
{.is-info}

### 2. **Layer Timelapse (the most popular)**
The camera takes a photo **at the end of each layer**, usually when the toolhead temporarily moves away or to a fixed position.

This method generates the famous *“headless timelapses”*, where it looks as if the part grows by magic.

- ✔️ Very clean video.
- ✔️ The toolhead is never in the way.
- ❌ Requires firmware or software support (in our case, that you have the community patches enabled).
- ❌ Print time will be noticeably longer since the extruder must move away on each layer to take the picture.

## Timelapse Examples

<table width="100%">
  <thead>
    <th>Settings used</th>
    <th>Timelapse</th>
    <th>Print times</th>
  </thead>
  <tr>
    <td>
      <ul>
        <li>Mode: Layer Macro</li>
        <li>Park Head: Enabled</li>
        <li>Park Time: 100ms</li>
        <li>Park Travel Speed: 400mm/s</li>
        <li>Park Position: Back Left</li>
        <li>Park Position Z-Hop: 0.2 mm</li>
        <li>Use Firmware retraction: Disabled</li>
        <li>Park Retraction Distance: 1mm</li>
        <li>Park Retraction Speed: 15mm/s</li>
        <li>Park Extrude Distance: 1mm</li>
        <li>Park Extrude Speed: 15mm/s</li>
        <li>Delay Compensation: 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-layer.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </center>
    </td>
    <td>
      4 hours 59 minutes.
    </td>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Mode: Hyperlapse</li>
        <li>Hyperlapse Cycle: 90s</li>
        <li>Park Head: Disabled</li>
        <li>Delay Compensation: 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-hyperlapse.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </center>
    </td>
    <td>
      4 hours 51 minutes.
    </td>
  </tr>
</table>

> You can configure the folder where Timelapses are stored in Fluidd by editing the ``moonraker.conf`` file. For example, if you want them saved inside ``timelapse`` on the Micro SD card:
>
> ```
> [timelapse]
> output_path: /home/mks/printer_data/gcodes/sda1/timelapse
> ```

> With the community Firmware, if desired, you can also make Hyperlapse park the extruder in a corner to take the captures, which can be useful in some prints where you want to play with capture timing to get multiple frames per layer.
{.is-info}
