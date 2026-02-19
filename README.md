# NexERP Frontend
<img width="1882" height="867" alt="화면 캡처 2026-01-19 195138" src="https://github.com/user-attachments/assets/98020c8e-733a-444c-9a48-10e46db4855b" />

## 💡 Intoduction

- NexERP is an Enterprise Resource Planning (ERP) solution targeted at Small and Medium-sized Enterprises (SMEs), providing integrated resource management and data analytics.


## 👀 Service Walkthrough
### 🏢 Company Registration
<video src="https://github.com/user-attachments/assets/15255fda-3f61-4eb0-86e6-741c7dc02fba" autoplay loop muted playsinline width="100%"></video>
- The first step with NexERP! 🚀 Register a new company and log in with the generated administrator account.
---
### 🧑‍💻 Employee Registration
<video src="https://github.com/user-attachments/assets/1bd71207-38d2-4b93-ae98-b83a79d54f05" autoplay loop muted playsinline width="100%"></video>
- Enter basic info like name and ID, then select the company, department, and position to complete the sign-up request.
---
### 🤝 Employee Approval
<video src="https://github.com/user-attachments/assets/e85e75b7-7378-427b-ad7d-76e13fadd3fa" autoplay loop muted playsinline width="100%"></video>
- A new team member has requested to join 📩. The administrator checks the request list on the management page and selects Approve or Reject.
---
### 🎯 Create a Project
<video src="https://github.com/user-attachments/assets/1d9eb662-3c55-49d7-b6be-faee7cf53a14" autoplay loop muted playsinline width="100%"></video>
- The admin enters project information and assigns personnel responsible for receiving and shipping.
---
### 📝 Receiving Task Management
<video src="https://github.com/user-attachments/assets/02991fbf-4632-4a54-b747-23130035eb7e" autoplay loop muted playsinline width="100%"></video>
- Receiving managers use the "My Tasks" toggle to easily check assigned duties.
- Enter task details (name and description), add new inventory or select existing stock, input the target receiving quantity, and send an approval request.
---
### 📝 Shipping Task Management
<video src="https://github.com/user-attachments/assets/4b70f989-957f-43de-adc5-bdcee24bf2b6" autoplay loop muted playsinline width="100%"></video>
- Shipping managers also use the toggle to view their tasks.
- Enter task name, description, transportation method, and carrier.
- Click Add Inventory to register required stock, enter the target shipping quantity, and send an approval request to finish.
---
### 🖱️ Admin Approval (Receiving/Shipping)
<video src="https://github.com/user-attachments/assets/0a1efb49-2492-40fe-a729-ecf1f1e7d9c3" autoplay loop muted playsinline width="100%"></video>
- Admins review approval requests sent by managers and finalize the process with a single click. Boost efficiency with a fast and simple approval process.
---
### 📦 Receiving Process
<video src="https://github.com/user-attachments/assets/c8c2171b-c442-4703-a492-c497f78f36b8" autoplay loop muted playsinline width="100%"></video>
- Select the item to receive, enter the quantity, and click the 'Process Receiving' button.
- The task is complete once the current receiving quantity matches the target quantity.
---
### 🚚 Shipping Process
<video src="https://github.com/user-attachments/assets/3196e399-8b58-4fa7-b638-b880e7486e6c" autoplay loop muted playsinline width="100%"></video>
- Select the item to ship, enter the quantity, and click the 'Process Shipping' button.
- Shipping is finalized when the current shipping quantity meets the target quantity.
---
### 🏆 Completed Projects
<video src="https://github.com/user-attachments/assets/8524b914-7c0c-4714-ad46-30d9fe0d04ec" autoplay loop muted playsinline width="100%"></video>
- iew all completed projects at a glance from the admin home and project lists.
- Use filters to easily search by status: In Progress, Not Started, or Completed.
---
### 📊 Inventory Management
<video src="https://github.com/user-attachments/assets/9957cdd1-adb2-4785-8388-0b702cf3698f" autoplay loop muted playsinline width="100%"></video>
- Select items from the list to update target inventory and safety stock levels.
---

## 🛠 Getting Started
Follow these steps to run the project in your local environment.

```bash
// 1. Clone Repository
git clone https://github.com/TAVE-9RP/NexERP_FE.git
cd NexERP_FE

// 2. Install Dependencies
npm install

// 3. Run Local Server
npm run dev

```

## 🏗 Tech Stack

### 🎨 Frontend

- **Framework**: React
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: TanStack Query (React Query)
- **HTTP Client**: Axios
- **Data Visualization**: Recharts, Ant Design Charts

### 🛠 Tools

- **Build Tool**: Vite
- **Package Manager**: npm

## 🚀 Core Features

NexERP provides three primary modules for efficient enterprise operations.

### 🏢 Management Service (Admin)

- Employee Approval: Owner reviews and approves new employee registrations.
- Access Control: Owner-centric user access control and organizational management.

### 📦 Inventory Service

- Receiving Management: Register quantities and detailed item info for new stock.
- Real-time Inventory Status: View current assets at a glance and adjust stock levels efficiently.

### 🚚 Logistics Service

- Shipping Workflow: Manage shipment status based on orders and requests.
- Logistics Tracking: Efficiently manage the flow of goods from receiving to shipping.

### 📈 Integrated KPI Dashboard

- Completion Rate & Lead Time: Monitor progress and efficiency based on accumulated data from previous months.
- Safety Stock Rate: Check stock levels to prevent out-of-stock scenarios.
- Inventory Turnover & Forecast: Predict future inventory needs based on daily accumulated data.

## 📂 Key File Structure

```
src
 ┣ 📂apis     
 ┣ 📂components 
 ┃ ┣ 📂common    
 ┃ ┣ 📂dashboard 
 ┃ ┣ 📂modals   
 ┃ ┗ 📂signup  
 ┣ 📂pages     
 ┃ ┣ 📂inventory-service   
 ┃ ┣ 📂logistics-service   
 ┃ ┣ 📂management-service  
 ┃ ┗ 📂login & 📂signup   
 ┣ 📂types   
 ┣ 📂utils 
 ┣ 📂styles  
 ┣ 📜App.tsx
 ┗ 📜main.tsx
```

## 👥 Team Members

|    Name    |  Role  |
| :--------: | :----: |
| **Park Haeun** |   FE   |
| **Chaeyeon Kwak** | FE, BE |
