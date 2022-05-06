# Quantum-Support-Vector-Machine
made qiskit QSVM work with updated libraries and code

I took as a template the code from Qiskit  https://qiskit.org/documentation/stable/0.24/tutorials/machine_learning/01_qsvm_classification.html
I  updated it with proper working libraries - in particular that site is using aqua, which is deprecated
Qiskit uses the "ad-hoc" data. I used nyc_restaurant data.
Also, I put the data on Elasticsearch. I used the Elastic client called Eland to interact between  python code and Elasticsearch.

