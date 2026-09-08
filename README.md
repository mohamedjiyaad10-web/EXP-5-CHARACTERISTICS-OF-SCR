# EXP-5-CHARACTERISTICS-OF-SCR
1. AIM
To study and plot the V-I characteristics of a Silicon Controlled Rectifier (SCR), and to determine its forward breakover voltage and holding current.
2. APPARATUS REQUIRED
S. No.	Component	Specification	Quantity
1	SCR	2P4M	1
2	Resistor	1 kΩ	2
3	Regulated Power Supply	Dual (0–30 V)	1
4	Voltmeter	0–30 V	2
5	Ammeter	0–30 mA	2
6	Breadboard	—	1
7	Connecting wires	—	As required
3. THEORY
An SCR is a four-layer PNPN semiconductor device having three terminals: anode, cathode and gate. In the normal OFF state, the device restricts current. When the anode-to-cathode voltage exceeds a certain threshold (forward breakover voltage) or a suitable gate current is applied, the SCR turns ON and conducts current.
Once the SCR is turned ON, it remains in the ON state even after the gate current is removed, provided the anode current remains above the holding current. When the anode current falls below the holding current for an appropriate period, the SCR switches OFF. A positive gate current can therefore be used to trigger the device into conduction.
The SCR V-I characteristic consists of forward blocking, forward conduction and reverse blocking regions. In the forward blocking region, only a small leakage current flows. After triggering, the SCR enters the forward conduction region, where the current increases substantially while the voltage across the device is low. In reverse bias, only a small reverse leakage current flows until breakdown.
4. PIN DIAGRAM / SYMBOL
SCR terminals:  Anode (A)   |   Gate (G)   |   Cathode (K)
5. CIRCUIT CONNECTION

6. 
The main anode-cathode circuit consists of the regulated DC supply, a 1 kΩ series resistor, an ammeter and the SCR. A voltmeter is connected across the SCR to measure VAK. A separate regulated supply is connected through a 1 kΩ resistor to the gate, with a gate ammeter to measure IG.
 
Reference circuit diagram from the supplied lab record.
6. CHARACTERISTIC CURVE




Plot VAK (V) on the X-axis and IAK (mA) on the Y-axis. The curve indicates the forward blocking region, forward breakover point, forward conduction region, holding current and reverse blocking region.
 
Reference characteristic curve from the supplied lab record.
7. PROCEDURE
1. Make the connections as shown in the circuit diagram.
2. Set R1 and R2 to the mid-position and set the regulated supplies V1 and V2 to minimum.
3. Set the gate current IG to approximately 0.7 mA. Check that the forward breakover voltage is within the available supply range.
4. Slowly vary the anode supply VAK in suitable steps and note VAK and IAK at each step until the SCR conducts. Note the maximum VAK just before the SCR conducts; this is the forward breakover voltage.
5. Finding latching current: Ensure that the SCR is in the conducting state. Start reducing the anode voltage in steps while simultaneously switching OFF the gate supply. The corresponding anode current at the point at which the SCR ceases to remain latched is the latching current IL.
6. Finding holding current: Ensure that the SCR is conducting and switch OFF the gate supply permanently. Slowly reduce VAK and note IAK at each step. The anode current just before it drops to zero is the holding current IH.
7. Reverse the anode supply polarity and vary the reverse voltage in steps. Note the corresponding reverse current values.
8. Plot the forward and reverse characteristics using the tabulated values and determine the SCR forward resistance from the graph.
9. Repeat the procedure for another suitable gate current (for example, IG = 1.2 mA) and verify the characteristics.
8. OBSERVATION / TABULATION
Gate current, IG: 0.7 mA
VAK (V)	IAK (mA)
	
	
	
	
	
	
	
	
	
	
	
	
	
	
9. CALCULATIONS / GRAPH
Forward breakover voltage, VBO = 11.5 V (from the recorded observation).
Holding voltage, VH ≈ 0.72 V (from the recorded observation).
Holding current, IH ≈ 12.4 mA (as recorded in the supplied observation/result).
Forward resistance, RF = ΔVAK / ΔIAK, to be obtained from the slope of the appropriate portion of the plotted characteristic.
10. RESULT
The V-I characteristics of the SCR have been studied and plotted.
Forward breakover voltage, VBO = 11.5 V.
Holding voltage, VH = 0.72 V.
Holding current, IH = 12.4 mA.


<img width="1293" height="720" alt="Screenshot 2026-09-08 131900" src="https://github.com/user-attachments/assets/6a8892b2-671e-4c56-82a0-dce6ba2c25f6" />
