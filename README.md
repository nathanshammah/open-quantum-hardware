# Open Quantum Hardware Projects
a list of quantum open hardware projects.

This is thought as a collaborative repository where everyone can add projects that belong to open hardware in quantum science and technology. For open-source software projects in quantum computing, there is the excellent repository by the Quantum Open Source Foundation, with the awesome repository, which includes experimental quantum computing packages. 

A list of projects is already added to this open-quantum-hardware list, but feel free to add more, by opening a pull request, or, if you are not familiar with git, opening a descriptive issue. 

## Blueprints for hardware design
- [pyEPR](https://pyepr-docs.readthedocs.io/) is standing out for superconducting qubits as a platform to design quantum processors. Originally developed at Yale, it is now used by tens of research groups in Northern America, Europe, and beyond. 
- [Qiskit Metal](https://github.com/Qiskit/qiskit-metal) - Quantum hardware design and analysis for superconducting qubits.
- [KQCircuits](https://github.com/iqm-finland/KQCircuits) - KLayout Python library for integrated quantum circuit design

## Remotely-controlled laboratories 
- Chris Monroe’s article highlighted the implementation of software for remote labs.
- ColdQuanta's [Albert](https://www.coldquanta.com/news/coldquanta-announces-quantum-matter-on-the-cloud/): a Bose Einstein Condensate controlled from the cloud. 

## Automate processes in the labs, for example for data acquisition:
- [QCodes](http://qcodes.github.io/Qcodes/), a Python-based data acquisition framework developed at research centers in Copenhagen, Delft, Sydney, and at Microsoft Research.  
- [Auspex](https://github.com/BBN-Q/Auspex), the AUtomated System for Python-based EXperiments, is a framework for performing laboratory measurements. 
- [LabScript](https://docs.labscriptsuite.org/en/latest/), Python based framework for experiment composition, control, execution, and analysis. Developed for quantum science and quantum engineering; deployable in laboratory and in-field devices. Used for example, with [PennyLane](https://github.com/synqs/pennylane-ls)
- [QLAB](https://github.com/BBN-Q/Qlab). 
- [ARTIQ](http://m-labs.hk/experiment-control/artiq/), which stands for Advanced Real-Time Infrastructure for Quantum physics is a software that provides fast control for trapped ions enhanced by the use of FPGAs. Developed at NIST, then National Institute for Standard and Time. 
- [qupulse](https://github.com/qutech/qupulse), a software created at QuTech specifically designed to implement pulse-level control of quantum spins in the lab. 
- OpenPulse, and Qiskit Pulse ([arxiv](https://arxiv.org/abs/2004.06755)). 
- [Quantify](https://gitlab.com/quantify-os): Quantify is a python based data acquisition platform focused on quantum computing and solid-state physics experiments.
- [Instrument Kit](https://github.com/Galvant/InstrumentKit): Python package for interacting with laboratory equipment over various buses.
- [Instrumental](https://github.com/mabuchilab/Instrumental): Instrumental is a Python-based library for controlling lab hardware like cameras, DAQs, oscilloscopes, spectrometers, and more.
- [Qick](https://github.com/openquantumhardware/qick): Quantum Instrumentation Control Kit is a kit of firmware and software to use the Xilinx RFSoC to control quantum systems ([arXiv](https://arxiv.org/abs/2110.00557)).

### Open-source software for hardware characterization and optimization
- Quantum optimal control, noise calibration, error mitigation, has a side that is amenable to extend hardware into open-software. 
- [C3](https://c3-toolset.readthedocs.io/), an optimal control software with a full quantum state simulator developed mainly at Julich and University of Saarland within the framework of the EU’s open quantum computer, OpenSuperQ, which has an attention to open accessibility. ([arxiv](https://arxiv.org/abs/2009.09866))
- Mitiq, the open source software being developed at Unitary Labs, the R&D arm of Unitary Fund, which can provide customizations with tight integration with specific executors. 
