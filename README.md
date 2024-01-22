<h1>Differential Amplifier Design</h1>

 <!--### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)-->

<h2>Description</h2>
This project consists of the design of both ideal and nonideal amplifiers. The designs were created and tested using Cadence Virtuoso. The amplifier designs meet the specific requirements for VDD at 2.5V, differential voltage gain greater than 20dB, differential output swing Vpp greater than 2.5V, and total current less than 0.5mA. The amplifers went under DC and AC analysis via hand calculations, then were constructed as a schematic and used in a testbench circuit to run AC, DC, and transient simulation. Plots were obtained from each simulation to verify specification requirements were met.
<br />

<h2>Environments Used </h2>

- <b>Cadence Virtuoso</b><br/>

<h2>Project walk-through:</h2>

<p align="center">
 <br/>
<b>Ideal Differential Amplifier Circuit and Calculations:</b><br><br/>
<img src="https://i.imgur.com/V5MciNk.jpg" height="80%" width="80%" alt="Schematic and Calculations Page 1"/></p>
<img src="https://i.imgur.com/TOh16Mt.jpg" height="80%" width="80%" alt="Schematic and Calculations Page 2"/></p>
<p align="left">
An ideal differential amplifier circuit was drawn and hand calculations were implemented to obtain differential gain, DC output and input voltages, drain resistor values, small signal transconductance, overdrive voltage, total current, transistor width, common mode gain, and common mode rejection ratio for the amplifier.</p>
<br />
<br />
<br />
<p align="center">
<b>DC, AC, and Transient Simulations for Ideal Amplifier:</b><br><br/>
<img src="https://i.imgur.com/gXh6tM1.png" height="80%" width="80%" alt="Ideal DC Schematic"/></p>
<p align="left">
The ideal differential amplifier symbol was made and implemented in a testbench circuit with a resistive load. A DC simulation was run to confirm DC operating points and required specifications for the amplifier.</p>
<br />
<br />
<img src="https://i.imgur.com/wG2eMm9.png" height="80%" width="80%" alt="Bode Plot"/></p>
<img src="https://i.imgur.com/tYxyo7F.png" height="80%" width="80%" alt="AC Response Plot"/></p>
<img src="https://i.imgur.com/puPx6yj.png" height="80%" width="80%" alt="Transient Simulation Plot"/></p>
<p align="left">
An AC simulation was run to measure the differential gain, 3dB point, unity gain, and an AC response plot. A CMRR vs. frequency plot was obtained to measure the CMRR, common mode gain, and gain of the ideal amplifier to confirm that the required specifications were met.</p>
<br />
<br />
<img src="https://i.imgur.com/HFlo7kP.png" height="80%" width="80%" alt="Transient Simulation Plot"/></p>
<img src="https://i.imgur.com/4QESe9E.png" height="80%" width="80%" alt="Transient Response Plot"/></p>
<p align="left">
A transient analysis was run to obtain an input and output voltage transient plot and measure the Vpp, and to obtain a transient response plot to show input and output port voltages, as well as the DC current across time.</p>
<br />
<br />
<br />
<p align="center">
<b>Nonideal Differential Amplifier Circuit and Calculations:</b><br><br/>
<img src="https://i.imgur.com/M4ZGwxl.jpg" height="80%" width="80%" alt="Nonideal Schematic and Calculations Page 1"/></p>
<img src="https://i.imgur.com/aAttF5v.jpg" height="80%" width="80%" alt="Nonideal Schematic and Calculations Page 2"/></p>
<img src="https://i.imgur.com/vs5kXLk.jpg" height="80%" width="80%" alt="Nonideal Schematic and Calculations Page 3"/></p>
<img src="https://i.imgur.com/fm5ST43.jpg" height="80%" width="80%" alt="Nonideal Schematic and Calculations Page 4"/></p>
<p align="left">
A differential amplifier circuit with a nonideal current source was drawn and hand calculations were implemented to obtain differential gain, DC output and input voltages, drain resistor values, small signal transconductance, overdrive voltages, total current, reference current, transistor widths, common mode voltages, common mode gain, and common mode rejection ratio for the amplifier.</p>
<br />
<br />
<br />
<p align="center">
<b>DC, AC, and Transient Simulations for Ideal Amplifier:</b><br><br/>
<img src="https://i.imgur.com/btoK4KB.png" height="80%" width="80%" alt="Nonideal DC Schematic"/></p>
<p align="left">
The nonideal differential amplifier symbol was made and implemented in a testbench circuit with a resistive load. A DC simulation was run to confirm DC operating points and required specifications for the amplifier.</p>
<br />
<br />
<img src="https://i.imgur.com/GkvfRiV.png" height="80%" width="80%" alt="Nonideal Bode Plot"/></p>
<img src="https://i.imgur.com/3YNTuoQ.png" height="80%" width="80%" alt="Nonideal AC Response Plot"/></p>
<img src="https://i.imgur.com/SgK7f7J.png" height="80%" width="80%" alt="Nonideal Transient Simulation Plot"/></p>
<p align="left">
An AC simulation was run to measure the differential gain, 3dB point, unity gain, and an AC response plot. A CMRR vs. frequency plot was obtained to measure the CMRR, common mode gain, and gain of the ideal amplifier to confirm that the required specifications were met.</p>
<br />
<br />
<img src="https://i.imgur.com/7UNjUtV.png" height="80%" width="80%" alt="Nonideal Transient Simulation Plot"/></p>
<img src="https://i.imgur.com/dZGKBdP.png" height="80%" width="80%" alt="Nonideal Transient Response Plot"/></p>
<p align="left">
A transient analysis was run to obtain an input and output voltage transient plot and measure the Vpp, and to obtain a transient response plot to show input and output port voltages, as well as the DC current across time.</p>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
