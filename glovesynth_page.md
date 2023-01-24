## THE VOLTFLUTE GLOVES (by Tien Nguyen and Patrick Martin)

**Project description:** This is a project that is focused on sound and movement. The gloves act like a controller making use of three interactions: touch, flex, and motion. For the touch aspect, we have a set of different resistors with different values, which then feed into an Arduino (we used [SparkFun RedBoard Plus](https://www.sparkfun.com/products/18158?gclid=CjwKCAiAoL6eBhA3EiwAXDom5o1pHBmLw4evZSg0s42MV4RDG1Incx7Id3NLVxjXL-zsDAnQutcWihoCsQsQAvD_BwE)), and then that serial data will go into [Pure Data](https://puredata.info/) our synthesis engine, which will assign a pitch for each data value. For the flex and motion aspect, the idea is pretty much the same, but the flex sensor will control the cutoff filter and the accelerometer, which has X and Y axis, will control vibrato and volume respectively. The values then feed into a different Arduino, but connect into the same computer. The VoltFlute Gloves    
<br>
Here is a poster summerized the project that my partner Patrick made for The 8th International Conference on Movement and Computing (MOCO'22) at Columbia College Chicago.
<img src="images/glovesynth.png"/>
<br><br>
### Demonstration


### References
