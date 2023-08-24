# Quantum Computing Course 2023 (LinkedIn Learning)

This repo is for the example challenges as part of the LinkedIn Learning Understanding Quantum Computing learning path.

The examples are in python and use qiskit  - a toolkit for working with quantum computing on silicon machines.

For me, I created a Python virtual environment to run everything but I think the course has a codespace environment that you can spin up. To get anaconda going, definitely recommend setting up a virtual environment with something like anaconda or a python3 venv. I just use the latter mostly.

```
python3 -m venv ./venv
source ./venv/bin/activate
```

To run the jupyter notebooks, you will need to setup a venv and ensure you have installed the required modules. These include :

```
pip install qiskit
pip install qiskit[visualization]
pip install qiskit-aer
```

(of special note is that last qiskit-aer module, which the qiskit install instructions might have missed)