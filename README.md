Download Link: https://assignmentchef.com/product/solved-mtrn4230-assignment-1
<br>
<em> </em>

<ol>

 <li><em>Read and understand safety documents for operating robots </em></li>

 <li><em>Online training with UR5e </em></li>

 <li><em>Offline configuration of UR5e by use of virtual machine </em></li>

</ol>

<h1><em>GETTING STARTED </em></h1>

<ol>

 <li><em>Download attached documents and files </em></li>

 <li><em>Create account in universal robotics </em></li>

 <li>Install virtual box</li>

 <li>Import virtual image given for UR5e</li>

</ol>

Note (xx) is used to show you how much point you receive answering that question. For example if it’s (0.5) it means 0.5 percent you receive.

<h1>ACTIVITIES</h1>

<h2>1. SAFETY QA</h2>

Read the following document and answer to the below

<ul>

 <li><strong>UR5e User Manual:</strong> <a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">https://s3</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">–</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">eu</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">–</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">west</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">–</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">amazonaws.com/ur</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">–</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">support</a><a href="https://s3-eu-west-1.amazonaws.com/ur-support-site/50557/UR5e_User_Manual_en_Global.pdf">site/50557/UR5e_User_Manual_en_Global.pdf</a></li>

</ul>

Questions

<ol>

 <li>Explain the steps in “Pre-Use Assessment”? (0.5)</li>

 <li>Shortlist integrator role in this document? (0.5)</li>

 <li>Summary modes in the robot? (0.5)</li>

</ol>

<ul>

 <li>Read ENG-MECH-RMF-15979 and ENG-MECH-SWP-8948 <a href="https://safesys.unsw.edu.au/hs/Lists/healthsafetyforms/DispForm.aspx?ID=16091">https://safesys.unsw.edu.au/hs/Lists/healthsafetyforms/DispForm.aspx?ID=16091</a><a href="https://safesys.unsw.edu.au/hs/Lists/healthsafetyforms/DispForm.aspx?ID=16091">,</a> <a href="https://safesys.unsw.edu.au/hs/Lists/healthsafetyforms/DispForm.aspx?ID=16090">https://safesys.unsw.edu.au/hs/Lists/healthsafetyforms/DispForm.aspx?ID=16090</a> Explain Start Up and Operation(0.5)

  <ol>

   <li>Explain Hazard/Task “Robot tool causing damage to user or equipment” (0.5)</li>

   <li>Explain Shutting Down(0.5)</li>

  </ol></li>

</ul>

<h2>2. ONLINE UR5 TRAINING</h2>

<ol>

 <li>Follow the below steps and upload the certificate as a part of deliverables for this assignment</li>

</ol>

<table width="505">

 <tbody>

  <tr>

   <td width="505">Got to https://www.universal-robots.com/academy/</td>

  </tr>

  <tr>

   <td width="505"></td>

  </tr>

  <tr>

   <td width="505"> </td>

  </tr>

  <tr>

   <td width="505"></td>

  </tr>

 </tbody>

</table>

<table width="505">

 <tbody>

  <tr>

   <td width="505"></td>

  </tr>

  <tr>

   <td width="505">Upload the certificate you received</td>

  </tr>

 </tbody>

</table>




<h2>3. OFFLINE UR5 PRGRAMMING</h2>

<table width="601">

 <tbody>

  <tr>

   <td width="601">Install virtual box</td>

  </tr>

  <tr>

   <td width="601">Import URSim_VIRTUAL-5.7.0.90932</td>

  </tr>

  <tr>

   <td width="601">Take snapshot of the setup you do on your robot and attach it to your report.</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>How much is maximum “Active Payload” for UR5? Set it to 15. (0.52)</li>

 <li>Set

  <ol start="5">

   <li>the tool Position to X = 5.1cm, Y= 6.2cm,Z = 0.9cm (0.25)</li>

   <li>the tool orientation to RX = 42, RY 32, Rz 30 (0.25)</li>

   <li>Centre of gravity to X = 50mm, Y=60mm, Z = 70mm (0.25)</li>

  </ol></li>

 <li>Add two digital inputs and name them in1 and in2. Connect in1 to Auto-init and in2 to StopProg. (0.25)</li>

 <li>Conveyor Tracking to be set to Conveyor1, Encoder Type incremental and conveyor type as Circular (0.25)</li>

 <li>Set the communication baud rate to 115200 (0.25)</li>

 <li>Set the home position to Base -247, Shoulder 78, Elbow -87 and Wrist 1 to -151, Wrist 2 to 141 and Wrist 3 to -145 (0. 25)</li>

 <li>Create a safety plane named Plane 1 based on Feature Base with restrictions as Normal and</li>

</ol>

Displacement of 12. Note it’s a Restrict Elbow. (3)

Hint: you need to set safety password before doing this task.





