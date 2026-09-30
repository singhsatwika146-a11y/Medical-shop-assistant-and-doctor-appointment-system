# Medical-shop-assistant-and-doctor-appointment-system

A Python-based console application designed to demonstrate a simple **medicine-shop management and healthcare assistance system**.

The project combines patient registration, symptom-based general information, medicine information, doctor details, appointment booking, medicine inventory, billing, and first-aid information in one menu-driven application.

> **Disclaimer:** This is an educational project. It does not diagnose diseases or prescribe medicines. The information provided is general in nature. For serious or persistent symptoms, users should consult a qualified healthcare professional.

---

## 📌 Project Overview

The **Medicine Shop Assistant & Doctor Appointment System** is a Python mini project developed using basic programming concepts such as:

* Variables
* Lists
* Dictionaries
* Functions
* Loops
* Conditional statements
* String handling
* Exception handling
* User input
* Menu-driven programming

The application begins by registering a patient and then provides a menu through which different healthcare-related functions can be accessed.

---

## ✨ Features

### 1. Patient Registration

The system collects basic patient information including:

* Patient name
* Age
* Gender
* Phone number
* Address
* Blood group
* Emergency contact

Age validation is also included to prevent invalid age values.

### 2. Patient Details

Registered patient information can be displayed whenever required.

### 3. Symptom Checking

Users can enter symptoms such as:

* Fever
* Cough
* Cold
* Headache
* Stomach pain
* Leg pain
* Body pain
* Sore throat
* Acidity
* Indigestion
* Diarrhea
* Vomiting
* Allergy
* Skin itching
* Minor cut
* Minor burn
* Muscle pain

The program searches its predefined condition database and displays general information and supportive measures.

### 4. Severe Case Detection

The program checks entered symptoms against a predefined list of severe symptoms.

Examples include:

* Chest pain
* Difficulty breathing
* Severe bleeding
* Unconsciousness
* Seizure
* Stroke
* Severe abdominal pain
* Very high fever
* Severe headache
* Face swelling
* Blood vomiting
* Black stool
* Serious injury

If a severe symptom is detected, the system advises the user to seek urgent medical evaluation.

### 5. Medicine Information

The project contains a predefined medicine/supportive-measure database for several common conditions.

For example, fever-related information includes paracetamol and ORS, while minor cuts include antiseptic products and sterile dressing.

### 6. Condition Search

Users can directly search for a condition and receive:

* General information
* Related products
* Supportive measures

### 7. Doctor Information

The system contains a predefined list of doctors with:

* Doctor name
* Speciality
* Phone number
* Available time
* Available days

### 8. Doctor Appointment

Users can select a doctor and enter an appointment date.

The system then displays an appointment confirmation containing the patient and doctor details.

### 9. Medicine Categories

The program displays categories such as:

* Pain and fever relief
* Cold and cough products
* Digestive health products
* Allergy products
* Oral rehydration products
* First-aid products
* Skin-care products
* Throat-care products

### 10. First-Aid Information

The application provides basic information for:

* Minor cuts
* Minor burns
* Fever
* Dehydration
* Serious injuries

### 11. Medicine Inventory

The system maintains an inventory containing:

* Medicine name
* Price
* Available stock

### 12. Medicine Billing

Users can select medicines and quantities to create a bill.

The program:

1. Checks whether the medicine exists.
2. Checks whether sufficient stock is available.
3. Calculates the item total.
4. Reduces the available stock.
5. Calculates the final bill amount.

### 13. Patient Summary

A summary of the registered patient can be displayed at the end or during the session.

---

## 🛠️ Technologies Used

| Technology             | Purpose                                   |
| ---------------------- | ----------------------------------------- |
| Python                 | Main programming language                 |
| Dictionaries           | Store medicines, conditions and inventory |
| Lists                  | Store doctors, symptoms and categories    |
| Functions              | Divide the program into modules           |
| Loops                  | Menu handling and repeated input          |
| Conditional Statements | Decision making                           |
| Exception Handling     | Input validation                          |
| String Handling        | Symptom searching and matching            |

---

## 📂 Project Structure

```text
Medicine-Shop-Assistant/
│
├── Pasted code.py
└── README.md
```

You can rename `Pasted code.py` to something cleaner before uploading, for example:

```text
medicine_shop_assistant.py
```

---

## ▶️ How to Run

### Step 1: Install Python

Install Python 3.x on your computer.

### Step 2: Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### Step 3: Open the project folder

```bash
cd Medicine-Shop-Assistant
```

### Step 4: Run the program

```bash
python "medicine_shop_assistant.py"
```

On some systems you may need:

```bash
python3 medicine_shop_assistant.py
```

---

## 🖥️ Program Flow

```text
START
  │
  ▼
Patient Registration
  │
  ▼
Main Menu
  │
  ├── Check Symptoms
  │      │
  │      ├── Severe Symptom?
  │      │       ├── Yes → Urgent Medical Evaluation
  │      │       └── No  → General Information
  │      │
  │      └── Display Supportive Measures
  │
  ├── Search Condition
  │
  ├── View Patient Details
  │
  ├── View Common Conditions
  │
  ├── Medicine Categories
  │
  ├── First-Aid Information
  │
  ├── View Doctors
  │
  ├── Book Doctor Appointment
  │
  ├── View Medicine Inventory
  │
  ├── Create Medicine Bill
  │
  ├── Patient Summary
  │
  ├── About Project
  │
  └── Exit
  │
  ▼
END
```

---

## ⚠️ Limitations

This project is intended for educational purposes and has several limitations:

* It is a console-based application.
* It does not use a real medical database.
* Patient information is not permanently stored.
* Doctor appointments are not connected to a real hospital system.
* Inventory is maintained only during the current program session.
* Symptom matching is based on predefined keywords.
* It does not provide medical diagnosis.
* It does not generate personalized prescriptions.
* It does not connect to pharmacies or healthcare professionals.

---

## 🚀 Future Improvements

The project can be expanded by adding:

* Graphical User Interface (GUI)
* MySQL or SQLite database
* Secure patient login
* Doctor login
* Admin dashboard
* Permanent patient records
* Appointment cancellation and rescheduling
* Real-time medicine stock management
* Medicine expiry-date tracking
* Prescription upload
* Search and filter functionality
* Online appointment system
* Email/SMS appointment notifications
* Improved symptom analysis
* Authentication and authorization
* Report generation
* Web-based interface

---

## 🎓 Educational Purpose

This project demonstrates how fundamental Python programming concepts can be combined to create a practical menu-driven application.

It is particularly useful for understanding:

* Data structures
* Functions
* Program flow
* Input validation
* Searching
* Inventory management
* Basic billing systems
* Modular programming

---

## 📄 License

This project is created for educational and academic purposes.

