ML with audio analysis
Introduction:

We used FFmpeg to trim audio recordings into smaller segments, each lasting one second, resulting in 2600 files. 
We used Python code to sort RMS values into ascending order.
After that we upload the RMS files to [Edge impulse](https://edgeimpulse.com/)
We divided 80% of the files for training purposes and allocated the remaining 20% for testing. 
These files were categorized into six groups.
Subsequently, we initiated the training process on either the processor or the graphics card.
Following the training phase, we conducted testing and achieved an accuracy rate of 90%, which is considered excellent for this application.
We then selected the development environment, opting for [Arduino IDE](https://www.arduino.cc/en/software), and integrated it into a library accessible to all.
Throughout this experiment, we utilized ESP-32 due to its capability to handle large datasets effectively.
<div id="header" align="center">
  <img src="[https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGc2MWM3aWxqemNrbXgwZmpzeHRndmRyNTJpa3B4dW0xMzQxeGQ3ciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/QsZol42CPIjMzke1QW/giphy.gif)" width="100"/>
</div>
