# Routing Project in OMNeT++

This project explores and implements custom routing algorithms in OMNeT++, designed for both educational and performance testing purposes. It includes simulation scenarios, performance analyses, and improvements made to the routing mechanisms to enhance efficiency in packet delivery and more.

## 🧠 What is OMNeT++?

[OMNeT++](https://omnetpp.org) is a modular, component-based C++ simulation framework primarily used for building network simulators. It is widely used in academia and research for simulating wired and wireless communication networks, including internet protocols, vehicular networks, and 5G/6G systems.

Key features of OMNeT++ include:

- A graphical IDE based on Eclipse for modeling and running simulations.
- NED language for defining network topologies.
- Support for hierarchical models and reusable modules.
- Strong visualization tools and result analysis features.
- Extensible with popular frameworks like INET, Simu5G, and Veins.

In this project, OMNeT++ is used to model and simulate custom routing protocols over multiple network topologies, enabling detailed performance evaluation and testing.

## 📌 Objective

The aim of this project is to:
- Develop and compare custom routing strategies.
- Analyze their performance under different network scenarios.
- Demonstrate how optimization techniques can improve throughput, reduce packet loss, and lower end-to-end delay in OMNeT++ simulations.

## 🧠 Key Features

- ✅ Static routing using `cTopology`.
- ✅ FSM-based routing logic enhancements.
- ✅ Multiple test networks (e.g., Net5, Net60).
- ✅ Conditional statistics tracking.
- ✅ Performance comparisons and metrics output.

## 🧪 Network Scenarios

The simulations are tested under various network topologies to understand routing behavior under different conditions:
- **Net5**: A small test topology for debugging and feature validation.
- **Net60**: A complex scenario to evaluate scalability and performance under load.

## 📊 Performance Metrics

The project tracks and compares routing strategies using the following metrics:
- Packet delivery ratio
- End-to-end latency
- Queue utilization
- Throughput
- Packet loss rate

These metrics are analyzed and exported for visual and statistical evaluation.

## 🛠️ Technologies Used

- **OMNeT++** (Version 6.x recommended)
- **INET Framework** (for network simulation modules)
- **C++** (for core logic implementation)
- **NED** (for network description files)
- **Python/Matplotlib** (for post-simulation data analysis - optional)

## 🗂️ Project Structure

```bash
Routing_Project_OMNeT_/
│
├── src/                    # Source files (C++)
│   ├── routing/            # Custom routing modules
│   └── scenarios/          # Scenario-specific logic
│
├── ned/                    # Network description files
│   ├── topologies/         # Net5, Net60 etc.
│   └── config/             # Scenario-specific configurations
│
├── results/                # Simulation output
│
├── omnetpp.ini             # Main configuration file
└── README.md               # Project description 
