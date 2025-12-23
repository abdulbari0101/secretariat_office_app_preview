

# 📦 Parcel Manager
**Enterprise Logistics Management System**

Cross-Platform Mobile Application built with **Flutter**

---

## 📌 Project Overview
**Parcel Manager** is a full-featured enterprise logistics and parcel management system designed and developed from the ground up.  
The application streamlines parcel handling, delivery tracking, financial accounting, and reporting for logistics offices.

The system follows a **modular, scalable architecture** with clean separation of concerns, making it suitable for real-world enterprise use cases.

---
# Screens
<img width="2607" height="1848" alt="App_Screens" src="https://github.com/user-attachments/assets/0177fc92-db82-48df-ad21-b3c777705edf" />

# Files of project
<img width="453" height="875" alt="image" src="https://github.com/user-attachments/assets/98de56ca-3356-4112-96b7-ceb488aff201" />

---

## 🏗️ Architecture & Design
- **Architecture Pattern:** Modular + Controller-based architecture
- **State Management:** GetX (Reactive Controllers, Bindings, Routing)
- **Platform Support:** Android & iOS
- **Localization:** Full RTL Arabic support

The project emphasizes maintainability, scalability, and performance by applying SOLID principles and defensive coding practices.

---

## ⚙️ Technical Stack
- **Framework:** Flutter 3.x  
- **Language:** Dart 3.9  
- **State Management:** GetX  
- **Database:** SQLite (sqflite)  
- **PDF Engine:** pdf + printing packages  
- **Native Integration:** Android Platform Channels (Kotlin)  
- **UI:** Responsive layout with flutter_screenutil  
- **Localization:** bidi + arabic_tools  

---

## 🗄️ Database & Persistence Layer
- SQLite persistence with:
  - Schema versioning and migration support (`onUpgrade`)
  - Hierarchical data modeling (Chart of Accounts with parent–child relationships)
  - Complex JOIN queries for reporting and transaction retrieval
- Automatic daily backup using JSON serialization
- Restore functionality for disaster recovery

---

## 💼 Business Logic & Financial Engine
- Complete **consignment lifecycle management**
- Integrated **double-entry bookkeeping system**, including:
  - Journal entries
  - Receipt and payment vouchers
  - Opening balances
  - Hierarchical chart of accounts
- Accurate financial reporting aligned with accounting principles

---

## 📄 PDF & Reporting System
- Custom-built PDF generation engine
- Supports:
  - RTL Arabic text rendering
  - Multi-page financial statements
  - Vouchers and detailed reports
  - Embedded Arabic fonts (Cairo, Amiri)
- Optimized for printing and sharing official documents

---

## 📲 Platform & Device Integration
- Native Android integration using **MethodChannel**
- Features include:
  - Dual-SIM SMS support
  - Background SMS handling
  - Delivery status callbacks
- Contact picker integration with phone number extraction and validation
- Image capture and cropping for delivery confirmation and ID verification

---

## 🧩 Data Modeling
- 8+ Dart models using:
  - Factory constructors
  - JSON serialization
  - Asynchronous data hydration
  - Computed properties
- Repository pattern for clean data access abstraction

---

## 📊 Codebase Metrics
- 138+ Dart files across controllers, models, views, and services
- 18 controllers managing distinct business domains
- 1,384 lines in database service layer
- 898 lines in PDF report generation service
- 15+ screens with modular routing

---

## 🔑 Key Engineering Decisions
- Repository pattern for data abstraction
- Single-responsibility controllers (SOLID principles)
- Reusable widget library for UI consistency
- Defensive coding with full null safety
- Clear separation between UI, business logic, and data layers

---

## 🚀 Use Cases
- Parcel offices and logistics centers
- Delivery and consignment tracking
- Financial accounting for logistics operations
- Generating official receipts, vouchers, and reports

---


