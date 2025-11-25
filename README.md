
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY
In optical fiber communication system, electrical signal is first converted into optical signal with the 
help of E / O conversion device as LED. After this optical signal is transmitted through optical fiber, it is 
retrieved in its original electrical form with the help O / E conversion device as photo detector. 
Different technologies employed in chip fabrication lead to significant variation in parameters for the 
various emitter diodes. All the emitters distinguish themselves in offering high output power coupled 
into the plastic fiber. Data sheets for LEDs usually specify electrical and optical characteristics, out of 
which are important peak wavelength of emission, conversion efficiency (usually specified in terms of 
power launched in optical fiber for specified forward current), optical rise and fall ties which put the 
limitation on operating frequency, maximum forward current through LED and typical forward voltage 
across LED. 
Photodetectors usually comes in variety of forms like photoconductive, photovoltaic, transistor type 
output and diode type output. Here also characteristics to be taken into account are response time of the 
detector which puts the limitation on the operating frequency, wavelength sensitivity and responsively. 
LED’s and LASER diodes are the commonly used sources in optical communication systems, whether 
the system transmits digital or analog signal. It is therefore, often necessary to use linear electrical to 
optical converter to allow its use in intensity modulation & high quality analog transmission systems. 
LED's have a linear optical output with relation to the forward current over a certain region of operation. 
Numerical aperture refers to the maximum angle at the light incident on the fiber end is totally internally 
reflected and is transmitted properly along the Fiber. The cone formed by the rotations of this angle along 
the axis of the Fiber is the cone of acceptance of the Fiber. The light ray should strike the fiber end within 
its cone of acceptance; else it is refracted out of the fiber core. 
  
  


## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM

![EXP 3 connection](https://github.com/user-attachments/assets/a2dc801b-7cb7-43a2-bdd7-ca4eb75edff4)


## 📊 TABULATION

![EXP 3 table](https://github.com/user-attachments/assets/18e94ce5-eff7-49ab-9532-427fe44aee9d)


## 📈 MODEL GRAPH

![EXP 3 MG](https://github.com/user-attachments/assets/8a9f8263-6933-493c-80c3-93e8f09b5377)
![EXP 3 graph](https://github.com/user-attachments/assets/b1f1ee1b-fccd-4e03-8bf0-e418f3e71652)


## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
