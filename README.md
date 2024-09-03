# Turing Machine and Universal Turing Machine Implementation

## Overview
This repository contains the implementation of a Turing Machine (TM) and a Universal Turing Machine (UTM), exploring fundamental concepts in the Theory of Computation. The task is focused on the following key aspects:

1. **Turing Machine (TM):** A theoretical model of computation that reads and writes symbols on an infinite tape according to a set of rules, transitioning between states until it reaches an accept or reject state.
2. **Universal Turing Machine (UTM):** A theoretical model capable of simulating any Turing Machine, given a description of that machine and an input string.

## Breakdown

### Part 1: Turing Machine (TM)
* **Components of TM:**
    * **Tape:** An infinite tape divided into cells, each capable of holding a symbol from a finite alphabet.
    * **Head:** A read/write pointer that moves left or right along the tape.
    * **State:** A finite set of states representing the machine's current configuration.
    * **Transition Function:** Determines the next state and the symbol to write based on the current state and the symbol being read from the tape.
* **Functionality:** The TM operates by reading symbols, writing new ones, moving the tape head, and transitioning between states until it reaches an accept or reject state.

* **Encoding:** The TM's states, tape symbols, directions, and transitions are encoded in binary and passed to the UTM for simulation.
  
### Part 2: Universal Turing Machine (UTM)
* **Components of UTM:**
    * **Input:** The description of a Turing Machine (TM) and an input string.
    * **Operation:** The UTM simulates the operation of the TM by processing the encoded description and input string, and executing the TM's transition rules.
* **Tape Structure:**
    * **Tape 1:** Encodes the description of the TM.
    * **Tape 2:** Holds the input string for the TM.
    * **Tape 3:** Displays the internal states of the TM as it processes the input.

### Implementation
* **Examples Folder:** Inside the `examples` folder, you will find two `.txt` files that serve as input data for the Turing Machine implementations in the Colab notebook. These files contain the transition tables for the TMs, demonstrating the TM and UTM functionalities.

## Requirements
- **Programming Language:** Python
- **Development Environment:** Google Colab

## Mentor
My sincere gratitude to **Dr. Soharab Hossain Shaikh** for his guidance and mentorship throughout the development of this task.

## Purpose
The purpose of this project is to demonstrate the principles of Turing Machines and Universal Turing Machines, providing a practical implementation of these theoretical concepts in the context of the Theory of Computation.

## Key Features
- Comprehensive implementation of a Turing Machine and a Universal Turing Machine.
- Demonstration of the encoding process for TMs to be simulated by a UTM.
- Example cases showcasing the TM's ability to recognize specific patterns in input strings.

## Explore the Code
Explore the codebase, which includes examples from the textbook *Theory of Computer Science* by KLP Mishra:
* **Turing Machine Code:** [Google Colab Link](https://colab.research.google.com/drive/1jbKiyeR0cxqs0HjMOF_dl4UECSJIbg4O?usp=sharing)

## References
- K. V. N Sunitha, N. K. (n.d.). *Formal Languages and Automata Theory*. Hyderabad: Pearson.
- K.K.P Mishra, N. C. (2008). *Theory of Computer Science: Automata, Languages, and Computation (Third Edition)*. New Delhi: Prentice Hall of India Private Limited.

## Contact
For inquiries, collaboration opportunities, or further information, please feel free to reach out to:

Email: nikhilgodavarthi9@gmail.com

Thank you for exploring this project and learning about the Turing Machine and Universal Turing Machine in the context of the Theory of Computation!
