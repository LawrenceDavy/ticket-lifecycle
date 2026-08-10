# osTicket – Ticket Lifecycle (Part 3)

Independent walkthrough of a complete ticket lifecycle inside osTicket: intake → diagnosis → updates → escalation → resolution / closure.

## What was done
- Created sample tickets from both end-user and agent perspectives
- Assigned tickets to agents and teams
- Applied Help Topics and SLAs
- Updated ticket status and added internal notes / public replies
- Escalated a ticket between support levels
- Closed tickets with proper resolution codes
- Verified the full audit trail and accurate record-keeping at every stage
- Documented the complete lifecycle process

## Purpose
Evidence of process discipline, documentation standards and systems ownership.  
This remains an infrastructure / service-management project. Its value is proof of structured process execution and clear written documentation — not a data or analytics project.

## Tools & technologies used
- Microsoft Azure (Virtual Machines)
- Windows 10 (21H2)
- Internet Information Services (IIS)
- osTicket (Agent Panel and End-User Portal)
- Remote Desktop

## AI assistance
None used for the core process or primary documentation.  

---

<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" width="200"/>
</p>

# osTicket – Ticket Lifecycle

This document outlines the complete lifecycle of a ticket from intake to resolution within osTicket.

**Part 1 – Prerequisites & Installation:**  
[https://github.com/LawrenceDavy/osticket-prereqs](https://github.com/LawrenceDavy/osticket-prereqs)

**Part 2 – Post-Installation Configuration:**  
[https://github.com/LawrenceDavy/post-install-config](https://github.com/LawrenceDavy/post-install-config)

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines / Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

## Operating System Used
- Windows 10 (21H2)

---

## Ticket Lifecycle Overview

The screenshots below show the starting point of the ticket lifecycle process.

![Ticket view 1](https://github.com/LawrenceDavy/ticket-lifecycle/assets/24421979/d098e676-e8ce-4505-8f77-49afa4afcd54)

![Ticket view 2](https://github.com/LawrenceDavy/ticket-lifecycle/assets/24421979/0893cd05-4432-47d9-b0fe-b9d609bf2f9a)

---

## 1. Ticket Intake (End-User Portal)

- Log in (or submit as guest) via the end-user portal
- Select the appropriate Help Topic
- Complete the ticket form with clear subject and description
- Submit the ticket and note the generated ticket number


---

## 2. Agent Assignment & Initial Diagnosis

- Open the ticket in the Agent Panel
- Assign the ticket to the correct Department / Team / Agent
- Apply or confirm the correct SLA
- Add an initial internal note summarising the diagnosis


---

## 3. Updates & Communication

- Post public replies to the requester
- Add internal notes for other agents
- Update ticket status (Open → In Progress, etc.)
- Attach any relevant files or screenshots


---

## 4. Escalation

- Escalate the ticket from Level I Support to Level 2 Support (or to System Administrators)
- Update the assigned agent / team
- Record the reason for escalation in an internal note


---

## 5. Resolution & Closure

- Confirm the issue is resolved with the requester
- Set the final status to Resolved / Closed
- Select an appropriate resolution code
- Verify that the full history (timestamps, agents, notes) is accurately recorded


---

## Lessons Learned
- Clear Help Topics and SLAs at intake make routing and prioritisation much more reliable.
- Consistent use of internal notes creates a usable audit trail for later review or hand-over.
- Escalation works best when the reason and current state are explicitly documented.
- Closing tickets with a proper resolution code keeps reporting meaningful.

---

**Last verified:** August 2026
