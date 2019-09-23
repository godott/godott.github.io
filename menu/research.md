---
layout: default
title: Research
---

Pulse-level Quantum Compilation
-------------------
<p id="secondarytitle"> Breaking the ISA abstraction </p> 
We proposed a novel quantum compilation scheme that improves quantum circuit latency by 5X on average. Traditional compilation method first compiles quantum algorithms into pre-defined quantum gates (quantum ISA), then load corresponding control pulses in the hardware. Our approach form a new set of aggregated instructions for each circuit and generate customized control pulses with a quantum optimal control algorithm called GRAPE (GRadient-Ascent Pulse Engineering). This compilation
scheme is a core component of the NSF Expedition [<a href="epiqc.uchicago.edu">EPiQC</a>] and considered to "provide speed boost to quantum computers" by <a href="https://phys.org/news/2019-04-boost-quantum.html">phys.org</a>. 

<img src="../assets/img/QAOA_CriticalPath.png" width="320" style="padding-bottom: 60px;">
<img src="../assets/img/qaoa_demo1.png" width="280">
<img src="../assets/img/QAOA_Aggregated.png"  width="320" style="padding-top: 30px; padding-bottom: 30px;">
<img src="../assets/img/qaoa_demo.png" width="280">


<div>
        <h3>Related papers </h3>
	    <ul>
        <li>
            <a href="https://arxiv.org/pdf/1902.01474.pdf">Optimized Compilation of Aggregated Instructions for Realistic Quantum Computers</a><br>
            Yunong Shi, Nelson Leung, Pranav Gokhale, Zane Rossi, David I. Schuster, Henry Hoffman, and Frederic T. Chong.
            <strong>International Symposium on Architectural Support for Programming Languages and Operating Systems (ASPLOS)</strong>. April 2019. Providence, RI.
  	    </li>

      <li>
           <a href="https://arxiv.org/pdf/1909.07522.pdf"> Partial Compilation of Variational Algorithms for Noisy Intermediate-Scale Quantum Machines </a><br> Pranav Gokhale, Yongshan Ding, Thomas Propson, Christopher Winkler, Nelson Leung, Yunong Shi, David I Schuster, Henry Hoffmann, Frederic T Chong
        <strong> International Symposium on Microarchitecture (MICRO). </strong> October, 2019. Columbus, OH.
      </li>
      </ul>
</div>

* * *

Bosonic Qubit Architecture
------------------------
<p id="secondarytitle"> Breaking the qubit abstraction </p> 


***

CertiQ verification framework
-------------------------
<p id="secondarytitle"> Reliable quantum software</p> 
