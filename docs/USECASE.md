# Usecase Diagram

![](Usecase_diagram.png)

## 1. Actors

### 1.1 Human Actors

- **User**  
  A generalized actor representing all human users of the system.

- **Technician**  
  Logs into the system, views assigned maintenance tickets, updates ticket status, and performs maintenance activities.

- **System Administrator**  
  Manages user access, registers technicians, manages machines, views alerts, and creates or updates maintenance tickets to ensure smooth system operation.

---

### 1.2 External System Actors

- **System (Automated Monitoring Service)**  
  Periodically monitors machine health and automatically generates alerts and maintenance tickets if a machine behaves abnormally, without any human intervention.