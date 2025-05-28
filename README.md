# 🎫 osTicket Lab – Ticket Lifecycle Simulation

This lab is the final step in the osTicket lab series, simulating a full help desk workflow from ticket creation to resolution. You'll act as both the **end user** and the **IT help desk analyst**, assigning SLAs, working across departments, and understanding real-world escalation logic.


---

## LAB OBJECTIVES

- Create and observe tickets from both the end-user and agent perspectives
- Apply SLAs and assign departments and teams
- Complete tickets through resolution
- Simulate role-based access and escalation
- Understand real-world ticket intake workflows

---

For lab purposes we will delete the "Maintanence" department to default tickets to the "Support" department


## 🧑‍💻 End-to-End Ticket Scenarios

### Scenario 1: Mobile Banking Outage
A customer submitted a high-priority ticket reporting that the entire mobile and online banking system was inaccessible to all users. John, a help desk agent, immediately reviewed the ticket details, confirming its urgency and potential business impact. 

**End User:**  
> "Entire mobile/online banking system is down."
<img width="1180" alt="image" src="https://github.com/user-attachments/assets/dd1afb5f-5e73-4697-b689-81310e6c6bfe" />



**Agent (John):**  
- View ticket details  
  - Priority  
  - Department  
  - SLA  
  - Assigned To
<img width="1312" alt="image" src="https://github.com/user-attachments/assets/ca687e02-41c4-4a8d-b24f-24acc23bd83b" />

- Set properties:  
  - SLA: `Sev-A (1hr, 24/7)`  
  - Department: `Online Banking`
  - Update Help Topic
<img width="969" alt="image" src="https://github.com/user-attachments/assets/9928e50e-a750-4475-964a-533ca01eb0b2" />

**Conclusion**
He set the SLA to Sev-A (1hr, 24/7) and assigned the ticket to the Online Banking department for immediate escalation. The issue was promptly triaged to ensure minimal downtime and customer disruption. Does not have access to ticket anymore.
<img width="1015" alt="image" src="https://github.com/user-attachments/assets/0c0d988c-7100-45b7-8fba-af591bc7ee94" />



---

### Scenario 2: Adobe Upgrade Request
An end user from the accounting department submitted a request stating that their Adobe software was no longer working and needed an upgrade. 

**End User:**  
> "Accounting department needs Adobe upgrade, broken."
<img width="1015" alt="image" src="https://github.com/user-attachments/assets/d9703a10-34c0-4ffb-ac90-408d9ebd0a95" />


**Agent (John):**  
- Set properties:  
  - SLA: `Sev-B (4hr, 24/7)`  
  - Department: `Support`  
- Work the ticket to completion

**Conclusion**
John, a support agent, reviewed the ticket and assigned it to the Support department with a Sev-B (4hr, 24/7) SLA to ensure timely resolution. He coordinated with the user to verify system compatibility, completed the upgrade, and confirmed the software was functioning as expected. The ticket was then resolved and closed with documentation for future reference.

<img width="987" alt="image" src="https://github.com/user-attachments/assets/8bf9b49b-1fd3-46cb-bec1-85602907678b" />


---

### Scenario 3: CFO Laptop Issue
A critical ticket was submitted by the CFO’s assistant reporting that the CFO’s laptop would no longer power on. 


**End User:**  
> "CFO’s laptop will no longer turn on."

**Agent (John):**  
- Set properties:  
  - SLA: `Sev-B (4hr, 24/7)`  
  - Department: `Support`  
- Work the ticket to completion

**Conclusion**
John, the support agent, triaged the issue and immediately assigned it a Sev-B (4hr, 24/7) SLA due to its urgency, routing it to the Support department. After troubleshooting, he identified a hardware fault and provided a loaner laptop while arranging for repairs. The ticket was documented, resolved, and closed within the SLA window.


---



