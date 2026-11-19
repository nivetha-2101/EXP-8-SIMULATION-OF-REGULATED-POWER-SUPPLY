# EXP-8-SIMULATION-OF-REGULATED-POWER-SUPPLY
Aim
To design and simulate a complete AC to DC power supply using LTspice, consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode, voltage regulator and load, and to observe the output waveform at each stage. 
Software Required
LTspice
Components Required
•	AC source 
•	Transformer 
•	Diodes – 4 
•	Smoothing capacitor 
•	Zener diode 
•	Series resistor 
•	Load resistor 
________________________________________
Procedure
1.	Double-click on the LTspice icon and open a new schematic window. 
2.	Pick and place the required components from the library and draw the transformer circuit using AC source, L1L_1, L2L_2 and coupling. 
3.	Run the simulation and observe the transformer secondary output. 
4.	Pick and place four diodes and draw the bridge rectifier circuit. 
5.	Run the simulation to obtain the rectified waveform. 
6.	Place the smoothing capacitor across the rectifier output. 
7.	Run the simulation again to observe the filtered DC waveform. 
8.	Add the Zener diode regulator with a series resistor and connect the load resistor. 
9.	Right-click each component and set the required values. 
10.	Save the file with a suitable name. 
11.	Click Run → Advanced → Transient Analysis and set the stop time, for example 60 ms. 
12.	Click Run and place the probe at each stage to observe: 
•	Transformer output 
•	Rectifier output 
•	Filter output 
•	Regulated output 
•	Load voltage

CIRCUIT DIAGRAM:
<img width="1911" height="437" alt="Screenshot 2026-11-19 102519" src="https://github.com/user-attachments/assets/9dfc6ace-eb2d-485d-9b84-454bfd9c6aa7" />

AC INPUT WAVEFORM:
<img width="1902" height="565" alt="Screenshot 2026-11-19 102526" src="https://github.com/user-attachments/assets/12dff7df-3aff-4895-b956-ae08e3682b64" />

OUTPUT GRAPH:

SIGNAL OUTPUT WITHOUT FILTER:
<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/237afcc2-99cc-4568-a118-b293129928db" />

SIGNAL OUTPUT WITH FILTER:
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/7dc02843-c51c-41c9-a76f-daa5876e4793" />
<img width="1131" height="611" alt="Screenshot 2026-11-19 103454" src="https://github.com/user-attachments/assets/e55840c0-7694-4634-a594-a435e7297882" />


________________________________________

Result


Thus, the regulated power supply was simulated using LTspice. The output waveform at each stage was observed and analysed, and a stable regulated DC output was obtained at the load. 
