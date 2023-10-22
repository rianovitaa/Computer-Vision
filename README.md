# Computer-Vision
As of July 2023, both Apple and Samsung lead the smartphone industry worldwide, with a combined 52.61% of the total market share (ref1). As the main feature that must be present on today's smartphones, Apple and Samsung are competing to create camera technology so you can capture your best photo even in the low light condition.

* In September 2019, Apple introduced Deep Fusion technology (via the iPhone 11 series) to tackle the challenge. Its upgrade, named Photonic Engine, was introduced in September 2022 via the new iPhone 14 series (ref2).
* In February 2023, Samsung introduced Adaptive Tetra-squared Pixel Sensor technology with the Samsung S23 series as a counter-solution to a similar problem, promising excellent bright photo results from dark-toned images (ref3).
  
At its core, both technologies work by combining several adjacent pixels into a single pixel, using a Max Pooling operation. In this case, you are challenged to replicate the concept (brighten dark-toned photos), and then compare the result with another approach, i.e., Contrast Limited Adaptive Histogram Equation (CLAHE).
