# WEEK 2 (4 September - 10 September, 2023)
![Picture](https://github.com/SCi-winner/SCI.github.io/blob/main/img/Team%20discussion.jpg?raw=true)
## Overview
  We divided up the work and explored the work in depth. We modelled the style of the initial platform and clarified the design direction of each part.

## Project Title
**Intelligent Marine buoyancy Platform System**

## Project Description
Over the past week, our group has been preliminarily conceptualizing the general model of the final design. 
We have been working on different ideas for the components of the model and have been further refining the 
structural features and general shape of the model with the help of our instructor.

1. Part of Fang, Zhenyu: I made the design of bionic water plant for the sea detection, my initial idea to 
design the plant with eight symmetrical leaves. Its stem is empty and has a nano-power generation structure 
inside. Based on the sea wind and wave undulation and nano power generation to achieve the effect of nano power 
generation. Currently there are a few parts of the design that need attention: one is how to waterproof the 
inside of the water plant structure in the sea, here we conceive the use of waterproof coating to solve the 
problem. There is also the poor ability of the bionic water plants to complete the exploration independently, 
so we plan it as an array to perform the task.


2. Part of Zhou, Jifeng: The project ontology is modeled initially and the location of each part is analyzed.
The idea was put forward to divide the project body into two parts, above the sea surface and below the sea 
surface, separated by a large floating platform in the middle. The part above the sea is equipped with two parts:
a PTZ camera and a retractable solar panel. The subsurface section consists of two parts: the friction nanogenerator,
which is closer to the surface, and the water pump that controls the snorkeling.


3. Part of the Zhang，Xinyue: I have a preliminary idea and design for the light storage rechargeable battery, 
I think we need solar panels, solar panels dedicated voltage regulator module, lithium batteries. If you want to 
add the function of automatic intelligent light chasing, you have to add a microcontroller (can use stm32c8t6 ), 
photoresistor, stepping motor, and 3.3v voltage conversion chip (can use rt6150b-33gqw).Ordinary buck regulator
module can also be achieved, to ensure that the power supply will not be lower than 5v can be.Function part can 
also add a display to show the current power, light intensity, temperature, sun angle and so on. If necessary,
you can also add buttons to control the menu and so on. You can also add a LED, light off and no lighton. You can
also add bluetooth or WiFi module, and develop an APP or oc program, so that the data uploaded in real time display.
The above functions are all part of the idea, currently there is a need for additional structure and then realise
the functions other than energy storage.

4. Part of Zhang, Jiaheng: I proposed two different options for the requirements of the snorkelling function of 
the platform in bad weather at sea. Option 1: The pressure tank is placed inside the carrier body and the leather
bag is in contact with seawater. When all the oil is in the pressure tank, the rubber bag is compressed, the
displacement is minimised and the positive buoyancy of the regulating system is minimised. As the oil is pumped
into the leather bag, the drainage of the system increases while the weight remains constant and the buoyancy 
increases. When all the oil is pumped from the pressure tank, the regulating system obtains the maximum positive
buoyancy. Option 2: The pressure tank is placed in the carrier body and the skin bag is in contact with seawater,
when all the oil is in the pressure tank, the gel bag is compressed, the drainage is minimum and the regulating
system has the minimum positive buoyancy. As the oil is pumped into the gel bag, the drainage of the system increases
while the weight remains constant and the buoyancy increases. When all the oil is pumped out of the pressure tank, 
the regulating system reaches maximum positive buoyancy.

5. Part of Gao, Sen: I mainly read the literature on the design of bionic jellyfish based on tensile monolithic
structure, and made a preliminary idea of the battery for storing power for the gimbal, as well as the shape of
the wiring of the platform and the surrounding facilities to cope with possible emergencies in the sea.
Literature address:[1] Zhang Ze. (2021). Design of Bionic Jellyfish Based on Tensioned Monolithic Structure 
(Master's thesis, Changchun University of Technology).
https://kns.cnki.net/KCMS/detail/detail.aspx?dbname=CMFD202102&filename=1021608657.nh

![Picture](https://github.com/SCi-winner/SCI.github.io/blob/main/img/Preliminary%20model%20of%20the%20head.png?raw=true)
