


<a href="https://www.python.org" rel="nofollow"><img src="https://camo.githubusercontent.com/bee9cae60ad03d7765f5bf82317c80a93ccd7d0b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e332d76332e362d677265656e3f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e" alt="python3" data-canonical-src="https://img.shields.io/badge/python3-v3.6-green?style=for-the-badge&amp;logo=python" style="max-width:100%;"></a>


<a href="http://badges.mit-license.org" rel="nofollow"><img src="https://camo.githubusercontent.com/107590fac8cbd65071396bb4d04040f76cde5bde/687474703a2f2f696d672e736869656c64732e696f2f3a6c6963656e73652d6d69742d626c75652e7376673f7374796c653d666c61742d737175617265" alt="License" data-canonical-src="http://img.shields.io/:license-mit-blue.svg?style=flat-square" style="max-width:100%;"></a>

# Quantum-Error-Mitigation


This is an attempt to reduce the quantum noice we get when we run a circuit in a quantum computer. I used the Qiskit framework along with Jupyter Notebook to code a simple quantum circuit. The circuit should output 1 when the values of both the qubits is equal to 1 so the probability of getting the state *11* should be 100% if the Quantum Computer is an ideal Quantum Computer. But since that is not the case we do get the probabilities of some other states mixed with our expected answer (states like *10 01 00*). So I have tried to mitigate this quantum noise by using Qiskit Ignis.

**Note** : If you run this program on a Quantum Simulator you will get the probabity to the state *11* to be 100% cause the Simulator imitates an ideal Quantum Computer.

The project was successful and the results improved by 11.8%. It went from 0.856% probability of getting a *11* state to 0.974% probability to getting a *11* state.***The circuit was run 3000 times on the service backend : ibmq_london(5 qubits)***



### Softwares and Libraries used 

- Jupyter Notebook
- Qiskit Terra 
- Qiskit Ignis
- Qiskit IBMQ-provider
- Matplotlib

 



