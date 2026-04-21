# DC-Motor-Modeling-and-Speed-Control-MATLAB-Simulink-

<p>
This project focuses on modeling a DC motor system and designing a closed-loop speed control system using MATLAB/Simulink. 
The objective is to analyze system dynamics and evaluate controller performance under different operating conditions.
</p>

<hr>

<h2> Project Objectives</h2>
<ul>
  <li>Develop a mathematical model of a DC motor</li>
  <li>Implement the model in MATLAB/Simulink</li>
  <li>Design a PID controller for speed regulation</li>
  <li>Analyze system response characteristics</li>
  <li>Evaluate system performance under disturbances and varying inputs</li>
</ul>

<hr>

<h2> System Modeling</h2>
<p>
The DC motor is modeled using electrical and mechanical equations, which are then converted into a transfer function representation.
</p>

<ul>
  <li>Electrical dynamics: armature voltage, resistance, inductance</li>
  <li>Mechanical dynamics: inertia, friction, torque</li>
  <li>Back EMF and torque constants included</li>
</ul>

<p>
The model is implemented in Simulink using standard blocks and transfer function representation.
</p>

<hr>

<h2> Control Strategy</h2>
<ul>
  <li>Closed-loop speed control system</li>
  <li>PID controller used for regulation</li>
  <li>Controller parameters tuned to improve system performance</li>
</ul>

<p>
The control system aims to track a given reference speed with minimal error and stable behavior.
</p>

<hr>

<h2> Performance Analysis</h2>
<p>The following performance metrics are analyzed:</p>

<ul>
  <li>Rise Time</li>
  <li>Settling Time</li>
  <li>Overshoot</li>
  <li>Steady-State Error</li>
</ul>

<p>
Different test scenarios are evaluated, including:
</p>

<ul>
  <li>Step response under nominal conditions</li>
  <li>Varying reference speeds</li>
  <li>Load disturbance effects</li>
</ul>

<hr>

<h2>Tools & Technologies</h2>
<ul>
  <li>MATLAB</li>
  <li>Simulink</li>
</ul>

<hr>

<h2> Project Structure</h2>
<ul>
  <li><b>/model</b> → Simulink model files (.slx)</li>
  <li><b>/scripts</b> → MATLAB scripts (if applicable)</li>
  <li><b>/results</b> → Simulation outputs and graphs</li>
  <li><b>/docs</b> → Project documentation</li>
</ul>

<hr>

<h2> Current Status</h2>
<p>
This project is currently under development. The modeling and control design phases are being actively implemented.
Results and analysis will be updated as the project progresses.
</p>

<hr>

<h2> Future Improvements</h2>
<ul>
  <li>State-space modeling approach</li>
  <li>Advanced control methods (LQR, MPC)</li>
  <li>Real-time implementation on embedded systems</li>
  <li>Integration with backend systems for data analysis</li>
</ul>

<hr>

<h2> Author</h2>
<p>
Yusuf Kocabıyık <br>
Control and Software Engineer
</p>
