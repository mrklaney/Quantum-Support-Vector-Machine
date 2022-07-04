# Quantum-Support-Vector-Machine
Made Qiskit QSVM work, but with updated libraries and code

I took as a template the code from Qiskit  https://qiskit.org/documentation/stable/0.24/tutorials/machine_learning/01_qsvm_classification.html

I updated it with proper working libraries, a different dataset, and interaction with Elasticsearch. In particular, that Qiskit site uses Aqua, a quantum computing library that has been deprecated. 
Qiskit uses their own "ad-hoc" dataset, while I used a more general nyc_restaurant dataset.
Also, I put the data in Elasticsearch. I used the Elastic client called Eland to interact between python, Elasticsearch, and IBM quantum computers.

