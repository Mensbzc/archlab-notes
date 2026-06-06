# ENCOR 350-401: STP Root Bridge Selection & Port Roles

### 🏷️ Etiketler
`ccie,encor,stp,cisco,network-architecture,layer2`

### 🔬 Laboratuvar ve Topoloji Detayları
In this laboratory session, we dive into the Mariana depth of Spanning Tree Protocol (STP), the backbone of Layer 2 network topologies.

## Architectural Analysis
We execute an atomic-level breakdown of the Root Bridge selection math (Bridge Priority + MAC Address) and observe how BPDU packets trigger port state transitions (Root, Designated, Alternate, Blocking).

## Proof of Competence
This architecture is deployed on a 40-core physical simulation environment. Using CLI-level `debug spanning-tree events`, we verify BPDU exchanges and state transitions packet-by-packet.

## Resources & Configurations
For configuration files (configs/) and detailed technical documentation, visit the repository.
Domain: https://archlab.solutions
GitHub: https://github.com/mensbzc

---
*Designed and automated by Mehmet Enes Bozacı.*
