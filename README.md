# SatPipe Demo

A anonymous demo for *INFOCOM 2025* submission: *SatPipe: Deterministic TCP Adaptation for Highly Dynamic LEO Satellite Networks*

### Rebuffering Comparison between BBR and SatPipe

In order to visualize SatPipe's effect on reducing the freezing frame during video transmission, we compare the stall rate of a fixed bitrate video over a period of time.

![Image: Rebuffering_Explanation.jpg](https://github.com/SatPipe/SatPipe_Demo/blob/main/Rebuffering_Explanation.jpg)

The left side of the image represents the results of the BBR, and the right side of the image shows the results of SatPipe. A buffer level of 0 means the video is stalled. We can tell that SatPipe reduces rebuffering time down to 2 seconds, 15 seconds less than BBR in a 2-minute video. The video recording time is close to ensure that the backbone network does not fluctuate much.



The full video is available [here](https://github.com/SatPipe/SatPipe_Demo/blob/main/Anonymous_SatPipe_Demo.mp4)
