---
layout: post
title: "NASA Mentorship"
date: 2020-09-12
description: As a senior student in the engineering strand at the Governor's School for Science and Technology (GSST),  I am required to do a mentorship. My mentorship is with a NASA Aerospace Engineer where I use Open VSP to explore designs for aircraft.  # Add post description (optional)
img: OpenVSP.jpg # Add image post (optional)
tags: [NASA, ENGINEERING, CAD]
---

## OVERVIEW
NASA has adopted an open-source aircraft design platform called OpenVSP (Vehicle Sketch Pad). This software allows a user to quickly design, draft, and model configurations of different aircraft. In other words, this tool is basically CAD (Computer-Aided Design) specifically made for those in the aerospace industry. This software allows the geometry of an aircraft to be designed using parametrics; basing the model off of different features and constraints. The user is able to input the different components on an aircraft like the fuselage (main body of the plane) or wings and edit them in a highly visual and intuitive way. The different parts of the plane can then be modified through the definition of quantities like chord thickness, length, and aspect ratio. In addition to the efficiency, conceptual aircraft design enabled by OpenVSP, this program is also incredibly valuable as it translates the aircraft into models that can be run in engineering analysis programs to study things like the CFD, or computational fluid dynamics, of the aircraft (Lockney). 

Although OpenVSP is an extremely useful tool, it does not have a customizable engine component that can be added by a user. If someone wanted to incorporate an engineer into their model, they would have to do it manually by making a stack (a feature that can be made by individually defining cross-sections) or designing the feature in another way. This research project is focused on modeling and coding a customizable turbofan that can be added to the model with one click. A turbofan engine is basically a mixture between a jet engine and a propeller. This means that some of the air flows through the core of the engine while the rest of it flows through a fan portion outside of the core (Turbofan 2020). In a turbofan engine, the pressure created in the jet portion of the engine is used to rotate a crankshaft that, in turn, spins the fan and creates more thrust. The customizable turbofan engine allows for a faster and more accurate model to be made. This addition to the software will improve the efficiency of the design process as a whole, and also allow people to focus more time and energy on different aspects of design, maybe even allowing for a more fuel-efficient or more aerodynamic model to be made. 

Overall, any improvements that will cut out extra time in the VSP modeling process will be beneficial. In order to actually code and design a customizable turbofan component, a new VSP part will be made. VSP parts are coded individually, allowing the user to add different features such as the fuselage, wings, and hopefully engine, into the model. One of the biggest advantages of this feature is that it will give people the ability to focus on the critical aspects of the engine, while the code takes care of the rest in the background. The geometry section of the program, where the user can change the model, is divided into both a nacelle and engine tab. The nacelle (outer shell of the engine) tab allows the user to change features like the maximum diameter, length, and strength of the nacelle and inlet. Additionally, the engine portion contains sliders that adjust the area of the fan face, so that the bypass ratio (ratio of air that goes around the fan versus through the core) can be measured easily. The area of the core exhaust and fan exhaust in the back of the engine also work similarly to the fan face and can be adjusted using a slider. These features are all very beneficial, as in design, things like inlet strength ( the thickness of the front wall of the engine) have a very specific effect on the model and its aerodynamics. For example, there are certain values on the inlet that help optimize the airflow, making it essential for the customizable turbofan engine model to be easily iterated and tested. (Farokhi, 2020). Overall, this research project will have a huge effect on the efficiency and design of aircraft.

## DETAILS

## 9/28/20 - Introductory Work
Up until this point in time working was mainly spent on an introduction and basic information that will be involved in the project. This involved getting familiarized with open-source software called OpenVSP and reading excerpts from several papers involving aeronautical design and aerodynamics. OpenVSP is the tool that is used by many aerospace
engineers to design a framework for different planes and test how they would function with regard to things like lift and drag. The picture below is one of the planes that was made to practice using the software.





