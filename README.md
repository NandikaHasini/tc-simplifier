
# 📋 T&C Simplifier

**T&C Simplifier** is a client-side web application that helps users quickly understand complex **Terms & Conditions** by automatically detecting important clauses and presenting them in **plain English**, using a **clear color-coded risk system**.

Instead of reading long legal documents, users get an instant breakdown of **safe**, **caution**, and **risky** clauses.

---

## 🚀 Features

* 🔍 **Automatic Clause Detection** using rule-based pattern matching
* 🎨 **Color-Coded Risk Levels**

  * 🟢 Safe / User-friendly
  * 🟡 Caution / Read carefully
  * 🔴 Risky / Concerning
* 🧠 **Plain-English Explanations** for each detected clause
* 📊 **Clause Statistics Dashboard** (Risky / Caution / Safe counts)
* 🧩 Supports:

  * Numbered lists
  * Paragraphs
  * Full Terms & Conditions pages
* ⚡ **Runs 100% in the browser** (No backend, no data storage)

---

## 🛠️ Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling & responsive UI
* **Vanilla JavaScript** – Rule engine, analysis logic, and DOM updates

No frameworks. No libraries. No external dependencies.

---

## 🧪 How It Works

1. User pastes Terms & Conditions text into the input box
2. The text is split into logical segments (sentences, numbered clauses)
3. A **rule engine** scans the content using predefined regex patterns
4. Matching clauses are:

   * Classified as 🟢 Safe, 🟡 Caution, or 🔴 Risky
   * Simplified into easy-to-understand language
5. Results are displayed with:

   * Verdict summary
   * Clause count statistics
   * Individual clause cards

---

## 🎯 Use Cases

* 👩‍💻 Everyday users checking app or website policies
* 🧑‍⚖️ Legal-tech awareness & education
* 🎓 Students learning about digital rights and privacy
* 🏆 Hackathons & demos focused on transparency and user safety

---

## 📂 Project Structure

```
T&C-Simplifier/
│
├── index.html    # Complete application (HTML + CSS + JS)
└── README.md     # Project documentation
```
