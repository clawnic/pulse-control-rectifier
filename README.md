# Pulse-Controlled-Rectifier

<h3>Objective</h3>   
simulation and analysis of AC to DC using pulse controlled rectifier

<h3>Introduction</h3>
This project explores the simulation of a pulse-controlled rectifier using MATLAB 
Simulink. Pulse-controlled rectifiers are essential in converting AC to DC and regulating 
output characteristics. The project aims to model the system, understand control strategies, 
and analyze its behavior and performance. Through Simulink, we'll visualize the rectification 
process, observe the impact of control, and appreciate the significance of pulse-controlled 
rectification in power electronics.


<h3>Explaination</h3>
A pulse-controlled rectifier, also known as a thyristor rectifier or controlled rectifier, is an 
electronic circuit used for converting alternating current (AC) into direct current (DC). It 
operates by controlling the firing angle of thyristors or other power semiconductor devices. 
Here's an exploration of the pulse-controlled rectifier:
Components:<br>

- AC Source: The input of the pulse-controlled rectifier is typically an AC voltage source, 
which provides the alternating current to be rectified.<br>

- Thyristors (SCRs): Thyristors, or Silicon-Controlled Rectifiers (SCRs), are solid-state 
semiconductor devices used as switches in the rectifier circuit. Thyristors allow current to 
flow only when triggered and remain conducting until the current falls below a certain 
threshold.<br>

- Diodes: In addition to thyristors, diodes are often used in the rectifier circuit to ensure the 
flow of current in one direction, thus converting AC to pulsating DC.<br>

- Load: The load represents the component or system that the rectified DC output is 
powering, such as motors, lights, or electronic devices.<br>

- Control Circuit: The control circuit generates the trigger pulses for the thyristors to control 
the timing and angle at which they conduct. This control determines how much of the AC 
waveform is rectified, affecting the output voltage and current characteristics.<br>

<h3>Working Principles</h3>

<ol>
  <li>
    <b>Firing Angle</b><br>The firing angle is a crucial parameter in pulse-controlled rectifiers. It 
determines when the thyristors are triggered to conduct in each AC half-cycle. By controlling 
the firing angle, you can regulate the output voltage and current.  
  </li>

  <li>
    <b>Half-Wave and Full-Wave Rectification</b><br>  : Depending on the configuration, pulse-controlled 
rectifiers can perform half-wave or full-wave rectification. Half-wave rectifiers use only one 
thyristor (or diode), while full-wave rectifiers use two thyristors (or diodes) to rectify both 
halves of the AC waveform.
  </li>

  <li>
    <b>Control Strategy</b><br> The control strategy involves triggering the thyristors at specific angles 
of the AC waveform to control the output voltage. Common strategies include phase control 
and on-off control.
  </li>

  <li>
    <b>Output Characteristics</b><br>Pulse-controlled rectifiers produce a pulsating DC output. The 
average DC voltage depends on the firing angle, and the ripple voltage is determined by the 
rectification method used.
  </li>

  <li>
    <b>Applications</b><br>
    - Pulse-controlled rectifiers are used in power supplies for various electronic devices and 
industrial equipment.<br>
- They are employed in motor drives for precise control of motor speed and torque.<br>
- Inverter systems for renewable energy sources, such as wind and solar, use pulse-controlled rectifiers to convert generated AC power to usable DC power.<br>
- Uninterruptible Power Supplies (UPS) often use pulse-controlled rectifiers to ensure a 
stable and clean DC power supply during power outages.<br>

  </li>
</ol>

<h3>Different types of Rectifier Based on Pulse variation :</h3>
<ul>
  <li>
    <b>12 pulse controlled rectifier</b><br><br>A 12-pulse control rectifier is a type of rectifier system that utilizes twelve diodes to 
convert alternating current (AC) into direct current (DC). It is commonly used in highpower applications, such as industrial motor drives, power supplies, and various 
other electrical systems requiring stable and efficient DC power conversion.<br><br>
    The advantages of a 12-pulse control rectifier include reduced harmonic distortion, 
improved power quality, and enhanced efficiency. By minimizing harmonics, it helps 
comply with stringent power quality standards and regulations. However, it is more 
complex and costly compared to standard rectifiers due to the need for specialized 
transformers and additional components. Nonetheless, the benefits often justify the 
use of a 12-pulse control rectifier in applications where high power quality and 
efficiency are critical
  </li>
  <li>
    <b>18 pulse controlled rectifiers</b><br><br>An 18-pulse control rectifier is a sophisticated type of power converter used to 
convert AC to DC with reduced harmonic distortion. It achieves this by using three 
sets of six-pulse rectifiers, each connected to transformers with specific phase shifts. 
These phase shifts help cancel out specific harmonics, leading to a significant 
reduction in total harmonic distortion in the input current waveform. This type of 
rectifier is commonly employed in industrial systems where the presence of 
harmonics can cause issues such as overheating and additional losses.<br><br>
    An 18-pulse control rectifier is a sophisticated type of power converter used to 
convert AC to DC with reduced harmonic distortion. It achieves this by using three sets of 
six-pulse rectifiers, each connected to transformers with specific phase shifts. These phase 
shifts help cancel out specific harmonics, leading to a significant reduction in total harmonic 
distortion in the input current waveform. This type of rectifier is commonly employed in 
industrial systems where the presence of harmonics can cause issues such as overheating 
and additional losses.
  </li>
  <li>
    <b>24 pulse controlled rectifier</b><br><br>The 24-pulse converter is a type of multipulse rectifier system used in power electronics to 
minimize harmonic distortions in the output waveform. It comprises four parallel-connected 
six-pulse rectifier bridges, each with a phase shift introduced by specific transformers. This 
configuration significantly reduces total harmonic distortion (THD) and improves the power 
quality of the converted DC output. The 24-pulse converter finds application in environments 
where stringent power quality standards must be met, such as precision manufacturing 
processes and research laboratories. Control strategies involving the adjustment of thyristor 
firing angles are employed to achieve the desired phase relationships, ensuring cleaner and 
more stable DC power generation.
  </li>
</ul>


