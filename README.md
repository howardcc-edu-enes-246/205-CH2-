# CH2 Starting Computation

## Lecture 2 is about Kirchhoff

We start off with circuits that can be done with parallel and serial concepts faster than Kirchhoff, but do them using Kirchhoff anyway to practice for the bigger circuits.

The circuits starting off small and get bigger and bigger. Eventually we are solving circuits that can't be solved with parallel or serial or concepts found in Ch 6 of the text. Parallel and serial, cut sets work only in certain circumstances. They are not an excuse to not learn Kirchhoff's laws. 

We will be using Kirchhoff in every chapter, in every HW, on every Exam from now on. The majority of exam time will be doing Kirchhoff. You will not be able to use a calculator. You will be required to use sympy. You will not have access to the internet during the test. The test will be like the HW. Comes in a repo, is pushed up to GitHub in a repo after you are done and the internet is opened for you. 

## HW 2 

Includes problem statements and warning about showing your mistakes. If you received a 0 (after turning something in) on hw1, and you receive a 0 on hw 2 (after turning something in) , you will be written up as having violate academic integrity. 

# LAB 2

Create an *.ipynb file ... perhaps start by copying hw2.ipnyb or file>new>python in juypter. Call it Lab2.ipynb. Cut and paste parts of this document into different cells in the *.ipynb file you create. Do all your work in the Lab2.ipynb file.

## Part I

Your goal is to build a resistor circuit of your choice. It must have at least 5 resistors and can not be solved through parallel or series techniques. Find your instructor and show your work **after each step** of this workflow:

1. **Design**

   Choose 5 resistors whose values you have measured. Draw a circuit (with what ever drawing tools, even paper and camera), and put a screen shot of the circuit in this lab2.ipynb file. Record the values in this labs *ipynb file. Then solve like a HW problem with SymPy similar to the first 5 lecture examples. 

2. **Simulate** 

   Start with the  KiCad circuit you made in Lab 1. Add resistors to it. Build the circuit you designed. Collect data from the simulator. Describe the folder name containing the KiCad project in the *.ipynb file you are working in.

3. **Build**

   Physically build the circuit on a breadboard and hook up to the DC power supply in the cabinets in the room. There are two power on buttons. Learn to use them and configure the power. Ask for help if uncertain after trying to understand their operation by reading the manual. Manuals were given to you in the first lab. Record any notes to yourself you want to remember in the *.ipynb file you have been working in. 

4. **Take Data** 

   Take data from the circuit using the same symbols and order as in steps 1 and 2. Form a table showing differences between the numbers. Expect differences. Put this table in the *.ipynb file. Typora can help you start the table in this document and then you can cut and paste it this labs  *.ipynb markdown cell. 

5. **Analyze**

   Now compare the numbers, do some calculations and compare them in writing, in the *.ipynb. No need to use statistics. Answer these questions:

   1. What would you do differently (with the same equipment) to improve the lab?
   2. What would equipment would you use to improve results?
   3. What about these Lab instructions could be improved?

## Part II

The goal is to build begin building a simple RC circuit. Find your instructor and show your work after each of these steps.  As in all experiments, write everything down in the *.ipynb file. Don't put any data here. Don't answer any questions here.

1. **Design**

   Choose two RC pairs. One pair has a [time constant](https://en.wikipedia.org/wiki/RC_time_constant) that is human time .. with the goal of watching the voltage change on a multimeter. The other is a time constant that will require a function generator and oscilloscope to see in operation. 

   Record these values in this labs *.ipynb file. Record the expected time constants. Your goal is to create begin the SymPy solution of the RC circuit. You will not be able to solve it with SymPy until next week where we review Chapter 3. 

   So label the unknowns, find the equations. Write capacitors equation in differential form. There is a HW problem similar to this. 

2. **Simulate**

   The simulation has been done for you in a KiCad project DC charge simulation in this repo. Find it, get it working with one RC pair, then clone the project and get the simulation working with the second RC pair. Record the simulated time constants for each.

3. **Build**

   Build the slow RC circuit and show a voltage meter changing it's value when apply DC power to the circuit and turning the power and/or shorting the circuit. 

4. **Take Data**

   Measure the time constant of the slow RC circuit using a computer clock while looking at the voltmeter. We will repeat with the fast RC circuit next lab.

5. **Analyze**

   Make the normal table describing the three values: Design, Simulate and Build. Talk about their differences as in part 1. 

   **Answer these additional questions:**

   What voltage does the capacitor always charge up to?

   How is the voltage across the resistor different?

   Using the voltage across the resistor and the resistor's value we can compute what?

   What do the voltage across the capacitor and resistor always add up to?

   What do you have to do in between data collection runs to make sure the capacitor has exactly the same energy in it at the beginning of the measurement process?

   What is the difference if the RC are in series or parallel?

   The discharge and the charge of the capacitor ideally should have some kind of symmetry. Describe the symmetry and then describe what happens in reality. 

   Does this depend upon the voltmeter (fancy or handheld)?

   