# EXP-3-.Experimental-Verification-of-Current-Voltage-IV-Characteristics-of-LED-and-LASER
## 🎯 AIM

To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

## 🧰 EQUIPMENTS REQUIRED

~~~
Power supply
Patch chords
1-meter fiber optic cable
Digital Multimeter (DMM)
~~~

## 📚 THEORY

LEDs and LASER diodes are commonly used sources in optical communication systems for both digital and analog transmission.
A linear electrical-to-optical converter is essential for intensity modulation and high-quality analog transmission.
LEDs exhibit a linear optical output with respect to forward current within a specific operating range.

## 🧪 PROCEDURE

~~~
Connect the power supply to the board.
Ensure all switched faults are in the ‘Off’ position.
Set emitter 1 block to Digital Mode.
Make the following connections:
Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
Connect the DMM between +12V supply and TP6 (LED cathode) to measure forward voltage (Vf).
Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.
Forward current (If) = DMM reading / 1000 (in mA)
Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
Record values of Vf and If, and plot the characteristic curve between them.
~~~

## 🔌 CONNECTION DIAGRAM
![WhatsApp Image 2025-11-16 at 14 56 02_03d29ee4](https://github.com/user-attachments/assets/3b2e00f6-0316-4619-8f33-3e92fcd68c21)


## 📊 TABULATION
LED Forward Characteristics
![WhatsApp Image 2025-11-16 at 14 56 07_8d00a0a9](https://github.com/user-attachments/assets/ccac32e3-2100-4d2a-b25d-0d92a787d3ec)

|Forward Voltage Vf (V)	|Forward Current If (mA)|
|-----------------------|-----------------------|
|         0             |          0            |
|        1.42           |         0.20          |
|        1.47           |         0.58          |
|        1.48           |         0.67          |
|        1.50           |         0.86          |
|        1.51           |         1.20          |

## 📈 MODEL GRAPH
(Insert graph of Vf vs If here)
![WhatsApp Image 2025-11-16 at 14 56 14_86f823a0](https://github.com/user-attachments/assets/355414b1-7a6a-4f9a-9304-28cf22cc401e)
![WhatsApp Image 2025-11-16 at 14 56 29_0292b416](https://github.com/user-attachments/assets/4927077a-c0a8-4856-9294-0279a170f02b)


## ✅ RESULT
The forward voltage and current characteristics of the fiber optic LED were successfully studied.
The photo detector response was observed and analyzed.
