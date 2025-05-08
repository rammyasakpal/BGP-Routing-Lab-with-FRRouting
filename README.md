# BGP-Routing-Lab-with-FRRouting

BGP Routing Lab with FRRouting

This project simulates a Border Gateway Protocol (BGP) environment using Dockerized FRRouting (FRR), emulating real-world routing infrastructure across multiple Autonomous Systems (ASes).

Overview

- Designed and deployed a simulated inter-AS network using Dockerized FRRouting (FRR), modeling realistic BGP infrastructure.
- Automated deployment of virtual routers with distinct ASNs and tailored routing policies using Bash scripts in a Linux environment.
- Captured and analyzed BGP control messages (OPEN,UPDATE,KEEPALIVE,NOTIFICATION) to verify prefix propagation, route negotiation, and convergence behavior.
- Diagnosed misconfigurations including AS path mismatches and unreachable prefixes, reinforcing best practices in packet forwarding architecture.

Technologies Used

- Docker
- FRRouting (FRR)
- Bash Scripting
- tcpdump
- Linux Networking Tools

Project Structure (Coming Soon)

- docker-compose.yml – container orchestration for FRR routers
- router1, router2, router3 – configuration folders per router
- scripts – automation scripts for setup and testing
- logs – captured traffic and diagnostic logs
- README.md – project documentation
- topology.png– BGP network topology diagram (to be added)

Status

In Progress – Finalizing configs, testing behavior, and cleaning documentation. Project files will be uploaded shortly.



Suggestions, issues, and contributions are welcome!
