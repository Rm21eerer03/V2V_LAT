# V2V_LAT
# PAPER ID - 10076

# TITLE: A Capacitor Coupled On-board Bi-directional Vehicle-to-Vehicle Charging System
# Authors: 
Mounika Reddimalla,
Research Scholar,
Department of Electrical Engineering,
National Institute of Technology, Warangal,
E-mail: rm21eerer03@student.nitw.ac.in .

Prof. Srinivasan Pradabane, IEEE member,
Assistant Professor,
Department of Electrical Engineering,
National Institute of Technology, Warangal,
E-mail: spradabane@nitw.ac.in .

# About Repository:
This repository contains the MATLAB files and latex documents used for our paper titled "A Capacitor Coupled On-board Bi-directional Vehicle-to-Vehicle Charging System".

# ABSTRACT: 
In recent times, Vehicle-to-Vehicle (V2V) chargers have gained popularity to transfer the energy between two Electric Vehicles (EVs). In this paper, a new direct V2V charger
is proposed that uses a capacitor coupling and an on-board DC-DC converter in each EV to enable the energy transfer betweenthem. Importantly, this charger differentiates itself from other
V2V chargers by eliminating the requirement for motor winding and inverter circuit from an EV. The charger operation is verified through simulation studies (via MATLAB/Simulink®) in three operating modes: Forward Boost, Reverse Buck and Forward buck-boost mode for EV’s with battery voltage of 350 V and 450
V. The simulation studies are validated through the OPAL-RT® Real-Time simulator. The proposed charger achieves an efficiency of 96.57 % in the forward boost mode, 96.56 % in the reverse
buck mode, and 96.26 % in the forward buck–boost mode of operation at a rated power level of 20 kW, while demonstrating a 25% to 76 % reduction in component count compared to existing topologies. Further, a laboratory proof of concept is
developed and tested with battery voltages of 12 V and 25.6 V in all modes of operation. Experimental results under static and dynamic discharge currents are presented.
# Description of Files:
The uploaded files include MATLAB scripts used to generate the analytical and simulation results presented in the manuscript. Block diagram files corresponding to the developed models are provided to illustrate the system architecture and control implementation. In addition, simulation output images, hardware images , and OPAL-RT files obtained during experimental validation are included. These materials were used for manuscript preparation and facilitate a clear understanding, reproducibility, and verification of the reported results.
# Software Requirements: 
1. MATLAB R2020b or later. 
# Simulation file Design Specifications: 
Simulation parameter Details : Battery-1 Capacity (Eb1) 40 kWh,
Battery-2 Capacity (Eb2) 100 kWh,
Battery-1 Nominal Voltage (Vb1) 350 V,
Battery-2 Nominal Voltage (Vb2) 450 V,
Switching Frequency (fsw) 20 kHz,
Filter Inductor (L1) 0.5 mH,
L1 Internal Resistance (R1) 0.005 Ω,
Filter Inductor (L2) 0.6 mH,
L2 Internal Resistance (R2) 0.006 Ω,
DC-link Capacitor (Ck) 1000 uF,
Battery internal parameters are also considered as functions of the state-of-charge (SOC) variation to analyze open-loop stability. Based on this analysis, a PI controller is designed, and the corresponding Bode plots are ploted to assess the closed-loop system stability.

# For Simulation Results Validation:
Open "MATLAB R2020b or later" version and Run.
The simulation and analysis results presented in the manuscript are obtained as follows:

1) The Simulink model is executed and the system responses are observed from Scopes 1 and 3. These recorded waveforms are used to generate Figs. 10, 11, and 12, corresponding to the converter operation in forward boost, reverse buck, and forward buck–boost modes, respectively.

2) The MATLAB script files are executed to perform the stability analysis of the system. From these scripts, the frequency-domain characteristics are obtained, and the resulting Bode plots are presented in Fig. 9.

3) Further OPAL-RT experimentation iscarried out using the Simulink model, and the responses captured from the relevant scopes are used to generate Figs. 21, 22, and 23, illustrating the dynamic performance of the proposed system under different operating conditions.
   
# Contact:
For questions or replication of results: 
rm21eerer03@student.nitw.ac.in ,
spradabane@nitw.ac.in .
