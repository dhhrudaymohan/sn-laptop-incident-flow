# ServiceNow – Laptop Issue Incident Flow

This project builds a ServiceNow Flow that triggers when users submit a catalog item to report laptop issues. It automatically creates an incident, populates fields, and emails the caller.

## 🔧 What It Does
- Auto-creates an Incident record from a Catalog Item
- Populates Caller, Assignment Group, Priority
- Sends email with the Incident Number

## 📦 Files
- `LaptopIncidentFlow.xml`: ServiceNow Update Set to import into any instance

## 📥 Installation
1. Go to **System Update Sets → Retrieved Update Sets**
2. Import this XML file
3. Preview & Commit
4. Test with “Report Laptop Issue” catalog item

---

MIT License

