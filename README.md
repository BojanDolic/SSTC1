# SSTC1
### This is a showcase of the solid state tesla coil project I'm working on.

___

### Table of contents

* [Story](#story)
* [Start of the project](#start)
* [Construction](#construction)

____

# Story

Ever since I visited the Nikola Tesla Museum in Belgrade in high school, and saw the tesla coil in person, I wanted to build my own version for myself. After all, it is pretty hard to make one and it is also a dangerous device.

I've always tinkered with electronics but never had a chance to build one until now. Although this one and the one in Belgrade differ quite a bit (besides the size :smile:), the principle of the operation is the same.

Unlike the one in the museum, this one uses semiconductors instead of the spark gap.

![Belgrade tesla coil](https://github.com/BojanDolic/SSTC1/blob/main/pictures/belgrade_coil/tc_belgrade.png)

#### (Tesla coil photographed in the Belgrade during my visit)

___

# Start

I started researching what would be most cost-effective way to build the tesla coil and I decided to build an SSTC.
### SSTC uses semiconductors instead of the spark gap to switch the primary coil. The most significant difference is the absence of resonant capacitors (primary capacitors). Because of this, the SSTC cannot generate huge voltages at the output; however, it is much cheaper to build.

My plan was to look at the builds other coilers made and try something similar. I went for the proven design of the Steve Ward with a few modifications regarding the logic board.

After that, I started to do calculations using an awesome tool called [JavaTC](http://www.classictesla.com/java/javatc/javatc.html).

My plan was to build a platform that houses all the electronics and above the platform would sit the secondary coil.
The secondary coil resonant frequency I was aiming for was ***300kHz max*** (preferably below that).

___
# Construction

