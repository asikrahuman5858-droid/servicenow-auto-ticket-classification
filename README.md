# Auto Ticket Classification Using Flow Designer in ServiceNow

## 📌 Project Overview

The Auto Ticket Classification System automates incident classification and assignment using ServiceNow Flow Designer. It classifies tickets based on predefined conditions and routes them to the appropriate support groups, reducing manual work and improving incident management efficiency.

## 🎯 Objectives

- Automate incident ticket classification.
- Assign tickets to the appropriate support groups.
- Reduce manual effort and classification errors.
- Improve incident management efficiency.
- Streamline IT service management workflows.

## 🛠️ Technologies Used

- ServiceNow
- Flow Designer
- Incident Management
- Incident Table (`incident`)
- Conditional Logic and Update Record Actions

## ⚙️ Project Workflow

1. A user creates an incident ticket in ServiceNow.
2. Flow Designer triggers when a new incident record is created.
3. The flow evaluates the incident description and relevant fields.
4. Predefined conditions determine the ticket category.
5. The incident category and assignment group are updated.
6. The ticket is routed to the appropriate support team.
7. Unmatched tickets can be sent for manual review.

## 🔄 Flow Designer Implementation

### Trigger
- Trigger Type: Record Created
- Table: Incident (`incident`)

### Sample Classification Rules

| Incident Type | Category | Assignment Group |
|---|---|---|
| Password reset | Inquiry / Help | IT Support |
| Network issue | Network | Network Support |
| Laptop issue | Hardware | Hardware Support |
| Software issue | Software | Application Support |
| Unknown issue | Manual Review | Service Desk |

*Note: Configure the categories and assignment groups according to your ServiceNow instance.*

### Actions
- If / Else conditions
- Update Record
- Set incident category and subcategory
- Assign the appropriate support group
- Handle unmatched tickets

## 👥 Team Members

| S. No. | Name | Role |
|---|---|---|
| 1 | Syed Asik Rahuman A | Team Leader |
| 2 | Mohamed Safwan M | Team Member |
| 3 | Yaseen Kader | Team Member |
| 4 | Abdul Rahub Nistar | Team Member |
| 5 | Ams Jasum | Team Member |

## 🧪 Testing

| Test Case | Expected Result |
|---|---|
| Password reset ticket | Assigned to IT Support |
| Network connectivity ticket | Assigned to Network Support |
| Hardware-related ticket | Assigned to Hardware Support |
| Software-related ticket | Assigned to Application Support |
| Unmatched ticket | Sent for manual review |

## ✅ Expected Outcomes

- Automatic incident classification
- Faster ticket assignment
- Reduced manual intervention
- Improved routing consistency
- More efficient incident management

## 🔮 Future Enhancements

- AI-based ticket classification
- Natural Language Processing (NLP)
- Automated knowledge base recommendations
- Classification accuracy dashboards
- Integration with additional ITSM workflows

## 📌 Conclusion

The Auto Ticket Classification Using Flow Designer in ServiceNow project demonstrates how workflow automation can simplify incident management. By applying predefined conditions and automated record updates, the system classifies incidents and routes them to the appropriate support teams, improving efficiency and reducing manual work.

## 📄 Project Details

- **Project Title:** Auto Ticket Classification Using Flow Designer in ServiceNow
- **Platform:** ServiceNow
- **Domain:** IT Service Management (ITSM)
- **Project Type:** Workflow Automation
- **Team Size:** 5 Members
- **Team Leader:** Syed Asik Rahuman A
