#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
<img width="779" height="440" alt="image" src="https://github.com/user-attachments/assets/a14d8bc1-9dc7-4a49-98b0-f5320f450a63" />

MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



## DESIGN:

Inverting amplifier:
![WhatsApp Image 2026-03-27 at 6 57 55 PM](https://github.com/user-attachments/assets/067ad514-7b85-4ffd-98ff-5fd4aecd19b2)

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

<img width="787" height="296" alt="image" src="https://github.com/user-attachments/assets/ed43c615-750f-4bf9-b04a-bf9301ebd520" />

## CALCULATION
<img width="766" height="321" alt="image" src="https://github.com/user-attachments/assets/c3e115c6-97cc-4da1-88cd-ff8ab45e0072" />

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1226" height="1600" alt="image" src="https://github.com/user-attachments/assets/14646833-57df-401f-8387-3cca26392200" />

### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


<img width="704" height="397" alt="image" src="https://github.com/user-attachments/assets/1b4b170f-cf21-4fa9-9dc7-96db30b3c153" />

---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
## DESIGN
![WhatsApp Image 2026-03-27 at 6 59 33 PM](https://github.com/user-attachments/assets/6ebe6a26-87cc-4c97-8fdb-0780e42bb5cb)

## PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
<img width="815" height="322" alt="image" src="https://github.com/user-attachments/assets/69b2b50a-589f-4e2c-b5b8-7a4311cda4d8" />

## CALCULATION
<img width="886" height="256" alt="image" src="https://github.com/user-attachments/assets/f2f95f37-d2de-4dd8-89a0-6e217eaa7e72" />

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="653" height="840" alt="Screenshot 2026-03-27 184219" src="https://github.com/user-attachments/assets/b369bd92-38f3-4fe5-b05a-248860ed69ca" />


## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="706" height="522" alt="image" src="https://github.com/user-attachments/assets/917f2544-3735-4a23-a9b7-1264966d0d20" />

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN
![WhatsApp Image 2026-03-27 at 6 36 16 PM](https://github.com/user-attachments/assets/6014fc83-d68d-4ea0-b320-c3a8b9d949ce)


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---


## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)
<img width="501" height="240" alt="image" src="https://github.com/user-attachments/assets/fa4dba1f-7577-43bd-8f1a-372392f2eb0b" />

## CALCULATION
<img width="468" height="454" alt="image" src="https://github.com/user-attachments/assets/f97fd95f-6555-4234-a4c7-c91ca2f1cb11" />

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1206" height="1600" alt="image" src="https://github.com/user-attachments/assets/d47cc1a9-5aaa-4cae-b45a-a550e7a66212" />

## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1006" height="1087" alt="image" src="https://github.com/user-attachments/assets/636c08f9-7940-470e-a89e-4891d57a9ac7" />

PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
<img width="941" height="526" alt="image" src="https://github.com/user-attachments/assets/9263fecd-c02a-4b46-8584-8156e849f8b4" />

## CALCULATION
<img width="266" height="248" alt="image" src="https://github.com/user-attachments/assets/56e5a705-1b8c-4512-bda6-be081ae86d3a" />

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1188" height="1600" alt="image" src="https://github.com/user-attachments/assets/6b541b80-03c2-4990-a222-529f3d0ffe84" />


## RESULT
<img width="486" height="189" alt="image" src="https://github.com/user-attachments/assets/701b217d-6c45-4fee-87dd-5e304b13a6ca" />


