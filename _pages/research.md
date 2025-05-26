---
layout: research
permalink: /research/
title: research
nav: false
nav_order: 3
---

# **Research**

---

</br>

## Preparing quantum states with measurements

<figure>
  <img src="/MPS.png" alt="image" width="500" height="auto">
  <figcaption>Algorithm to prepare a matrix-product state. Figure from <a href="https://doi.org/10.1103/PhysRevLett.132.040404">PRL (2024)</a>.</figcaption>
</figure>

</br>

Measurements are often solely thought of as means to extract information from a quantum state. However, measurement can also be used as an *active ingredient* in quantum protocols. This line of work explores how the resources (such as circuit depth) needed to transform a given state to a target one can be *drastically reduced* by utilizing measurements.

The problem of state preparation is evidently motivated by the *practical need* to prepare states in quantum devices, e.g., for quantum computing and simulation. However, it also has a more *fundamental flavor* to it since it connects to the classification of topological phases. It turns out that measurements can significantly lower the complexity for the preparation of states, which implies that certain *topological phases collapse* when measurements are considered.


</br>

### Selected Publications:

</br>

*   *Phases of Matrix Product States with Symmetric Quantum Circuits and Symmetric Measurements with Feedforward,*  
    Gunn, **Styliaris**, Kraft, Kraus
    [\[PRB (2025)\]](https://journals.aps.org/prb/accepted/b507cDdeA6b1910000c96b65ac150201fc7292425)

</br>

*   *Characterizing MPS and PEPS Preparable via Measurement and Feedback,*  
    Zhang, Gopalakrishnan, **Styliaris**
    [\[PRX Quantum (2024)\]](https://doi.org/10.1103/PRXQuantum.5.040304)


</br>

*   *Approximating many-body quantum states with quantum circuits and measurements,*  
    Piroli, **Styliaris**, Cirac
    [\[PRL (2024)\]](https://journals.aps.org/prl/accepted/8f07aY05E9e18f84042543493780b9c85f774fc18)


</br>

*   *Preparation of Matrix Product States with Log-Depth Quantum Circuits,*  
    Malz<sup>\*</sup>, **Styliaris<sup>\*</sup>**, Wei<sup>\*</sup>, Cirac [\[PRL (2024)\]](https://doi.org/10.1103/PhysRevLett.132.040404)
    [\[Talk at TQC 2024 @OIST\]](https://www.youtube.com/watch?v=kIUDV3AvuiM&t=3600s)
  
</br>

*   *Quantum Circuits Assisted by Local Operation and Classical Communication: Transformations and Phases of Matter,*  
    Piroli, **Styliaris**, Cirac [\[PRL (2021)\]](https://doi.org/10.1103/PhysRevLett.127.220503)
     [\[Talk at QIP 2022 @Caltech\]](https://youtu.be/mct_FB3O-Ms?si=vyQbgSB3A_uF7tLR)
     
</br>

----

</br>

## Theory of tensor networks

<figure>
  <img src="/TN.png" alt="image" width="500" height="auto">
  <figcaption>Multiple copies of a random tensor network. Figure from <a href="https://doi.org/10.1103/PRXQuantum.4.030330">PRX Quantum (2023)</a>.</figcaption>
</figure>


</br>

The many-body Hilbert space is large, as it grows *exponentially* with the number of constituents \[*"no one can hear you scream there"*, as I learned from [Todd Brun](https://viterbi.usc.edu/directory/faculty/Brun/Todd)\]. However, when interactions are local, the corresponding low-energy eigenstates are *captured by tensor-networks*. This not only allows for an *efficient* description of the relevant quantum states, but also provides a general framework for many-body physics, in the *language of quantum information*.

</br>


### Selected Publications:


</br>

*   *Matrix-product unitaries: Beyond quantum cellular automata,*  
    **Styliaris**, Trivedi, Pérez-García, Cirac [\[Quantum (2025)\]](https://doi.org/10.22331/q-2025-02-25-1645)

</br>

*   *Parent Lindbladians for Matrix Product Density Operators,*

    Liu, Ruiz-de-Alarcón, **Styliaris**, Sun, Pérez-García, Cirac [\[arXiv (2025)\]](https://doi.org/10.48550/arXiv.2501.10552)
    
</br>

*   *Typical Correlation Length of Sequentially Generated Tensor Network States,*  
    Haag, Baccari, **Styliaris** [\[PRX Quantum (2023)\]](https://doi.org/10.1103/PRXQuantum.4.030330)

</br>

----

</br>

## Exactly solvable quantum states and dynamics

<figure>
  <img src="/Space_time.png" alt="image" width="700" height="auto">
  <figcaption>A quantum circuit of space-time quantum channels. Figure from <a href="https://doi.org/10.22331/q-2023-05-24-1020">Quantum (2023)</a>.</figcaption>
</figure>

</br>

Dual-unitary circuits have emerged as a rich model of quantum dynamics. While this class includes both *integrable and chaotic* models, it allows for the analytical solution of *correlation functions*. The defining property of these circuits is that, when the role of *space and time is exchanged*, the corresponding evolution remains physical, i.e., unitary.

No realistic quantum system is perfectly isolated. Fortunately, it turns out that the ideas of dual-unitarity can be extended to the realm of open systems. Here we explore how, by postulating the analogous symmetry between space and time, *solvability is extended to quantum channels*.

The same ideas allow to define a nontrivial subclass of 2D tensor-network states with exactly solvable single and 2-body correlation functions. The connection can be understood by interpreting the tensor-network contraction as evolution over the virtual space.

</br>

### Selected Publications:

</br>

*   *Dual-isometric Projected Entangled Pair States,*  
    Yu, Cirac, Kos<sup>*</sup>, **Styliaris<sup>\*</sup>** [\[PRL (2024)\]](https://journals.aps.org/prl/accepted/33071Y7cFd81329590089116f7a025c305b9efdc0)
    
</br>

*   *Circuits of space and time quantum channels,*  
    Kos<sup>*</sup>, **Styliaris<sup>\*</sup>** [\[Quantum (2023)\]](https://doi.org/10.22331/q-2023-05-24-1020)  [\[Perspective on our article by Shane Dooley\]](https://doi.org/10.22331/qv-2023-07-26-75)


</br>

----



</br>


## Quantum information theory & Quantum computing

<figure>
  <img src="/monotones_BW.png" alt="image" width="600" height="auto">
  <figcaption>Symmetries in Markovian dynamics give rise to monotones. Figure from <a href="https://doi.org/10.22331/q-2020-04-30-261">Quantum (2020)</a>.</figcaption>
</figure>

</br>

Quantum information offers a *powerful language* for understanding quantum phenomena through the lens of *information processing* and *computation*. I enjoy thinking about different problems from the perspective of quantum information, ranging from measurement incompatibility, to information scrambling and symmetries in open systems.


</br>

### Selected Publications:

</br>

*   *Accuracy guarantees and quantum advantage in analogue open quantum simulation with and without noise,*  
    Kashyap, **Styliaris**, Mouradian, Cirac, Trivedi [\[PRX (2025)\]](https://journals.aps.org/prx/accepted/64071Ke6Ebe1f30bc85b6de6a6d889a50f914592c)

</br>

*   *Computable Rényi mutual information: Area laws and correlations,*  
    Scalet, Alhambra, **Styliaris**, Cirac [\[Quantum (2021)\]](https://doi.org/10.22331/q-2021-09-14-541)

</br>

*   *Information Scrambling over Bipartitions: Equilibration, Entropy Production, and Typicality,*  
    **Styliaris**, Anand, Zanardi [\[PRL (2021)\]](https://doi.org/10.1103/PhysRevLett.126.030601)

</br>

*   *Symmetries and monotones in Markovian quantum dynamics,*  
    **Styliaris**, Zanardi [\[Quantum (2020)\]](https://doi.org/10.22331/q-2020-04-30-261)
    
</br>

*   *Fundamental Limitations to Local Energy Extraction in Quantum Systems,*  
    Alhambra, **Styliaris**, Rodríguez-Briones, Sikora, Martín-Martínez [\[PRL (2019)\]](https://doi.org/10.1103/PhysRevLett.123.190601)    

</br>

*   *Quantifying the Incompatibility of Quantum Measurements Relative to a Basis,*  
    **Styliaris**, Zanardi [\[PRL (2019)\]](https://doi.org/10.1103/PhysRevLett.123.070401)



</br>

----