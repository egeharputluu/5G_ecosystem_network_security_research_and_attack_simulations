5G Ecosystem Network Security — Research

This repository contains research material, theoretical documentation, and the original presentation I prepared during my Network Engineering internship at Nokia. The work was delivered to the GPEC team and my engineering managers as part of a deep-dive study on security challenges in 5G and beyond network architectures.

The repository focuses on critical security aspects of 5G mobile networks, including threat models, slice-level attack surfaces, GTP-U tunneling risks, and modern adversarial techniques that target telecom infrastructures. It also includes high-level explanations of two applied attack simulations developed as part of my exploratory security research.

My Other Related Repositories (Source Code):

The corresponding source code for each attack simulation is maintained in separate repositories to preserve modularity and clarity:

IP Fragmentation → RCE Attack Simulation https://github.com/egeharputluu/ip_fragmentation_attack_to_rce_vulnerable_server_simulation

Federated Learning Poisoning Attack (FLPA) Simulation: https://github.com/egeharputluu/federated_learning_poisoning_attack


Contents of This Repository:

1. Presentation

A detailed presentation covering:

- 5G architecture fundamentals

- Network slicing security risks

- MEC and distributed edge vulnerabilities

- GTP-U tunneling weaknesses

- Modern 5G threat landscape

- Zero Trust & quantum-safe security models

- Nokia’s telecom-aware security solutions (NetGuard XDR, Cybersecurity Dome)

Files are in /presentation/ (PDF and PPTX formats).

2. Attack Simulation Explanations

The /attack_simulation_docs/ directory includes theoretical explanations for two network-security attack simulations:

- IP Fragmentation Attack in 5G Context: How fragmentation can bypass security controls, especially when inner IP packets travel inside GTP-U tunnels.

- Federated Learning Poisoning Attack (FLPA): A demonstration of how distributed AI components in 5G/6G ecosystems can be manipulated by adversarial clients.

These documents describe the threat models, attack vectors, and implications for next-generation telecom networks.

My Related Repositories (Source Code):

The corresponding source code for each attack simulation is maintained in separate repositories to preserve modularity and clarity:

IP Fragmentation → RCE Attack Simulation https://github.com/egeharputluu/ip_fragmentation_attack_to_rce_vulnerable_server_simulation

Federated Learning Poisoning Attack (FLPA) Simulation: https://github.com/egeharputluu/federated_learning_poisoning_attack


Each project includes its own implementation details, payload logic, and demonstration scripts.


Purpose of This Repository

The goal of this repository is to:

- Document my 5G network security research performed at Nokia

- Demonstrate telecom-aware threat understanding

- Highlight modern attack surfaces relevant to 5G/6G mobile networks

- Present theoretical foundations behind real attack simulations

- Show my combined expertise in network engineering, network security, cybersecurity research.

This repo acts as a research portfolio rather than a codebase.

Actual implementations are referenced through external repositories.

Focused on:
L2/L3 Networking • Network Security • Cybersecurity Engineering • Red/Blue Team Concepts • Network & Security Automation • 5G/6G Security Research
