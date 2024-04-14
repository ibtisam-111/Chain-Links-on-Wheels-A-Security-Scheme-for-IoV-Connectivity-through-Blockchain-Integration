# A Security Scheme for IoV Connectivity through Blockchain Integration
This repository contains code and data used for the performance evaluation of a blockchain-based Internet of Vehicles (IoV) architecture. The research aims to assess the computational and packet overhead incurred by the blockchain-based IoV architecture compared to a baseline method that handles transactions without encryption, hashing, and blockchain.

Key Features:

Simulated IoV scenarios using the Cooja simulator with Contiki OS.
Utilized IPv6 over Low Power Wireless Personal Area Networks (6LoWPAN) for communication.
Simulated three z1 mote sensors mimicking IoV devices sending data to a local vehicle miner every 2 seconds.
Evaluated packet overhead for different flows: from devices to the miner, from the miner to the cloud, and from the cloud to the miner.
Repository Contents:

Code: Contiki OS code used for simulation.
Data: Packet overhead evaluation results in CSV format.
Figures: Figures demonstrating the outcomes for time overhead.
Documentation: README.md providing an overview of the research project and simulation setup.
Usage:

Clone the repository.
Follow the instructions in the README.md to set up the simulation environment and run the code.
Analyze the packet overhead evaluation data and figures to understand the performance implications of the blockchain-based IoV architecture.
Contributing:

Contributions to this repository are welcome. Please open an issue or submit a pull request with any suggestions, improvements, or additional data.
