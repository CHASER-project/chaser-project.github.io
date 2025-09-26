---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

### CHASER Workshop on Privacy in Wireless Communications
[Link](https://chaser-project.github.io/privacy-workshop) to the workshop's page.

---

Channel charting (CC) is an emerging application of self-supervised machine learning (ML) to wireless communication, which leverages the fact that wireless communications systems continuously collect data about the electromagnetic propagation channel. This data, known as channel state information (CSI), is high-dimensional and acquired at fast rates but typically discarded immediately after use. In contrast, CC recycles acquired CSI data by means of dimensionality reduction (DR) to learn a so-called channel chart. This channel chart is essentially a low-dimensional representation of the CSI with the salient property that users who are close in the channel chart are also close in physical space. Put simply: CC is a method that produces a pseudo-location information with no recourse to classical positioning methods, potentially opening up a range of location-based applications to operate with significantly reduced overhead.

### Typical Channel Charting Pipeline
![Typical Channel Charting Pipeline](/images/channel_charting_pipeline.png)

An infrastructure basestation (BS) or access point (AP) passively collects high-dimensional CSI (describing complex-valued frequency and time coefficients at possibly multiple antennas) from a large number transmitting user equipments (UEs) and/or UE locations. The BS or AP then extracts CSI features, which describe large-scale fading properties contained in the collected CSI. Finally, dimensionality reduction (DR)-techniques are applied to the CSI-feature database in order to learn a low-dimensional description, which is the **channel chart**. The channel chart has the key property that nearby points correspond to nearby locations in real space. For further resources on Channel Charting, we recommend visiting the dedicated [website](https://channelcharting.github.io).

### The Project
The objective of the CHASER Project is to develop new methods and algorithms allowing to implement network-wide CC and improve its predictive capabilities when applied to real-world use cases with heterogeneous users and dynamically changing environments. To achieve all of these goals, the CHASER Project will perform fundamental research on the algorithm and implementation levels, validate our solutions by gathering long-term CSI measurements in dynamically changing environments, and optimize channel-charting as a service for radio resource management.