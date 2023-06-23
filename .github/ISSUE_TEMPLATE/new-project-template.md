---
name: Music Q
about: Modu-lab
title: Exploring the connection between quantum circuits and music
labels: #Music #FT #QuantumCircuit 
assignees: ''

---

# Abstract
<!-- A more detailed description of the idea -->
Our team was interested in the relationship between music and quantum circuits, so we investigated how to represent mathematical formulas or quantum circuits musically. We used three packages: qmuvi, quantum audio, and qiskit. The Qmuvi project teaches you how to create musical representations of quantum circuits. In the case of the quantum audio package, it shows how to express an array of numbers as a quantum circuit. The qiskit package is needed to use the quantum auto encoder and the HHL algorithm.

# Description 
<!-- ⚠️ Optional. Remove this section if not needed -->
 Our team was interested in the connection between quantum circuits and music: we wanted to investigate how music is represented by numbers, and how sequences can be represented by quantum circuits. Conversely, we also wanted to investigate how quantum circuits can be represented by numbers, and how those numbers can be represented by music. 
More specifically, you can sample an analog signal, quantize a digital signal, and represent the quantized sequence as a quantum circuit. 
 qmuvi and quantumaudio represent this process respectively. 
 When I experimented with the qmuvi and quantumaudio packages, I didn't just use the resources they provided. I was curious to see how the sound would change after adding noise to the quantum circuit, which is the input data when using qmuvi. I added depolarizing error, which is one of the flip errors, to see if the sound changed, and then added quantum auto encoder to see if the sound sounded normal again.   
Meanwhile, how can music be represented mathematically? To explore this issue, we looked at the wave equation, whose solution set is represented by a Fourier series. The wave equation is represented by a differential equation, and it is known that differential equations are interchangeable by the Fourier and Laplace transforms. However, when solving this differential equation, it is sometimes difficult to compute the inverse matrix, and we further found that the HHL algorithm makes it easier to find the solution.
<!-- A more detailed description of the idea -->


# Members
<!-- up to 5 members in the team. You don't need them when you submit the idea, but they need to be there when the hackathon starts. -->
- Jeonghun Kim - Slack: `@jeonghun kim` email: `kimboyworkman@gmail.com`
- Minji Kim - Slack: `@minmin` email: `mjdorothy679@naver.com`
- Yungbeom Kim - Slack: `@김영범` email: `eddy9797@naver.com`

<!-- ⚠️ Before the final submission, the project needs to have a coach -->

# Deliverables
(reference)
https://garymooney.github.io/qmuvi/mapping_quantum_to_music_link.html
https://quantumaudio.readthedocs.io/en/latest/tutorial.html
<!-- A paper, a mobile app, a Terra module, etc -->

# GitHub repo link
https://github.com/minminjao/MusicQ
<!-- A link to the github repo where the project will be developed -->
