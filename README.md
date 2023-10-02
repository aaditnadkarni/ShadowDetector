# ShadowDetector


Components

LM741 IC	
LED	
LDR	
BC547 Transistor 	
1k Ohms Resistor	
10k Ohms Resistor	
100uF Capacitor	
Diode 1N4007	
10k POT	
Connecting Wires
Breadboard
9 V Battery	

INTRODUCTION
This project describes the development of a shadow alarm using IC 741, LDR and BC547 transistor. The shadow alarm is a type of light detector circuit that can be used to detect the presence of shadows and generate an alarm signal. The circuit uses an LDR (Light Dependent Resistor) to detect changes in the amount of light falling on it. When the light falling on the LDR decreases due to the presence of a shadow, the resistance of the LDR increases, causing the voltage at the base of the BC547 transistor to decrease. This triggers the IC 741 to generate an alarm signal, which can be used to alert the user of the presence of a shadow. The circuit is simple, low-cost, and easy to build, making it an ideal choice for applications that require a simple and reliable shadow detection system.

![image](https://github.com/aaditnadkarni/ShadowDetector/assets/96303113/f2c34fea-4e13-414c-9da6-105f4ad9f2a8)

WORKING
Op Amp IC UA 741 is used as a voltage comparator.
The LDR is used as a variable resistor that changes its resistance value in response to changes in the amount of light falling on it. One end of the LDR is connected to a fixed voltage source, while the other end is connected to the non-inverting input of the op-amp.
The inverting input of the op-amp is connected to a reference voltage that is set by a potentiometer. When the amount of light falling on the LDR changes, the voltage at the non-inverting input of the op-amp also changes. If the voltage at the non-inverting input is higher than the voltage at the inverting input, the output of the op-amp goes high. If the voltage at the non-inverting input is lower than the voltage at the inverting input, the output of the op-amp goes low.
The output of the op-amp is connected to the base of the BC547 transistor through a resistor. When the output of the op-amp goes high (shadow is passed), it turns on the transistor, which activates the buzzer and LED.

![image](https://github.com/aaditnadkarni/ShadowDetector/assets/96303113/c87afa89-f212-4fc4-9a13-db2a5eab0b79)
![image](https://github.com/aaditnadkarni/ShadowDetector/assets/96303113/af4edf96-27cc-4e0d-b70b-77d0b98338a9)



