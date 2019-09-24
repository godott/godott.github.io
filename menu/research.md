---
layout: default
title: Research
---

Pulse-level Quantum Compilation
-------------------
<p id="secondarytitle"> Breaking the ISA abstraction </p> 
We proposed a novel quantum compilation scheme that improves quantum circuit latency by 5X on average. Traditional compilation method first compiles quantum algorithms into pre-defined quantum gates (quantum ISA), then load corresponding control pulses in the hardware. Our approach form a new set of aggregated instructions for each circuit and generate customized control pulses with a quantum optimal control algorithm called GRAPE (GRadient-Ascent Pulse Engineering). This compilation
scheme is a core component of the NSF Expedition [<a href="epiqc.uchicago.edu">EPiQC</a>] and is considered to "provide speed boost to quantum computers" by <a href="https://phys.org/news/2019-04-boost-quantum.html">phys.org</a>. 

<img src="../assets/img/QAOA_CriticalPath.png" width="330" style="padding-bottom: 45px;">
<img src="../assets/img/qaoa_demo1.png" width="250" align="right"> <br>
<img src="../assets/img/QAOA_Aggregated.png"  width="330">
<img src="../assets/img/qaoa_demo.png" width="250" align="right">

<div>
        <h3>Related papers </h3>
	    <ul>
        <li>
            <a href="https://arxiv.org/pdf/1902.01474.pdf">Optimized Compilation of Aggregated Instructions for Realistic Quantum Computers</a> (ASPLOS'19)
  	    </li>

      <li>
           <a href="https://arxiv.org/pdf/1909.07522.pdf"> Partial Compilation of Variational Algorithms for Noisy Intermediate-Scale Quantum Machines </a>(MICRO'19)      </li>
      </ul>
</div>

* * *

Bosonic Qubit Architecture
------------------------
<p id="secondarytitle"> Breaking the qubit abstraction </p> 
Bosonic encodings such as the Gottesman-Kitaev-Preskill (GKP) code are qubit architectures that provide error information for upper-level software to monitor its internal correctness, thus are promising candidates for fault-tolerant quantum computing comparing to traditional qubits such as transmon. The GKP code overcomes the fundamental limit set by the Heisenberg uncertainty principle. However, the GKP code is highly non-classical and hard to make. We gave fault tolerance definitions to the preparation of GKP states and designed protocols to fault-tolerantly preprare it.
<div align="center">
<img src="../assets/img/gkp.gif"  width="280">
</div>
<div>
        <h3>Related papers </h3>
	    <ul>
        <li>
           <a href="https://iopscience.iop.org/article/10.1088/1367-2630/ab3a62/pdf">Fault tolerant preparation of approximate GKP states </a>
           (New Journal of Physics)
        </li>
      </ul>
</div>

* * *

CertiQ verification framework
-------------------------
<p id="secondarytitle"> Reliable quantum software</p> 

Qiskit Terra is the most complete and widely used quantum compiler now. It's the foundation of the cloud-based IBMQ service with 10K+ users. With increasing community contribution, it's crucial to guarantee the code quality and automate the code review process. We implemented CertiQ, a mostly-automated verification framework. As far as we know, CertiQ is the first verification framework for a realistic quantum compiler. Leveraing SMT reasoning and contract based design, CertiQ revealed several critical bugs in Qiskit Terra, some of which are specific to quantum software. We believe that the methods developed in CertiQ pave the way to a fully verified quantum toolchain.
<div align="center">
<img src="../assets/img/certiq_flow.png"  width="320">
</div>
<div>
        <h3>Related papers </h3>
	    <ul>
            <li> <a href="https://arxiv.org/abs/1908.08963.pdf">
              Contract-based Verification of a Realistic Quantum Compiler. </a> (arXiv)
            </li>
        </ul>
</div>
