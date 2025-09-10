# 💊 MyPharmacy – Bash Project

## 📝 Introduction
**MyPharmacy** is a command-line pharmacy system built using **Bash scripting** under **COMP311 (Linux OS Lab)** and **COMP438 (UNIX OS)**.  
The program allows pharmacists to organize medications, search drug records, and handle prescriptions directly through a terminal interface.  

This project highlights:
- Modular shell scripting techniques  
- Reliable file operations in Linux  
- Robust validation for user inputs  
- A simplified model of pharmacy workflows  

---

## 🔑 Core Functionalities
### ➕ Add New Drug
- Enforces a **unique 4-digit identifier**.  
- Captures scientific and trade names with character rules.  
- Stores price, manufacturing date, and quantity.  
- Automatically calculates expiration date (+547 days).  

### ✏️ Edit or Remove Drug
- Delete a drug using its ID.  
- Update details (except ID & expiration date).  
- If manufacturing date changes, expiration updates as well.  

### 🔍 Drug Search
- Lookup by **ID** → full details.  
- Lookup by **name** → partial/full match, sorted by trade name.  
- Sort by **expiration date** → latest to oldest.  
- Sort by **quantity** → smallest to largest.  

### 💊 Prescription Module
- Identify a drug by ID or trade name.  
- Confirm stock availability before dispensing.  
- Reduce inventory after dispensing.  
- Keep dispensing until user enters `stop`.  
- Display **total bill** for dispensed drugs.  

---

## 🚀 Usage Guide
1. Download or clone the repository:
   ```bash
   git clone https://github.com/username/myPharmacy.git
   cd myPharmacy

---

## ⚙️ Tools & Environment

- Bash (GNU Shell)

- Linux/UNIX platform

- Flat text storage (drugs.txt)
