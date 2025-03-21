---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Securing IoT Communication Protocols at Scale"
summary: "Adding fine-grained dynamic access controls in large-scale, information-sensitive IoT and IIoT environments based on MQTT Protocols."
authors: [steve]
tags: [Privacy, Access Control, Policies, Internet of Things, Communication Protocols]
categories: []
share: false
date: 2024-06-15

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


The world of the connected “Internet of Things” is expanding to include more devices which observe our daily lives, routines, locations, and even our state of health. But have the underlying protocols by which they communicate this data kept pace with the need to protect our privacy and security?

In this project, we will investigate various “middleware” approaches to injecting dynamic access control agents into existing MQTT broker servers and measure their performance on real and/or simulated network environments as well as their resilience to security threats. 

We seek to strengthen the protocols underlying the communication between IoT devices, such as MQTT, to adjudicate who is authorized to access which information, where the access parameters may rapidly and frequently change, without impacting performance, based on the implications of the MQTT message topic hierarchical structure combined with geospacial security policy “zones” and techniques to simplfy and consolidate policy rules in real time.

