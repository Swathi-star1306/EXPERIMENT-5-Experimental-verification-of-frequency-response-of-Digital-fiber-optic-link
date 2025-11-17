
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---


## BLOCK DIAGRAM

<img width="504" height="208" alt="image" src="https://github.com/user-attachments/assets/3eba8b40-f4b1-4bd8-8b56-dfbc18711566" />

---

## CONNECTION DIAGRAM  
**Setting up a Digital Link**

<img width="515" height="127" alt="image" src="https://github.com/user-attachments/assets/5e18d568-7cf6-4d26-a2e6-3fca9f74c8d1" />


---

## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-17 at 20 15 34_2c967fb6](https://github.com/user-attachments/assets/5d9120b4-bdb1-431f-ad7f-4251a80693bd)

---

## MODEL GRAPH

<img width="599" height="322" alt="image" src="https://github.com/user-attachments/assets/1315dcd7-7a5b-49a4-8d9f-c2b4ceec2feb" />

---

## RESULT

The digital 660 nm fiber optic link accurately reproduced the input square wave at the receiver, confirming proper digital signal transmission and bandwidth response.
