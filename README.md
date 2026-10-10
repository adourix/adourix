# Abdulrahman Ayad

**Computer & Communication Engineering Graduate · Networked Systems · Linux Infrastructure**

I am a Computer and Communication Engineering graduate from **Mansoura University, Egypt**. I build systems around Linux networking, infrastructure automation, and the relationship between high-level policy and the system state that actually runs.

My current direction is research-oriented: **networked systems, network management and programmability, Linux systems, and automated policy enforcement**.

---

## Research Interests

- Networked systems and network management
- Network programmability and automation
- Linux systems and kernel networking
- Declarative policy enforcement and state reconciliation
- Systems correctness and performance
- Cloud and container infrastructure

## Selected Projects

### Linux Network Control System (LNCS)

A policy-driven Linux gateway controller exploring how declarative network policies can be translated into kernel-level enforcement and reconciled against realized state.

- Uses a controlled enforcement boundary for Linux networking operations.
- Works with `nftables`, `tc`/HTB, IFB, and `iproute2`.
- Separates desired policy from observed kernel state instead of treating a database record as proof of enforcement.
- Includes policy and traffic-control state inspection, reconciliation logic, and device-identity handling.
- Current implementation scope: single-interface routing with IFB-based shaping.

**Repository:** [ayad-network-manager](https://github.com/adourix/ayad-network-manager)

*Research direction:* correctness, convergence, and the enforcement cost of continuously reconciling declared policy with actual network state. Quantitative performance guarantees are not claimed; real-hardware benchmarking remains future evaluation work.

### AyadCloud

A self-hosted platform project focused on containerized deployment and service routing.

- Docker-based application deployment
- Nginx reverse-proxy routing and HTTPS/TLS
- GitHub webhook-driven deployment workflows
- Multi-container infrastructure

**Repository:** [ayadcloud](https://github.com/adourix/ayadcloud)

### AI-Enhanced SD-WAN

A team project exploring machine-learning-assisted SD-WAN. My contribution focused on network topology, WAN traffic generation and measurement, and the attack-simulation testbed.

**Repository:** [depi-garduation-project](https://github.com/adourix/depi-garduation-project)

---

## Technical Areas

| Area | Tools and Technologies |
|---|---|
| Linux networking | `nftables`, `tc`, HTB, IFB, `iproute2`, ARP, `dnsmasq` |
| Networking | TCP/IP, routing, network automation, SDN concepts |
| Backend development | Node.js, TypeScript, Fastify, REST APIs, WebSockets |
| Data and interfaces | PostgreSQL, Prisma, SQLite, React |
| Infrastructure | Linux, Docker, Nginx, HTTPS/TLS, GitHub webhooks |
| Programming | Python, JavaScript, TypeScript, C/C++ |

## Education

**B.Sc. in Computer and Communication Engineering**  
Mansoura University, Egypt · 2022–2026  
**GPA: 3.79 / 4.00**

## Certifications & Training

- Cisco CCNA
- Cisco CCNP ENCOR — in progress
- Microsoft Azure Fundamentals (AZ-900)
- Microsoft Azure Administrator (AZ-104) — in progress
- Huawei HCIA-AI

## Current Focus

I am preparing for **thesis-based Master's research for Fall 2027** and looking for research problems at the intersection of networked systems and Linux infrastructure. In particular, I am interested in how systems can express intent, enforce it through operating-system mechanisms, detect divergence, and evaluate the correctness and cost of bringing actual state back into line.

## Contact

- **Email:** [abdulrahmanayad67@gmail.com](mailto:abdulrahmanayad67@gmail.com)
- **GitHub:** [@adourix](https://github.com/adourix)

---

<sub>Research interests and project descriptions reflect current work and intended directions; prospective technologies such as eBPF/XDP are interests for future exploration, not claims of implementation in LNCS.</sub>
