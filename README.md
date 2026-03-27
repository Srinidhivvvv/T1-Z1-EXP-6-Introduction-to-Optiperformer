
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Aim
To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Observation

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**
![6a](https://github.com/user-attachments/assets/3f0b3869-3ad2-455e-bb38-7345c4a4148a)


## Graphs
<img width="940" height="335" alt="6b" src="https://github.com/user-attachments/assets/5afd32b4-b736-4e42-a38f-15535c6d841d" />
<img width="940" height="326" alt="6c" src="https://github.com/user-attachments/assets/c2526188-f7f3-4b8c-920f-f8733da8ad90" />
<img width="1728" height="677" alt="6d" src="https://github.com/user-attachments/assets/a41fe0db-1755-4179-bd68-57c21b09204f" />
<img width="1723" height="600" alt="6e" src="https://github.com/user-attachments/assets/49fd5873-335c-45c7-ac64-e0a7f0d5a729" />
<img width="1734" height="601" alt="6f" src="https://github.com/user-attachments/assets/730ffcce-0823-45db-a1e3-7d8fbe542f42" />


## RESULT
Simulation of Optical Communication System is done compeleted successfully.
