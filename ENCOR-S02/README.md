# ENCOR 350-401: STP Topology Change Notification (TCN) & Network Storms

### 🏷️ Etiketler
`ccie,encor,stp,tcn,layer2,troubleshooting`

### 🔬 Laboratuvar ve Topoloji Detayları
 This session investigates the disruptive nature of STP Topology Change Notifications (TCN) and their impact on MAC address tables.

## Architectural Analysis
We simulate a link failure to observe the generation of TCN BPDUs, analyzing how the Root Bridge responds with TCA (Topology Change Acknowledgment) and forces switches to flush their MAC tables, dropping the aging time to 15 seconds.

## Proof of Competence
Captured via CLI packet analysis, we validate the propagation of TCNs across the Layer 2 domain and demonstrate mitigation techniques.

## Resources & Configurations
For configuration files (configs/) and detailed technical documentation, visit the repository.
Domain: https://archlab.solutions
GitHub: https://github.com/mensbzc

---
*Designed and automated by Mehmet Enes Bozacı.*
