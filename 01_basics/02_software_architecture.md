# 🏗️ Software Architecture Notes

## 📌 What is Architecture?

Software architecture refers to the **internal design and structure** of an application — how components are organized and how they interact with each other.

---

## 🧩 Types of Software Architecture

Software architecture can be categorized into different styles based on how components are structured and interact.

### 📌 Common Types

* Monolithic Architecture
* Microservices Architecture
* Layered (N-tier) Architecture
* Event-Driven Architecture
* Serverless Architecture

---

## 🧱 Monolithic Architecture (Overview)

A **Monolithic Architecture** is a design where all components and functionalities of an application are **combined into a single codebase**.

* Single repository
* Single deployment unit
* Backend, frontend, and database logic are tightly coupled

---

## 🔍 Key Characteristics

* All modules exist in one system
* Deployed on a single platform
* Minimal network communication (internal calls instead of APIs)
* Centralized system design

---

## 🏗️ Monolithic vs Microservices (Quick Comparison)

| Feature     | Monolithic      | Microservices           |
| ----------- | --------------- | ----------------------- |
| Codebase    | Single          | Multiple services       |
| Deployment  | Single unit     | Independent deployments |
| Scalability | Hard            | Easy (per service)      |
| Complexity  | Low (initially) | High                    |
| Flexibility | Low             | High                    |

👉 Detailed notes:

* See `../02_architecture/monolith.md`
* Microservices (to be added)

---

## 🧠 Why Architecture Matters

* Determines scalability of the system
* Impacts performance and reliability
* Affects development speed and team structure
* Influences maintainability and future changes

---

## ⚙️ Key Principles of Good Architecture

<details>
<summary>Click to expand</summary>

### ✔️ Scalability

System should handle growth in users/data

### ✔️ Maintainability

Easy to update and fix issues

### ✔️ Reliability

System should work consistently without failures

### ✔️ Performance

Efficient response time and resource usage

### ✔️ Loose Coupling

Components should be independent

</details>

---

## 💡 Interview Insight

* Start with **monolithic architecture** for simple systems
* Explain its limitations (scaling, flexibility)
* Then move to **microservices or distributed architecture**

---

## 🧠 Summary

* Software architecture defines how a system is structured
* Different architectures solve different problems
* Monolithic is simple and a good starting point
* Distributed systems add flexibility but increase complexity

---
