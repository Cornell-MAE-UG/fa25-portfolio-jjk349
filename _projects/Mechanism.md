---
layout: project
title: Mechanism
description: Class project, Homework 12
technologies: [Art]
image: /assets/images/portfolio.jpg
---

I took on the challenge of designing a mechanism to lift a heavy weight as far as possible. The goal of this project was to design a mechanism with limited space and materials to lift the most amount of weight, the greatest distance: here are the constraints that governed my design:

1. The design must fit in a 2D area of 150cm long and 50cm tall.
2. The bar can have any fixed length as long as it fits in this area.
3. The mechanism must consist of 3 pin supports, 2 of which are mounted on the ground, and any linear actuator from a certain online catalogue.

This left me free to design the bar to any dimensions, material, and shape that I desired, and the specific placement of the pins, actuator, bar, and weight. 


 My design consists of a single straight bar pinned at the corner of the allowed design space, with the actuator pinned to the ground, with the push arm pinned to the other end of the bar. The weight is located at the exact middle of the bar, to be lifted up. This gives a good balance between height and weight that the actuator can lift using the bar as a lever arm.

Here is the design:

![Photo of design]({{"/assets/images/pic.png" | relative_url }}){: .inline-image-l}

I decided to use the actuator Tolomatic RSX because it has a high maximum force output of 294KN, and a stroke length of 1.5m. I paired this with a bar of 1.5m to just barely fit into my bounding area. I then used this to calculate the maximum weight and heights that my mechanism could lift as shown: 

![Photo of design]({{"/assets/images/pic2.jpg" | relative_url }}){: .inline-image-l}

![Photo of design]({{"/assets/images/pic3.jpg" | relative_url }}){: .inline-image-l}

The next part of this project was to consider the beam under bending and design the beam to have a sufficient cross section and material properties to withstand the bending load.

![Photo of design]({{"/assets/images/pic4.jpg" | relative_url }}){: .inline-image-l}

![Photo of design]({{"/assets/images/pic5.jpg" | relative_url }}){: .inline-image-l}

Using this, I chose to make a beam of Grade 12 Titanium Alloy (UNS R53400) with a square cross section of area 5.5225cm^2

![Photo of design]({{"/assets/images/pic6.jpg" | relative_url }}){: .inline-image-l}

Here is the final design of the beam:

![Photo of design]({{"/assets/images/pic7.jpg" | relative_url }}){: .inline-image-l}