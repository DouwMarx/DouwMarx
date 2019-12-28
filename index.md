{::options parse_block_html="true" /}

## On this page
{:.no_toc}

- TOC
{:toc}

# Hate to burst your bubble: This page is still under construction.
<img src="https://media.giphy.com/media/1SW3w3VEmsn1C/giphy.gif" width="1500"/>

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

Consider the mechanism below. 
- The plate initially highlighted is constrained to move in a plane without rotational degrees of freedom.
- The mechanism makes use of three linear actuators to achieve motion


![rotation](https://user-images.githubusercontent.com/58186739/71544233-22d51300-2985-11ea-8391-ce364d4c7a84.gif)


- In the first configuration, the plate initially highlighted is fixed in space (The translational degrees of freedom are removed). This could be achieved with the used of for instance a hydraulic brake. 
- The mechanism now has two rotational degrees of freedom and one translational degree of freedom.



The "brake" is now removed from the plate, and it regains its translational degrees of freedom.
- The brake is now applied to the universal joint in the center of the end effector.

![translation](https://user-images.githubusercontent.com/58186739/71544235-25d00380-2985-11ea-8e04-c77c050fa7a2.gif)

- The mechanism now has three translational degrees of freedom (x,y,z).

Ok, so what? Well, if we consider the brake to be a single actuator, a single actuator can be used to "gain" multiple degrees of freedom. Two rotational degrees can be exchanged for two rotational degrees of freedom with the requirement being only one (not two) additional actuator. Obviously, a choice between either rotational degrees of freedom or translational degrees of freedom is required and we are not actually achieving 5 degrees of freedom with 4 actuators seeing that all of the degrees of freedom cannot be utilized simultaneously. Come on, don't ruin a good story with facts.


<div class="panel panel-info">
**I guess at the end of the day you could argue that a sophisticated clutch mechanism can be used to drive an infinite amount of degrees of freedom with a single motor. **
{: .panel-heading}
<div class="panel-body">


----
# Reulaux Triangle planar motion concept

- Makes use of relative motion between centers of mass of circular and Reulaux triangle-shaped gears. 
- Inverse kinematics that include differential equations? Sounds good. 
----

# Natural Frequency Energy Storage

![MGHA](https://user-images.githubusercontent.com/58186739/71544604-523a4e80-298a-11ea-804f-14139f771c18.gif)

<img src="https://user-images.githubusercontent.com/58186739/70127181-3392b180-1683-11ea-9966-49df05058be4.gif" width="1500"/>

Unbalanced moment acts like spring mass system
![MGHB](https://user-images.githubusercontent.com/58186739/71544606-56666c00-298a-11ea-8ca5-180798b4428f.gif)

![Animated-mass-spring-faster](https://user-images.githubusercontent.com/58186739/70127575-f8dd4900-1683-11ea-9b96-1b9d4e7592f3.gif)

![Energy_plot](https://user-images.githubusercontent.com/58186739/69635130-670a8600-105c-11ea-8388-ba9778d2926c.png)

----








  
----
  <div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle; padding:40px 0;">
<a href="/donate">Text</a>
</div>

<div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle; padding:40px 0; margin-top:30px">
<a href="/blog">testtext</a>
</div>

NOTE DESCRIPTION

</div>
</div>
----

# Alternative energy for Feller bunchers


### Hey! Saw something that you find interesting or applicable to a problem you are working on? Please let me know!
