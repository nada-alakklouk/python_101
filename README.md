# 📞 Telephone Directory Application

A lightweight and interactive Telephone Directory CLI application built with Python. Developed as a course project with the **Satar (سطر) Platform**, this tool simulates a smart phonebook system capable of storing database records, validating input integrity using Regular Expressions (Regex), and handling user requests dynamically through structured logic.

---

## 📂 Project Assets & Structure

* 💻 **[View Core Code Notebook](./main.ipynb)** – Interactive Jupyter Notebook containing the full Python dictionary data, functional loops, and the validation pipeline.
* 📋 **Project Framework:** Built to satisfy real-world program requirements including rigorous phone number format checking and structural search behaviors.

---

## 🛠️ Tech Stack & Key Concepts

* **Programming Language:** Python 🐍
* **Data Structures:** **Dictionaries (`dict`)** utilized as an in-memory key-value database mapping unique phone numbers to user names.
* **Input Validation Engine:** **Regex (`re` module)** implemented to sanitize user inputs, ensuring phone strings contain no alpha-characters or illegal punctuation symbols.
* **Functional Programming:** Modular design using isolated functions (`search_number`, `add_phone`, `search_name`) to control software states and scalability.

---

## 🚀 Application Features & Logic Flow

The system presents an interactive terminal menu supporting three foundational operational scopes:

1. **Search by Phone Number (`search_number`):** * Prompts the user for a 10-digit number.
   * Runs conditional validations: Checks length equality to 10 and triggers a regex sweep (`[^(0-9)]`) to deny foreign string patterns.
   * Queries the database to retrieve the owner's name or safely prints a "Not Found" exception.
2. **Add New Contact (`add_phone`):**
   * Allows dynamic directory expansions.
   * Ensures data integrity by blocking duplicate number insertions and enforcing formatting compliance before committing the key-value pair to memory.
3. **Search by Name (`search_name`):**
   * *Extended Capability:* Scans the dictionary's value ecosystem to instantly check if a target user name exists within the directory registry.

---

## 👤 Developed by:
* **Nada Alaklook**
* 🔗 [Connect with me on LinkedIn](https://linkedin.com/in/nada-alaklook-725049252)
