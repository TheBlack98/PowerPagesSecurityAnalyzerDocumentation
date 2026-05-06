# Power Pages Security Analyzer

<img src="./icon.svg" alt="Logo" width="120" />

Power Pages Security Analyzer is an XrmToolBox plugin designed to help you **understand, visualize, and analyze the security configuration of your Power Pages environment**.

---

## 🚀 What this tool does

This tool helps you analyze and visualize:

- Web Roles
- Table Permissions
- Parent / Child permission chains
- Web API exposure (Site Settings)
- Security risks and misconfigurations

It provides both:
- 📊 A **dashboard view** (counts, risk levels)
- 🔗 An **interactive graph** (relationships between roles, permissions, tables)

---

## 🧭 Getting started

### 1. Open the tool

- Open XrmToolBox
- Launch **Power Pages Security Analyzer**

---

### 2. Connect to your environment

- Select your Dataverse environment
- The tool will automatically detect available Power Pages sites

---

### 3. Select a site

- Choose the Power Pages site you want to analyze
- Click **Start analysis**

---

### 4. Wait for analysis

The tool will:
- Load components (Web Roles, Table Permissions, Site Settings)
- Parse relationships
- Analyze risks
- Build the graph and dashboard

---

### 5. Explore the results

You will see:

#### 📊 Dashboard
- Total roles
- Total permissions
- Total tables
- Risk breakdown (Critical / High / Warning / Neutral)

#### 🔗 Graph view
- Nodes:
  - Roles
  - Table Permissions
  - Tables
  - Web API exposure
- Edges:
  - Role → Permission
  - Permission → Table
  - Parent → Child permissions

---

## 🎯 Interacting with the graph

You can:

- Click on a **role, permission, or table**
- The graph will:
  - Highlight related elements
  - Fade unrelated elements
- See detailed information in the **bottom-right panel**

---

## ⚙️ Filters

You can filter the graph:

- Show only risky elements
- Show only critical risks
- Filter by:
  - Roles
  - Tables
  - Permissions

---

## 🎨 Layout options

You can change how the graph is displayed:

- Hierarchy
- Organic
- Circle
- Grid
- Risk-focused layout

---

## ⚠️ Important behaviors

### Changing environment

If you switch the Dataverse organization:
- The current analysis becomes invalid
- The tool will reset automatically after a short delay

---

### No connection

If no connection is active:
- The tool will guide you to connect first
- No crash will occur

---

## 🔐 Risk detection

The tool identifies potential issues such as:

- Anonymous access with global permissions
- Write / Create / Delete on global scope
- Missing parent relationships
- Overly permissive configurations
- Web API exposure with broad field access

---

## 🧠 Why this tool

Power Pages security can become complex quickly:

- Multiple roles
- Nested permissions
- Implicit relationships

This tool helps you:
- **Visualize complexity**
- **Detect risks faster**
- **Understand security structure instantly**

---

## 📌 Requirements

- XrmToolBox
- Access to a Dataverse environment
- Power Pages configured

---

## 🛠️ Feedback & contributions

If you find issues or have ideas:

👉 Open an issue on GitHub  
👉 Suggest improvements  
👉 Contribute to the project

---

## 📄 License

This project is licensed under the MIT License.
