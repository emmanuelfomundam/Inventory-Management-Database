# ITS DTS Inventory Management Database

## Situation:
The ITS Department lacked a centralized, digital inventory system to monitor the movement and availability of devices like laptops, desktops, network equipment, and peripherals. Relying on manual records led to inefficiencies, miscounts, and difficulty during audits.

## Task:
Design and develop a reliable inventory management solution using Microsoft Access that could:
- Store detailed inventory data (serial numbers, device types, statuses, locations)
- Track check-in/check-out history
- Generate reports (inventory summaries, item histories, availability reports)
- Be accessible by authorized personnel with role-based restrictions

## Action:
- Created relational database schema with tables for devices, categories, users, transactions, and status logs.
- Designed user-friendly Access forms for:
  - Item registration and modification
  - Issuance and return workflows
  - Report generation
- Implemented queries and macros for efficient filtering, validation, and reporting
- Added automated calculations for stock balances and due items
- Documented all forms, relationships, and user guides

## Result:
- Reduced inventory mismanagement incidents by over 70%
- Auditing process time cut in half
- Used by multiple ITS staff members with no technical background
- Modular design allows future integration with Power BI or external APIs

---

## 💻 How to Use

1. Open `ITS_DTS_Inventory.accdb` with Microsoft Access
2. Use the main navigation form to register new inventory or manage transactions
3. Navigate to the **Reports** section to generate predefined inventory reports
