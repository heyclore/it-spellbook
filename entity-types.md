# Recommended Core Entity Types (IT Ontology v1.0)

You don’t want too many.  
You want enough to separate abstraction levels.

A solid starting model is **12–15 entity types**.

---

## 1. Concept

Abstract ideas.

**Examples:**
- Virtualization
- Encryption
- High Availability
- Zero Trust

Use when it is theoretical or principle-based.

---

## 2. Technology

A concrete technical solution category.

**Examples:**
- Containerization
- Blockchain
- Relational Database
- LAN

Higher-level than product, lower-level than concept.

---

## 3. Product

Vendor-specific implementation.

**Examples:**
- Windows Server
- VMware vSphere
- Cisco Catalyst 9300
- MySQL

---

## 4. Component

Physical or logical building block.

**Examples:**
- Router
- CPU
- API
- Kernel
- Switch

---

## 5. Protocol

Communication rule/system.

**Examples:**
- TCP
- HTTP
- DNS
- BGP

---

## 6. Standard

Formalized specification.

**Examples:**
- ISO 27001
- IEEE 802.3
- NIST SP 800-53

---

## 7. Framework

Structured methodology or model.

**Examples:**
- ITIL
- COBIT
- TOGAF
- NIST Cybersecurity Framework

---

## 8. Process

Operational workflow.

**Examples:**
- Incident Response
- CI/CD
- Backup Procedure
- Change Management

---

## 9. Policy

Governance directive.

**Examples:**
- Access Control Policy
- Data Retention Policy
- Password Policy

---

## 10. Control

Security or operational safeguard.

**Examples:**
- Firewall Rule
- Multi-Factor Authentication
- Physical Access Badge System

Can be:
- Physical Control
- Logical Control
- Administrative Control

---

## 11. Architecture

Structured system design.

**Examples:**
- Client-Server Architecture
- Microservices Architecture
- Zero Trust Architecture

---

## 12. Service

Provided capability (internal or external).

**Examples:**
- Cloud Storage Service
- Authentication Service
- SaaS CRM

---

## 13. Role

Human or system actor.

**Examples:**
- System Administrator
- Security Analyst
- End User
- DevOps Engineer

---

## 14. Data Entity

Structured information object.

**Examples:**
- User Account
- Log File
- Database Record
- Access Token

---

## 15. Event

Something that occurs.

**Examples:**
- Login Attempt
- Security Incident
- System Failure
- Deployment

---

# Minimal Version (If You Want Simpler)

If you want ultra-clean structure (Version 1.0 minimal):

1. Concept  
2. Technology  
3. Product  
4. Component  
5. Protocol  
6. Standard  
7. Framework  
8. Process  
9. Policy  
10. Control  

That is enough for most IT knowledge systems.

---

# Important Rule

Every node must have:

- Exactly one primary Entity Type  
- Optional secondary tags  

**Example:**

Firmware  
Primary Type: Component  
Secondary Tag: Software  

LAN  
Primary Type: Technology  
Secondary Tag: Network

---

# Why This Matters

If you skip this discipline, your system becomes:

- Inconsistent  
- Hard to query  
- Impossible to graph correctly  
- Mixed abstraction levels  

With proper entity typing, you can:

- Query: "Show all Protocols"  
- Query: "Show all Products that implement a Standard"  
- Query: "Show all Controls related to Access"

