+++
# Date this page was created.
date = 2017-06-28

# Project title.
title = "R studio server in a Raspberry"

# Project summary to display on homepage.
summary = "Using a Raspberry 3B to host R studio"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "/project/RStudio_server_raspi/Raspi.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["personal", "raspberry", "r", "server"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/Raspi_banner.jpg"
caption = ""

+++

Beside it's low cost, the [Raspberry Pi](https://www.raspberrypi.org/) is a linux card-sized computer quiet useful for a lot of projects. At first it was created mostly for educational purposes. Now it's heavily used in IoT, domotic and more recently in science, with a strong community and a lot of open ressources available.

the CPU/RAM limitations made it unstable to use under medium/heavy load. Until now it was difficult if not impossible to use it as a Shiny Server. But since the 3rd version, with a 1.2 Ghz quad-core 64 bits ARM CPU and 1 Gb RAM, using it for data analysis is not efficient, but possible and fun !