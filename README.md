# Power Pages Security Analyzer

A lightweight XrmToolBox plugin to analyze **Power Pages (Dataverse) security configuration**.

This tool helps identify potential risks in:

- Table Permissions  
- Web Roles  
- Parent Permission Chains  
- Web API exposure (Site Settings)  

---

## 🚀 Features

- 🔍 Analyze Table Permissions and Web Roles  
- ⚠️ Detect risky configurations (e.g. Anonymous + Global + Write)  
- 🔗 Visualize relationships between Roles → Permissions → Tables  
- 🧠 Identify broken or complex Parent chains  
- 🌐 Highlight Web API exposure per table  
- 📊 Generate structured security insights  

---

## 🧠 Why this tool?

Power Pages security setups can become complex over time due to:

- multiple Web Roles  
- nested Parent permissions  
- global access rules  
- API exposure  

This tool provides **transparency and clarity**, helping teams:

- reduce security risks  
- simplify configurations  
- understand access flows  

---

## 🏗️ Architecture

The plugin is structured into:

- **Core** → models, services, analysis logic  
- **Plugin** → XrmToolBox integration  
- **UI** → tabs and graph visualization  
- **Graph** → interactive rendering (WebView2 + Cytoscape.js)

---

## 📦 Installation (Development)

1. Clone the repository  
2. Open the solution in **Visual Studio 2022**  
3. Build the project  
4. Copy the compiled `.dll` from:
