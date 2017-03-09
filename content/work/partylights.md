Seeking to enhance my birthday party at home, I built a system to make the outdoor lights dance with the beat of the music. I started planning and iterating the design several months before the event. It was initially to use an arduino microprocessor to run the whole system, however the arduino was found to be too performance constrained for truly accurate beat extraction. The system then morphed to a PC doing the extraction and sending beat signals to the arduino, which would use its GPIO pins to run all the lighting patterns from there. I created custom drivers boards to control low voltage pool lights, a replacement control unit for a string of christmas lights, and simple relays for several other light sets as well. The system came together well in the end, as seen in the below video. Unfortunately it rained most of the evening so my guests couldn't properly appreciate it, but it added a memorable touch to a fun evening.


<iframe width="570" height="315" src="https://www.youtube.com/embed/qDzLDmJZyIg" frameborder="0" allowfullscreen></iframe>


<br>
Seen below is the arduino with the driving relays and power supply for the Christmas lights.

![arduino](img/work/partylights/21stelectronics.jpg)