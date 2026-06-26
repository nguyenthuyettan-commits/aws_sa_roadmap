# aws_sa_roadmap

# 🎯 AWS Presales Solutions Architect Portfolio & Knowledge Base

A secure, centralized repository dedicated to architectural blueprints, technical documentation, compliance frameworks, and Architecture Decision Records (ADRs). This knowledge base is structured to support enterprise-grade cloud migration, modernization, and FinOps discovery phases.

> **Role & Track Focus:** Account Manager / Presales Solutions Architect Track.
> **Objective:** Transition from generic product-selling to high-impact, architecture-driven advisory for Enterprise, FSI, and Government segments in Vietnam.
> **Schedule:** 3 sessions/week, 1.5–2 hours/session over ~18 weeks (Part-time alignment with full-time AM role).

---

## 🧭 Strategic Objectives

*   **Advanced Cloud Networking:** Master secure hybrid connectivity patterns (VPC topology, AWS Transit Gateway, AWS Direct Connect) to unblock complex migration constraints during the discovery phase.
*   **Security & Compliance (Vietnam Localized):** Deepen expertise in cloud-native defense (AWS IAM Least Privilege, KMS, GuardDuty, WAF) and map them directly to local data residency laws, specifically **Decree 13/2023/ND-CP (PDPL)**.
*   **Credibility & Validation:** Anchor technical proficiency by preparing for and securing the **AWS Certified Solutions Architect – Associate (SAA-C03)** credential.
*   **Deal-Driven Architecture:** Translate technical capabilities into production-ready proposals, gap analyses, and architectural diagrams tied directly to active enterprise pipelines.

---

## 📂 Repository Structure

```text
├── diagrams/                   # Global architectural blueprints and Draw.io design files
├── adr/                        # Architectural Decision Records tracking technical trade-offs
├── phase-0-setup/              # Environment readiness, cloud sandbox configs, and case studies
├── phase-1-networking/         # VPC topology, hybrid connectivity patterns, and routing notes
├── phase-2-security-compliance/ # Cloud-native defense controls and Vietnam Decree 13 frameworks
├── phase-3-certification/      # SAA-C03 preparation assets, domains review, and exam blueprints
└── phase-4-sa-practice/        # Full proposal synthesis, mock Q&A matrices, and peer reviews

🗓 Detailed Study & Execution Schedule

🛠 PHASE 0: Setup & Orientation (Week 1)

Goal: Environment readiness & selecting an active pipeline deal as a continuous case study.

Sessions:

Session 1 (1.5h) - AWS Sandbox Account: Understanding Sandbox separation. Setup AWS Free Tier, $5 Billing Alarm, and a dedicated non-root IAM Administrator user.

Session 2 (1.0h) - GitHub for Documentation: Why SAs document architectural decisions beyond standard CRM logging. Repo structure initializing (presales-notes).

Session 3 (1.0h) - Case Study Selection: Selecting an active enterprise account (e.g., PV***) to ground all technical concepts into a real-world solution.

🌐 PHASE 1: AWS Networking Foundation (Weeks 2–5)

Goal: Master core networking patterns — the root cause of 80% of migration bottlenecks.

Sessions:

Session 1 (2.0h) - VPC & Subnet Design: Public vs. Private subnets, CIDR block planning, and architectural diagramming via Draw.io.

Session 2 (2.0h) - Routing, IGW, NAT Gateway: Route table mechanics, NAT Gateway vs. Internet Gateway deployment, and verification.

Session 3 (1.5h) - Security Group vs. NACL: Stateful vs. Stateless traffic filtering for enterprise 3-tier architectures.

Session 4 (2.0h) - Direct Connect vs. VPN vs. Transit Gateway: Evaluating latency, cost, and reliability for on-premise to AWS hybrid connections.

Session 5 (1.5h) - Route 53 & DNS Patterns: DNS resolution strategies and routing policies (Latency, Geolocation, Failover).

Session 6 (2.0h) - Terraform Blueprint Reading: Understanding Infrastructure-as-Code (IaC) block syntax to effectively interpret SA team scripts.

🔐 PHASE 2: AWS Cloud-Native Security & Compliance VN (Weeks 6–9)

Goal: Independently answer security, sovereignty, and isolation questions without waiting for technical delivery teams.

Sessions:

Session 1 (2.0h) - IAM Advanced: Principle of Least Privilege, cross-account roles, and STS configurations.

Session 2 (1.5h) - Encryption (KMS & Data Protection): Customer-managed keys vs. AWS-managed keys; compiling non-technical talk tracks.

Session 3 (2.0h) - Threat Detection (GuardDuty, Security Hub, Config): Continuous automated threat monitoring and identifying common architectural gaps.

Session 4 (1.5h) - WAF & Shield: Edge security, DDoS mitigation, and configuring Layer 7 rate-limiting rules.

Session 5 (2.0h) - Well-Architected Framework (Security Pillar): Running an architectural gap analysis against your active target deal.

Session 6 (2.5h) - Compliance VN (Decree 13/PDPL, ISO 27001): Mapping local data residency and data protection laws directly to AWS regional services and security controls.

🏆 PHASE 3: AWS SAA-C03 Certification (Weeks 10–13)

Goal: Secure the Solutions Architect – Associate credential to cement market credibility.

Sessions:

Session 1 (3.0h) - Domains 1–2: Resilient & High-Performing Architectures (leveraging Phase 1 knowledge).

Session 2 (2.5h) - Domain 3: Secure Architectures (leveraging Phase 2 deep dives).

Session 3 (3.0h) - Domain 4 & Full Mock Exams: Cost-Optimized Architectures and continuous full-length practice review.

Session 4 (3.0h+) - Official Examination: Completing the AWS official proctored SAA-C03 test.

🚀 PHASE 4: Real-World Presales Application (Weeks 14–17)

Goal: Close the loop by translating technical validation into live pipeline proposals with peer-review.

Sessions:

Session 1 (2.5h) - Full Architecture Blueprinting: Synthesizing network and security layers into a single end-to-end Draw.io model.

Session 2 (2.0h) - Architecture Decision Records (ADRs): Writing structural documents defending high-impact layout decisions.

Session 3 (2.0h) - Mock Q&A (CISO/IT Director Focus): Compiling a tactical response matrix against tough technical objections.

Session 4 (1.5h) - Technical Peer Review: Pitching the architecture blueprint and ADRs to internal technical leads for critical feedback.

Session 5 (Variable) - Deal Insertion: Integrating the finalized, reviewed architectural layout directly into a live client commercial proposal.

📑 Core Architecture Principles (Weekly Guardrails)
Solution-Oriented, Not Ops-Heavy: Focus on reading infrastructure, interpreting anomalies, and evaluating security postures to communicate effectively with client executives, rather than building production-level pipelines from scratch.

Every Design Tied to Business Value: Never study abstract theory; every service configured in the AWS Sandbox must answer: "How does this mitigate a financial/operational risk or reduce cost for our target enterprise deals?"

Strict Architectural Traceability: Every critical design decision must be backed by an ADR documenting context, alternatives considered, and architectural trade-offs.

Attacker Mindset vs. Presales Focus: Exploring offensive security/CTFs on the side is highly encouraged to understand threat behaviors, but must remain strictly time-boxed so defense, compliance, and structural design remain the core priorities.

Maintained by Tan Nguyen — Account Manager & Presales SA Track
