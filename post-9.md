---
layout: default
---
# Post 9: Designing an Automatic Traffic Light Controller Circuit

### Introduction to the Project
In our Digital Logic Design lab, we got a very exciting hands-on project. We had to design and build an Automatic Traffic Light Controller circuit. This project was a great way to take everything we learned on paper—like logic gates, flip-flops, and state diagrams—and use it to solve a real-world problem. It was very interesting to see how practical hardware animation actually works.

### Planning the System with Finite State Machines
Before touching any wires or chips, we had to do a lot of planning on paper. A traffic light system works step-by-step, which means it operates as a Finite State Machine (FSM). We had to define the exact stages for the traffic lights. For example, State 0 means Green light on the main road and Red light on the side street. State 1 means Yellow light on the main road and Red light on the side street. We drew a complete state transition diagram to show exactly how the system moves from one light to another based on a clock signal.

### Simplifying Logic Equations with K-Maps
After drawing the state diagram, we created a large truth table for all the inputs and outputs. To make the circuit, we needed to find the simplest mathematical formulas for our logic gates. We used Karnaugh Maps (K-Maps) to simplify these expressions. This step required a lot of focus because even a tiny mistake in the K-Map would give the wrong formula. If the formula is wrong, the traffic lights will skip states or show green lights in both directions at the same time, which is dangerous. Simplifying the equations helped us know exactly which chips to use.

### Building the Hardware Circuit
Once our formulas were ready, we started building the actual circuit on our test boards. We used standard logic gate Integrated Circuits (ICs) along with flip-flop chips to hold the memory of the current state. We also integrated a 555 timer IC to create a regular clock pulse. This clock pulse acts like a timer that tells the lights when to change at fixed intervals. Connecting all the wires carefully was tricky, but seeing the LEDs successfully blink through Green, Yellow, and Red in a perfect automatic loop was the best feeling!

#DLDProject #TrafficLightController #HardwareLab #FSM #[Dr. Bilal Ahmad](https://github.com/drbilalahmad)
