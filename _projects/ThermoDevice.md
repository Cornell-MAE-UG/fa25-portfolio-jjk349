---
layout: project
title: Thermodynamics Device
description: Analysis of a device using thermodynamics principles.
technologies: Google
image: /assets/images/turbo.jpg
---

Internal combustion engines are classic examples of useful thermodynamic devices that are extremely important for everyday life. They drive a primary mode of reliable transportation that humans have been reliant on in many parts of the world since their creation. Since engines are so important to us, we have invented ways to improve their power output without increasing their size or weight. One incredibly imporant way that this is achieved, primarily in ICE cars, is the Turbocharger.

![engine]({{"/assets/images/engine.jpg" | relative_url }}){: .inline-image-l}

Standard piston-cylinder combustion engines work (for my purposes) by mixing air with a small amount of fuel and igniting the mixture to drive pistons and produce rotational work. It would be trivial to inject more fuel into the engine to produce more work, but unfortunately this is very inefficient, and uses a lot of fuel for how much work is produced. As it turns out, there is an ideal ratio of air to fuel (about 14:1) in the mixture that both produces a lot of work and conserves fuel. Thus the difficulty in making more powerful engines is shoving more air into your engine at a time to match the amount of fuel that you can use at once. Rather than making a high-volume engine, a more weight efficient solution is to compress air into the air-fuel mixture, so that there is more fuel in the same volume, without making a lean air-fuel ratio.

Turbochargers achieve this by using exhaust gases released from combustion to spin a compressor which compresses intake air into the engine. The turbocharger consists of an intake through which gas released from the engine flows - still at high temperature and pressure - into turbine blades. This turbine is spun up by the high energy exhaust gases, which continue out of the turbocharger and eventually out of the car. The turbine is connected via a shaft to a centrifugal compressor. This type of compressor is useful for this purpose because they can produce a very high pressure resultant gas for their size, which is good for making the very dense air that is useful to the engine.The spin of the compressor sucks in air and moves it rapidly outward, compressing it. Since the compressor is mechanically connected to the turbine, the work required to make it spin is constantly supplied by turbine, and ultimately comes from waste gases.


![schematic]({{"/assets/images/schematic.png" | relative_url }}){: .inline-image-l}

## The System

![schematic]({{"/assets/images/system.jpg" | relative_url }}){: .inline-image-l}

Turbochargers operate at steady state as control volume systems. It is expected that a constant flow of air enters and leaves the device at any given moment, yet this amount can vary depending on engine operation. Driving faster will require the engine to spin faster, meaning faster combustion and more exhaust gas from the engine at that moment. Also, moving faster will force more air into the compressor side of the system at a given moment.

![schematic]({{"/assets/images/mass.jpg" | relative_url }}){: .inline-image-l}

Assuming the system is ideal and no work is lost, the power produced by the turbine equals the power used by the compressor, essentially converting enthalpy in the exhaust gases into enthalpy in the intake gases. Since enthalpy H = U + PV, we can see why the intake gases gain pressure and are compressed.


![schematic]({{"/assets/images/work.png" | relative_url }}){: .inline-image-l}

## Modification

One change to a turbocharger that can be incredibly beneficial to its function is by connecting its output to an intercooler rather than directly to the engine's intake. Standard turbochargers can be inefficient because they are powered by hot exhaust gases. Heat transfer from the exhaust gas to the turbocharger can cause the compressor itself to be hot and heat up the intake gas that it is trying to compress. Since the newly compressed gas is hot, it expands again before entering the engine, which makes the turbocharger much less valuable. Adding a heat exchanger to cool down the compressed air before sending it to the engine allows the gas to stay compressed and preserving the usefulness of the turbocharger. Because of this, attaching an intercooler to the turbocharger increases its performance.

References: 

