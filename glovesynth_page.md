## THE VOLTFLUTE GLOVES (by Tien Nguyen and Patrick Martin)

**Project description:**
<br>
This project focuses on sound and movement, utilizing gloves as a controller that incorporates three types of interactions: touch, flex, and motion. 

For the touch interaction, we use a set of resistors with varying values connected to an Arduino (specifically the [SparkFun RedBoard Plus](https://www.sparkfun.com/products/18158?gclid=CjwKCAiAoL6eBhA3EiwAXDom5o1pHBmLw4evZSg0s42MV4RDG1Incx7Id3NLVxjXL-zsDAnQutcWihoCsQsQAvD_BwE)). The data collected from these resistors is sent serially to [Pure Data](https://puredata.info/), our synthesis engine, which assigns a pitch based on each data value.

In the case of the flex and motion interactions, the concept is similar. A flex sensor controls the cutoff filter, while an accelerometer, which has both X and Y axes, manages vibrato and volume, respectively. The values from these sensors are sent to a second Arduino, which is connected to the same computer.
<br><br>
The VoltFlute Gloves are an instrument that introduces a new way to create sounds and music using your hands.
<br><br>
This poster summarizes the project my partner Patrick created for The 8th International Conference on Movement and Computing (MOCO'22) at Columbia College Chicago.
<br><br>
<img src="images/glovesynth.png"/>
<br>
### Demonstration
Watch the demonstration video [here](https://drive.google.com/file/d/1ZpX3eQfKFP_I_iwalWMx1skBHGPlXGj2/view?usp=sharing). Performed by Patrick Martin.

---
### References
Mi.MU Gloves by MI.MU GLOVES LIMITED. [Link](https://mimugloves.com/documentation/mimu-gloves-overview/).
<br>
"The Quarterstaff, a Gestural Sensor Instrument" by Jan C. Schacher.
<br>
_A human connection_, performed by Palindrome. [Link](https://vimeo.com/112230953).
