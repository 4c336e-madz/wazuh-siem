# wazuh-siem

Cybersecurity homelab using Wazuh as a SIEM.
The main objective of this project is to explore how a SIEM works, how to analyse logs and see the different automated responses across different attack scenarios.

---

The lab environment is fully virtualized using VirtualBox with the following nodes:

| Node | OS | Role | Description |
| --- | --- | --- | --- |
| Wazuh Server | Ubuntu | SIEM Manager / Dashboard | Central node for log collection. |
| Linux Endpoint | Ubuntu | Client / Target Agent | Monitored system running the Wazuh Agent. |

---

Deployment:

Wazuh Manager Setup: We install Wazuh in our Wazuh Server following the official Wazuh Quickstart documentation.
Network config: We make sure that all the nodes work inside the same network.
Agent deployment: Enrolled the Linux endpoint by executing the commands via "Deploy new agent" in Wazuh on our target node.
---

Scenarios WIP
