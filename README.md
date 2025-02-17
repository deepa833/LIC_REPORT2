# LIC_REPORT2
#DESGIN 2
![Screenshot 2025-02-17 213008](https://github.com/user-attachments/assets/a181c5e9-6dbb-44de-8a61-e00c4e9de568)


*Aim:*  Determine the DC operating point, and measure the gain using transient and AC analyses.

*Components:* MOSFETs (M1 and M2), DC power supply.

*Procedure:*

1.  Assemble the circuit.
2.  Connect VDD to the gate terminals.
3.  Ground the source terminals.
4.  Determine Vin for saturation using a VTC curve and set VDD to 1.8V.

*Calculations:*

Target Id remains 5.56 * 10^-5 A.  MOSFET dimensions were adjusted accordingly.

*VTC Curve and Vin Selection:*

A DC sweep analysis was performed to obtain the VTC curve.



![VTC Curve](https://github.com/user-attachments/assets/abddb50e-8287-42ad-9dcc-fc4e29b37ff7)

Vin was chosen as 0.8V, within the saturation region.





*Analyses:* (Similar setup as Design 1)

*1) DC Analysis:*



![DC Analysis Results Design 2](https://github.com/user-attachments/assets/dded314a-ede4-45dd-aa51-d8a5251a6ec2)

*2) Transient Analysis:*



![Transient Response Design 2](https://github.com/user-attachments/assets/7d25b588-1dd1-406c-98cd-8fa4fc5c6163)

*3) AC Analysis:*


![AC Response Design 2](https://github.com/user-attachments/assets/e24ddc06-ca3f-41da-b214-6e012222aa04)

*Results (Design-2):*

1.  *DC Analysis:*  Target Id achieved. M1: L=500nm, W=950nm. M2: L=300nm, W=1020nm.
2.  *Transient Analysis:* Stable transient behavior observed.
3.  *AC Analysis:* Gain of 3.8 dB and ~180-degree phase shift.

*Inference (Design-2):*

1.  MOSFET dimensions effectively control Id.
2.  VTC curve facilitated appropriate Vin selection (0.8V).
3.  M2 width has a more significant impact on Id compared to M1.
4.  Design-2 performed as expected.

