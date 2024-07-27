# Chapter 9: Simulation and Design

</br>

## Review Questions
True/False

    1. Computers can generate truly random numbers.
    2. The Python random function returns a pseudo-random int.
    3. Top-down design is also called stepwise refinement.
    4. In top-down design, the main algorithm is written in terms of functions that don't yet exist.
    5. The main function is at the top of a functional structure chart.
    6. A top-down design is best implemented from the top down.
    7. Unit-testing is the process of trying out a component of a larger program in isolation.
    8. A developer should use either top-down or spiral design, but not both.
    9. Reading design books alone will make you a great designer.
    10. A simplified version of a program is called a simulation.

</br>

## Multiple Choice
### 1. Which expression is true approximately 66% of the time?
    a) random() >= 66 b) random() < 66
    c) random() < 0.66 d) random() >= 0.66

### 2. Which of the following is not a step in pure top-down design?
    a) Repeat the process on smaller problems.
    b) Detail the algorithm in terms of its interfaces with smaller problems.
    c) Construct a simplified prototype of the system.
    d) Express the algorithm in terms of smaller problems.
    
### 3. A graphical view of the dependencies among components of a design is called a(n)
    a) flowchart b) prototype c) interface d) structure chart
    
### 4. The arrows in a module hierarchy chart depict
    a) information flow b) control flow
    c) sticky-note attachment d) one-way streets
    
### 5. In top-down design, the subcomponents of the design are
    a) objects b) loops c) functions d) programs
    
### 6. A simulation that uses probabilistic events is called
    a) Monte Carlo b) pseudo-random c) Monty Python d) chaotic
    
### 7. The initial version of a system used in spiral development is called a
    a) starter kit b) prototype c) mock-up d) beta-version
    
### 8. In the racquetball simulation, what data type is returned by the gameOver function?
    a) bool b) int c) string d) float
    
### 9. How is a percent sign indicated in a string-formatting template?
    a) % b) \% c) %% d) \%%
    
### 10. The easiest place in a system structure to start unit-testing is
    a) the top b) the bottom c) the middle d) the main function

</br>

## Discussion
### 1. Draw the top levels of a structure chart for a program having the following main function:
    def main():
        printIntro()
        length, width = getDimensions()
        amtNeeded = computeAmount(length,width)
        printReport(length, width, amtNeeded)

</br>

### 2. Write an expression using either random or randrange to calculate the following:
    a) A random int in the range 0-10
    b) A random float in the range -0.5-0.5
    c) A random number representing the roll of a six-sided die
    d) A random number representing the sum resulting from rolling two six-sided dice
    e) A random float in the range -10.0-10.0

</br>
    
### 3. In your own words, describe what factors might lead a designer to choose spiral development over a top-down approach.

</br>

## Programming Exercises
PAGE 326
