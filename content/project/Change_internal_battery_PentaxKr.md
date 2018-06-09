+++
# Date this page was created.
date = 2017-07-10

# Project title.
title = "Pentax Kr internal battery replacement"

# Project summary to display on homepage.
summary = "The internal battery of the Pentax Kr, which keeps time when the main battery is depleted or switched, is not conceived to last forever or to be easily changed. This article shows how to change it."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project/Change_internal_battery_PentaxKr/preview.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["personal", "electronic", "how-to"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/Change_internal_battery_PentaxKr_banner.jpg"
caption = "Pentax Kr"

+++

# Introduction
I use a Pentax Kr for 5 (or maybe 7) years now as my main camera, and it started to 'forget' the date every times I changed the main battery... So I needed to set the date and time very often to keep my photo correctly tagged. Which is a little annoying.. It took me a year before addressing the problem and to change the internal battery responsible for keeping time.

## More facts
Most camera have two internal batteries : one easy to switch and most of the time rechargeable which store the main power to use the camera. The other one, more or less accessible, stores internal parameters like the clock. On the Pentax Kr, the internal clock is kept by a dual-layer capacitor which act as a battery. This component is used only when the main battery is depleted or missing (when switching). The problem is, the capacitor life is about 500 hours, which seems a lot of time to switch the main battery ! But if the camera is stored with the main battery removed or depleted, it's dead in 20 days. It took 5 years before mine was dead and here is how to replace it if you don't want to change your camera or get annoyed.

![](/img/project/Change_internal_battery_PentaxKr/images/Dual_power_source.jpg)

# How to change the internal battery
## Prepare !
You need little material to do the repair, here the list :  
- I like to keep screws and parts tidy, so I used a firm paper to trace the camera contour and makes little hole were the screw are located on the camera to place theme during disassembly.  
- Precision screwdrivers  
- A basic soldering station (with tin)  
- The new battery  
- Your hands  

![](/img/project/Change_internal_battery_PentaxKr/images/Fig01.jpg)

## Unscrew 'almost' everything
[1] Unscrew the bottom part:
![](/img/project/Change_internal_battery_PentaxKr/images/Fig02.jpg)

[2] Unscrew the top part but don't take it off:
![](/img/project/Change_internal_battery_PentaxKr/images/Fig03.jpg)

[3] Unscrew the sides (2 screw hidden for each sides):
![](/img/img/project/Change_internal_battery_PentaxKr/images/Fig04.jpg)

[4] Now the delicate part : To remove the back part, the top part must be raised a little (not to much, there are soldered cables connecting those parts). The back part should resist a little, but go slowly and it will detach. Pay attention to the electric ribbon connected to the main part. It's connected from the bottom, so you can access it by raising the top part, it should comes off really easily:
![](/img/project/Change_internal_battery_PentaxKr/images/Fig05.jpg)

[5] Solder the new battery in place of the old one:
![](/img/project/Change_internal_battery_PentaxKr/images/Fig06.jpg)

[6] Reassemble in reverse order !

# Some sources
- [Pentax forum post](https://www.pentaxforums.com/forums/116-pentax-k-r/272934-internal-battery-dead-have-set-date.html)
- [Pentax forum post with component reference](https://www.pentaxforums.com/forums/58-troubleshooting-beginner-help/297948-clock-resets-battery-change.html)
- [Elna component](https://www.digikey.com/product-detail/en/DCK-3R3E204T614-E/604-1078-ND/1658299)
- [Aliexpress component used here](https://www.aliexpress.com/item/Farah-capacitance-3-3V-0-22F-DMS3R3224-super-capacitor-size-6-8-1-4mm/32683193185.html?traffic_analysisId=recommend_3035_null_null_null&scm=1007.13338.80878.000000000000000&pvid=e99791a1-3c14-40ee-b5c7-e13e0a1f3ca6&tpp=1)
- [Pentax K-X procedure to change the top wheel](http://www.wiratama.net/camera/pentax-k-x-scroll-wheel-repair)