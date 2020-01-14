{::options parse_block_html="true" /}

# Hate to burst your bubble: This page is still under construction.
<img src="https://media.giphy.com/media/1SW3w3VEmsn1C/giphy.gif" width="1500"/>

----
# On this page
{:.no_toc}
- TOC
{:toc}
----

----
*Please see the **Terminology** section for some lingo demystification*
----


# 3 Degree of freedom planar motion concept
This parallel mechanism has the following interesting attributes
- The mechanism has rotational inputs only
- The mechanism is capable of changing the position of the black dot (in-plane) on the end effector based om some combination of rotational inputs. Not only can the position of the black dot be specified (translation x,y), but the rotation as well. 
-The stationary actuators (rotational inputs) lead to parallel kinematic advantages
-This configuration will surely lead to some rather pesky kinematic singularities. However, note that in the animation, one of the three rotational inputs (red) is stationary with time. This member can be rotated a full 360 degrees, resulting in a large doughnut-shaped workspace. 

![PM](https://user-images.githubusercontent.com/58186739/71544220-f620fb80-2984-11ea-8113-d19be218dfeb.gif)


----
# Actuating two degrees of freedom with a single actuator. 

Ok, the heading above is a bit of a lie, but hear me out. 
Consider the rather elaborately colored mechanism below. 

![3DT2](https://user-images.githubusercontent.com/58186739/71546107-0db7ae80-299c-11ea-845d-daa9b6cd0157.gif)

Imagine a brake can be applied to any of the revolute joints in the mechanism, thereby constraining one of the degrees of freedom of the mechanism. 

In the mechanism pictured, a brake (perhaps a hydraulic brake) constrains the rotational degrees of freedom of the mechanism.  Consequently, when the linear actuators (green and blue) are extended and contracted, the end effector (black cylinder) translates in the x,y and z directions whilst the rotational orientation of the end effector remains fixed. 

When the brake is removed and reapplied to fix the blue and yellow plates, the mechanism is transformed to have two rotational degrees of freedom and a translational degree of freedom (z-direction).

![3DR2](https://user-images.githubusercontent.com/58186739/71546105-07c1cd80-299c-11ea-83cf-b6317062a366.gif)

Under the assumption that a single actuator can be used to achieve both of the above configurations (for instance a hydraulic cylinder that can move hydraulic fluid in both directions of flow), two degrees of freedom can be exchanged for another two. 

 So, two rotational degrees can be exchanged for two rotational degrees of freedom with the requirement being only one (not two) additional actuator. A choice between either rotational degrees of freedom or translational degrees of freedom is however required and therefore 5 degrees of freedom is not achieved using only 4 actuators. Come on man, don't ruin a good story with facts. 

But while we're at it, one could argue that using a sophisticated clutch mechanism, you could drive an infinite amount of degrees of freedom with a single motor. This mechanism just allows for more straight forward "clutch" integration. 

As a final little tangent: This type of friction-based mechanism can get particularly interesting when "brakes" are applied in a dynamic sense. By rapidly switching the braking configuration and relying on some inertial effects, multiple degree of freedom motion with an actuator deficiency might just be possible.


----
# Reulaux Triangle planar motion concept
Ok, so this one is certainly nothing short of optimistic. 
![MP5](https://user-images.githubusercontent.com/58186739/72324451-a72cd300-36b3-11ea-9591-f9a552116d27.png)
- Exploits the relative motion between centers of mass of circular and Reulaux triangle-shaped gears to rotate the blue gear. The (white) center of the Reulaux triangle slides in a slot in this blue gear. 
- At the end of the day the mechanism will still have only two degrees of freedom with only a remote possibility of applying the ideas mentioned in the **Actuating two degrees of freedom with a single actuator.** section.
- The one interesting thing to take away from this mechanism is that, when the actuators move at the same speed in opposite direction, it would lead to a rotation of the blue gear whilst the blue gear remains stationary. Isn't that already happening with the big red gear without the need for complex Reulaux Triangle shaped gears? Well, yes.
- Inverse kinematics dictated by the differential equation of a rolling Reulaux triangle? Sounds good. 


----
# Natural Frequency Energy Storage
Renewable energy is great. The success off wind and solar energy are however very reliant on our ability to store the energy we gather. There are many interesting ways to achieve energy, one of which is storing energy in gravitational potential energy (https://www.gravitricity.com/, https://heindl-energy.com/). Why not extend this concept to a dynamic energy storage method.

The mechanism is excited at its natural frequency to store energy. 

![MGHA](https://user-images.githubusercontent.com/58186739/71544604-523a4e80-298a-11ea-804f-14139f771c18.gif)


![MGHB](https://user-images.githubusercontent.com/58186739/71544606-56666c00-298a-11ea-8ca5-180798b4428f.gif)

Unbalanced moment acts like a spring-mass system

![Animated-mass-spring-faster](https://user-images.githubusercontent.com/58186739/70127575-f8dd4900-1683-11ea-9b96-1b9d4e7592f3.gif)

Considering that one of the largest cost limitations is having sufficient height to dangle the energy storage device from, a comparison of the energy capacity with usable elevation of the conventional gravity-based and this dynamic energy-based mechanism is shown below

![Energy_plot](https://user-images.githubusercontent.com/58186739/69635130-670a8600-105c-11ea-8388-ba9778d2926c.png)

The gravity-based mechanism scales linearly with height whilst the dynamic-energy based mechanism scales quadratically with height. 

This sounds great, but losses and maintenance are expected to be much higher in a dynamic system. Is it worth it? Perhaps. Perhaps not. 


----
# Feller buncher energy harvesting
Let's face it, cutting down trees is not quite the first thing that comes to mind when addressing the energy crisis. However, we have a lot of potential energy up there (you know, in the mass of living trees?). We cut down plenty of trees every day in plantations. Why not use the rotational moment of a falling tree to generate energy that would have been dissipated on impact with the ground? Could we for instance power a feller buncher saw with compressed air harvested from a falling tree?
<img src="https://user-images.githubusercontent.com/58186739/71547424-87559980-29a8-11ea-9015-156949d5c417.gif" width="1500"/>
(Blue Line Land Works, https://www.youtube.com/watch?v=AZO_QIgQ04A)


----
# Thinking about Pivot irrigation
## Parallel kinematic Pivot irrigation
<>![pivot_pic](https://user-images.githubusercontent.com/58186739/71547516-86713780-29a9-11ea-91de-614ec1cfe437.jpg)
<img src="https://user-images.githubusercontent.com/58186739/71547516-86713780-29a9-11ea-91de-614ec1cfe437.jpg" width="1500"/>
Somehow, when we pivot around a point, we tend to end up with, well, circles.
<>![Pivot_air](https://user-images.githubusercontent.com/58186739/71547515-85d8a100-29a9-11ea-96d8-694b54bb4d03.png)
<img src="https://user-images.githubusercontent.com/58186739/71547515-85d8a100-29a9-11ea-96d8-694b54bb4d03.png" width="1500"/>
Considering that we have only so much space for planting our crops, at what point does it start making sense to make use of more sophisticated irrigation techniques that are more space-efficient? 

----
# Terminology
- Degrees of Freedom (DOF) -https://en.wikipedia.org/wiki/Degrees_of_freedom_(mechanics)
- End effector - https://en.wikipedia.org/wiki/Robot_end_effector
- Pivot Irrigation - https://en.wikipedia.org/wiki/Center_pivot_irrigation
- Feller buncher  -  https://en.wikipedia.org/wiki/Feller_buncher

----
**Hey! Saw something that you find interesting or applicable to a problem you are working on? I'd like to hear from you!** *douwmarx@gmail.com*
