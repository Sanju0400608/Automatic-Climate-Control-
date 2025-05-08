🌡️ Automatic Climate Control System – Real-Time Embedded Project
This project demonstrates the implementation of an Automatic Climate Control System using dSPACE MicroAutoBox, ConfigurationDesk, and ControlDesk. The system regulates temperature in real-time by monitoring ambient conditions and controlling outputs based on a user-defined setpoint.

🧰 Tools & Hardware Used
MicroAutoBox II (DS1202)

ConfigurationDesk – For graphical model development and I/O configuration

ControlDesk – For real-time signal monitoring and setpoint tuning

Temperature Sensor – Wired to analog input

Actuator Output – Controlled via digital output (e.g., fan/heater)

⚙️ Project Workflow
Input Acquisition: Ambient temperature is measured using a temperature sensor connected to an analog input channel.

Control Logic:

Compares the current temperature with a desired setpoint.

Activates heater or fan output if the temperature deviates beyond a threshold.

Real-Time Monitoring:

ControlDesk is used to observe input/output signals and adjust setpoints live.

🔌 I/O Configuration Summary
Signal	Type	Channel Example
Temperature Input	Analog Input	AIN1
Setpoint	Variable	Tuned via ControlDesk
Heater Output	Digital Out	DOUT1
Fan Output	Digital Out	DOUT2

✅ Key Learning Outcomes
Real-time control implementation with MicroAutoBox

Sensor integration and signal conditioning

Embedded system modeling in ConfigurationDesk

Real-time validation and tuning in ControlDesk
