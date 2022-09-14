---
layout: post
title:  "4 steps to build a wind power from your backyard: Do it Yourself"
author: sal
categories: [do it yourself]
image: assets/images/windvan1.webp
tag: [DIY]
tags: [featured]
---
## Backyard Wind Power

To begin our project, we will start by listing the marterials needed.

## <code>Materials needed for project</code>

1. Bicycle front wheel
2. PVC drain pipe
3. Machine screws, with nuts and large washers.
4. Steel water pipe, zinc galvanized, threaded both ends, 1½" diameter.
5. [Buck-boost voltage converter](https://www.electrical4u.com/buck-boost-converter/), DC–DC such as [Mesa #DSN6009 4A](https://www.aliexpress.com/item/32859038435.html).<br> I recommend 30W output capacity
6. [Electrolytic capacitors](https://eepower.com/capacitor-guide/types/electrolytic-capacitor/), 2200µF (2) 12V minimum.
7. [Full-bridge rectifier](https://www.electronics-tutorials.ws/diode/diode_6.html) 500mA minimum.
8. [Diode](https://www.electrical4u.com/diode-working-principle-and-types-of-diode/), 1N4007.
9. Electrical tape.
10. Wire cables and screw eyes (optional) to guy out a tall mast.
11. Concrete, 60lb bag (optional) to set the mast.
                                
## BUILD YOUR TURBINE USING THE BIKE WHEEL

First we begin by building our [rotor](https://www.watelectrical.com/what-is-a-rotor-types-working-applications/) and [generator](https://phys.libretexts.org/Bookshelves/Electricity_and_Magnetism/Book%3A_Electromagnetics_I_(Ellingson)/08%3A_Time-Varying_Fields/8.07%3A_The_Electric_Generator#:~:text=A%20generator%20is%20a%20device,of%20coils%20and%2For%20magnets.).<br> The rotor, that is the bicycle wheel is attached to a mast(steel water pipe) which acts as the stator.<br>The mast is placed firm on the ground using concrete mixed with cement. 

Depending on local conditions, you may also need to anchor your mast using wire cables.

### 1. Cut the turbine blades
<img style=" width:75%; height:350px" src="https://i1.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-IMG_5230.jpg?resize=683%2C1024&ssl=1" alt="img">

<b>Figure A.</b>

To make the [turbine](https://www.techtarget.com/whatis/definition/turbine#:~:text=A%20turbine%20is%20a%20machine,electromagnetic%20induction%20to%20produce%20electricity.) blades we use a PVC drain pipe.<br> Using a thin PVC pipe would be convenient.

<img style=" width:75%; height:350px" src="https://i0.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-IMG_5231.jpg?resize=683%2C1024&ssl=1">

<b>Figure B.</b>

In cutting use a  [jigsaw](https://en.m.wikipedia.org/wiki/Jigsaw_(tool)) or you simply use a [hacksaw](https://en.m.wikipedia.org/wiki/Hacksaw)
The PVC pipes should be cut into 8 parts.

### 2. Attach blades to generator

<img style=" width:75%; height:350px" src="https://i0.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-IMG_5232.jpg?resize=768%2C916&ssl=1">

<b>Figure C.</b>

For the generator we use a bicycle wheel(front wheel), attached to a dynamo hub.<br> An aluminium wheel is used for easy drilling.<br> Make sure the tire and inner tubes of wheel are removed.

<img style=" width:75%; height:350px" src="https://i2.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-IMG_5235.jpg?resize=768%2C480&ssl=1">

<b>Figure D.</b>

 Attach the turbine pipes to the wheel using two screws and nut.<br> Washers should be used to enable evenly distribution of load on the screws.<br>Try counting the spokes, and centers on the wheel.

### 3. Make the mast
<img src="https://i0.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-IMG_5360.jpg?resize=768%2C480&ssl=1">
<b>Figure E.</b>

Make the mast from zinc-plated steel water pipe threaded at both ends <b>(Figure E)</b>.<br> Drill a 9mm hole into the end cap and tighten your hub nut onto the bike wheel’s<br> axle to attach the wheel to the cap (Figure F below). Once the mast has been<br> mounted securely in the ground (!), you can screw the cap onto the mast.

<img class="windpower2" src="https://i1.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-IMG_5369.jpg?resize=768%2C480&ssl=1">
<b>Figure F.</b>

For erecting the mast, the thread at the other end may come in handy. You can thread a matching tee piece onto it, and encase the tee in the concrete block that you’ll pour in the ground. <br>The concrete should be sufficiently heavy to both support and anchor the turbine, and must be fixed firmly in the ground.<br> Then, whenever a storm comes up, you can simply unscrew the mast from the concrete block and take the turbine somewhere safe.
<br>Don’t make the mistake of underestimating the forces created by winds.<br> They grow proportionally to the cube (third power) of the wind speed! If necessary, guy out the mast with wire cables.

### 4. Assemble the electronics

<img style="height:450px; width:100%" src="https://i1.wp.com/makezine.com/wp-content/uploads/2020/11/Wind-Turbine-Diagram.png?resize=733%2C1024&ssl=1">
<b>Figure G.</b>

Our device is set up for charging a [lead-acid battery](https://byjus.com/chemistry/lead-acid-battery/) using the current generated by the [dynamo](https://edisontechcenter.org/generators.html) <b>(Figure G)</b>. [The hub dynamo](https://en.wikipedia.org/wiki/Hub_dynamo) produces alternating current, which we’ll convert to pulsating direct current using a [full-bridge rectifier](https://www.electronics-tutorials.ws/diode/diode_6.html). To smooth it out, the pulsating DC is fed into the two 2200µF (microfarad) electrolytic capacitors.<br>
The smoothed DC is then passed to a buck-boost converter (about $14.48 on [eBay](https://www.ebay.com/b/Buck-Boost-Converter/117000/bn_7023302773)) which we’ll
use as a [charging regulator](https://www.sciencedirect.com/topics/engineering/charge-controller#:~:text=A%20wind%2Delectric%20charge%20controller,a%20dump%20(diversion)%20load.). This will convert any input voltage from 1.25V to 30V into an adjustable, constant output voltage. We’ll set the converter’s output to be 0.7 volts above the
end charging voltage of our battery (compensating for the diode’s forward voltage).<br> The 1N4007 diode is required to prevent current flowing back from the battery to the converter.<br>For example, a 6-volt lead-acid battery has a charging voltage of 7.2 volts. Adding the diode’s forward voltage of 0.7V, the converter should be set to an output voltage of 7.9V. Your electrical load (whatever’s going to consume the power, an LED lamp, for instance) will be connected to the battery’s output.<br> Be aware that the load must be able to handle the output voltage set for the converter. While the generator itself may only be able to provide a small amount of current, the battery may output several amps.<br> In case of a short circuit, the consequences may be dire (fire hazard). To prevent accidents, you’ll need to safeguard accordingly whatever circuit you’re connecting to the battery.
