<h1>🚀 My Digital Clock in Logisim</h1>

<h2>📖 Introduction</h2>
<p>This repository contains the design and simulation of a Digital Clock using Logisim Evolution, a digital circuit simulation tool. The project demonstrates how digital components, such as counters, multiplexers, and clock signals, can be used to implement a functioning digital clock. The clock displays the time in hours, minutes, and seconds using a binary counter approach.</p>

<p>The project also includes various components, files, and resources necessary to view and understand how the circuit operates. It is ideal for students and hobbyists looking to explore digital logic circuits and learn about time-keeping in binary format.</p>

<p><strong>Check my post in LinkedIn to see the simulation of my clock:</strong> <strong><a href="https://www.linkedin.com/posts/mehedi-hasan86_designed-and-simulated-a-digital-clock-using-activity-7304647573372358656-Dfbq?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFUCP4kBC1AIuBA45X2iqOXn7lX5nu1yFDg" target="_blank">Digital Clock Simulation</a></strong></p>

<h2>📂 File Structure</h2>
<pre>
/My_Digital_Clock_in_Logisim
│── Screenshorts/                # Screenshots of the digital clock simulation
│── mehedi_2107086.circ          # Logisim file for the original clock design
│── new_Mehedi_2107086.circ      # Logisim file for the updated clock design
│── README.md                    # Project overview and instructions
</pre>

<h2>🛠 Included Files</h2>

<h3>1️⃣ mehedi_2107086.circ</h3>
<p>This is the original Logisim circuit file for the digital clock design. The circuit includes counters for seconds, minutes, and hours, as well as necessary components to control the flow of the clock.</p>

<p><strong>Key Features:</strong></p>
<ul>
  <li>Counter logic for tracking time in seconds, minutes, and hours.</li>
  <li>Multiplexers to select the appropriate value for display.</li>
  <li>Uses clock signals to update the values at regular intervals.</li>
</ul>

<h3>2️⃣ new_Mehedi_2107086.circ</h3>
<p>This is an updated version of the original mehedi_2107086.circ file, with improvements and enhancements. It may include optimizations in the circuit, additional features, or fixes that improve its performance or simulation accuracy.</p>

<p><strong>Key Features:</strong></p>
<ul>
  <li>Improved counter precision to handle overflows.</li>
  <li>More efficient logic for time increments.</li>
  <li>Better simulation performance with reduced complexity.</li>
</ul>

<h3>3️⃣ Screenshorts</h3>
<p>This folder contains screenshots of the Logisim project, showing the digital clock circuit design and simulation results. These images help to visualize how the circuit is constructed and how the simulation behaves.</p>

<p><strong>Key Features:</strong></p>
<ul>
  <li>Visual representation of the digital clock design.</li>
  <li>Simulation outputs that demonstrate how the clock increments time.</li>
  <li>Useful for understanding the flow of the circuit and how components interact.</li>
</ul>

<h3> 4️⃣ README.md </h3>
This file contains an overview of the project, the functionality of the digital clock, and instructions on how to open and run the circuit in **Logisim Evolution**. It also provides guidance on troubleshooting and future improvements.

<h2>🚀 How to Run the Digital Clock Circuit</h2>

<h3>🔹 Steps to Open in Logisim Evolution</h3>
<p><strong>1. Download and Install Logisim Evolution:</strong><br>
If you don’t already have Logisim Evolution installed, download it from the official website:<br>
<a href="https://logisim-evolution.org" target="_blank">Logisim Evolution</a></p>

<p><strong>2. Open Logisim Evolution:</strong><br>
Launch the Logisim Evolution software after installation.</p>

<p><strong>3. Load the Circuit Files:</strong><br>
Open the repository directory where you saved the files. Select the <strong>mehedi_2107086.circ</strong> or <strong>new_Mehedi_2107086.circ</strong> files to load them into Logisim Evolution.</p>

<p><strong>4. Start the Simulation:</strong><br>
Click on <strong>Simulate → Tick Once</strong> or press the <strong>F5</strong> key to run the simulation. The clock should start running and will display the time on the screen.</p>

<p><strong>5. Modify Inputs and Observe Outputs:</strong><br>
You can modify the simulation by adding switches for user input or using LEDs to display output. The digital clock will update based on the clock pulses.</p>

<hr>

<h3>🔍 Debugging & Common Issues</h3>

<h4>🔹 Floating Inputs (Red Wires)</h4>
<p>Ensure that all inputs, especially for logic gates, have a defined value. In Logisim, floating inputs are shown as red wires, indicating undefined or missing inputs.<br>
<strong>Solution:</strong> Use <strong>constants</strong> or <strong>input switches</strong> to provide defined values for inputs.</p>

<h4>🔹 Incorrect Outputs</h4>
<p>If the output doesn’t match the expected result, there may be an issue with the logic or connections in the circuit.<br>
<strong>Solution:</strong> Double-check the wiring, ensure proper clock signals are applied, and verify the truth tables for combinational logic.</p>

<h4>🔹 Clock Not Updating</h4>
<p>Sometimes, the clock signal may not be properly connected, or there may be an issue with how the clock is driving the counters.<br>
<strong>Solution:</strong> Make sure that the clock signal is connected to the appropriate components and that the circuit is receiving the correct pulses.</p>

<hr>

<h3>🛠 Future Improvements</h3>
<ul>
  <li>✅ Extend the counter circuits to support higher bit-widths for larger time representations.</li>
  <li>✅ Implement an alarm feature to trigger at a specific time.</li>
  <li>✅ Improve cache management for the digital clock design, such as adding a backup for time in case of power failure.</li>
</ul>

<hr>

<h3>📜 License</h3>
<p>This project is <strong>open-source</strong>. You are free to use, modify, and contribute to the project under the terms of the <strong>MIT License</strong>. Feel free to create forks, submit pull requests, or report issues.</p>

<hr>

<h3>💡 Conclusion</h3>
<p>This repository serves as an example of <strong>digital logic design</strong> using <strong>Logisim Evolution</strong>. The digital clock demonstrates basic concepts such as counters, multiplexers, and clock signal management, providing a simple yet effective way to learn about binary time-keeping and digital electronics. This project is helpful for anyone learning about digital circuits, computer architecture, or hobbyists interested in experimenting with Logisim Evolution.</p>
