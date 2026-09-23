# 8-Bit CPU Architecture Project (Work in Progress)

An independent personal project focused on understanding computer architecture from the ground up by designing and simulating custom digital logic circuits. 

## 🎯 Project Overview
The goal of this project is to design, simulate, and eventually integrate all the core subsystems of a functional 8-bit CPU. Rather than using pre-built components, I am building individual modules starting from fundamental logic gates to understand how processors actually execute instructions at the hardware level.

## 🛠️ Current Components Implemented
* **Fundamental Logic:** Half adders, full adders, and core logic gates (AND, OR, XOR).
* **8-Bit Sub-Circuits:** 
  * 8-bit Binary Adder
  * 8-bit Logic Units
  * 8-bit Tri-State Buffers for bus management
* **Status:** Individual components have been designed and tested inside a logic simulator environment, laying the foundation for an upcoming 8-bit ALU and full CPU assembly.

## 💻 Technical Stack & Environment
* **Simulation Software:** [Digital Logic Sim](https://sebastian.itch.io/digital-logic-sim) by Sebastian Lague.

## 📚 Acknowledgments & References
* Guided and heavily inspired by the educational computer engineering concepts and tutorials from [Fulxor Electronics](https://www.youtube.com/@FULXORELECTRONICS), which helped shape my understanding of data flow and component layout.

## 🚀 Future Development Roadmap
* **Phase 1:** Combine the adder, logic units, and tri-state buffers into a complete, testable 8-bit Arithmetic Logic Unit (ALU).
* **Phase 2:** Design internal registers and a Program Counter (PC).
* **Phase 3:** Implement a Control Unit and assemble the complete architecture into a working 8-bit CPU.
