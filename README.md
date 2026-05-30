# 🛡️ XSS Labs — Cross-Site Scripting Training Environment

A structured, hands-on security lab designed to help developers, penetration testers, and security researchers understand and practice real-world **Cross-Site Scripting (XSS)** vulnerabilities in a safe and controlled environment.

This project simulates common insecure coding patterns found in modern web applications and provides progressively harder challenges across multiple XSS categories.

---

## 📌 Overview

This lab environment contains **10 carefully designed challenges** covering the most common XSS attack surfaces in web applications.

### 🎯 Focus Areas

* How XSS vulnerabilities are introduced in real applications
* How client-side and server-side sinks behave
* How input sanitization and filtering can be bypassed
* How context (HTML, attribute, JavaScript, SVG) affects exploitation

---

## 🧠 XSS Categories Covered

| Type                           | Description                                                                         |
| ------------------------------ | ----------------------------------------------------------------------------------- |
| **Reflected XSS**              | User input is immediately returned in the HTTP response without proper sanitization |
| **DOM-Based XSS**              | Vulnerability exists in client-side JavaScript sinks                                |
| **Filter Evasion XSS**         | Input sanitization bypass techniques targeting HTML/JS filters                      |
| **Contextual XSS**             | Injection depending on HTML attributes, JS strings, or URL contexts                 |
| **Advanced Injection Vectors** | SVG, iframe, and JavaScript URI-based injection techniques                          |

---

## 🗂️ Lab Structure

---

### 🟢 Easy Level — Fundamentals

**Focus:** Understanding basic reflection and DOM sinks

| # | Lab                                        | Type      | Concept                     |
| - | ------------------------------------------ | --------- | --------------------------- |
| 1 | Reflected XSS — Basic Input Reflection     | Reflected | Unsafe output encoding      |
| 2 | Reflected XSS — Template Literal Injection | Reflected | JavaScript template context |
| 3 | DOM XSS — location.hash Sink               | DOM       | Client-side unsafe parsing  |

---

### 🟡 Medium Level — Filtering & DOM Manipulation

**Focus:** Bypassing filters and abusing DOM sinks

| # | Lab                                       | Type      | Concept                   |
| - | ----------------------------------------- | --------- | ------------------------- |
| 4 | HTML Tag Filtering Bypass                 | Bypass    | Broken sanitization logic |
| 5 | DOM XSS — document.write Sink             | DOM       | Unsafe DOM rendering      |
| 6 | Reflected XSS with HTML Encoding Weakness | Reflected | Partial encoding bypass   |

---

### 🔴 Hard Level — Advanced Exploitation

**Focus:** Context-aware injection and restricted environments

| #  | Lab                                        | Type      | Concept                         |
| -- | ------------------------------------------ | --------- | ------------------------------- |
| 7  | JS Context XSS with Character Restrictions | Reflected | JavaScript escaping limitations |
| 8  | Attribute Context XSS (href Injection)     | Attribute | HTML attribute breaking         |
| 9  | SVG-based Script Injection                 | SVG       | Event-based execution vectors   |
| 10 | Iframe Data URI Injection                  | iframe    | sandbox & URI-based execution   |

---

## 🎯 Learning Objectives

By completing this lab series, you will gain practical experience in:

* Identifying XSS vulnerabilities in different execution contexts
* Understanding how browsers interpret HTML, JS, and DOM sinks
* Exploiting weak or broken sanitization mechanisms
* Bypassing common blacklist-based filters
* Crafting payloads for restricted environments
* Recognizing real-world insecure coding patterns

---

## ⚠️ Disclaimer

This project is strictly intended for **educational and research purposes only**.

All challenges are designed to run in a **local or explicitly authorized environment**.

Any misuse of the techniques demonstrated in these labs against unauthorized systems is strictly prohibited.

The author assumes no responsibility for improper use of this material.

---

## 🚀 Getting Started

To begin exploring the labs, visit:

👉 [https://the0x-pwn.github.io/lab-xss/](https://the0x-pwn.github.io/lab-xss/)

### Recommended Setup

* Modern web browser (Chrome / Firefox)
* Developer Tools enabled
* Basic understanding of HTML & JavaScript

---

## 🧪 Recommended Approach

* Start from **Easy → Medium → Hard**
* Inspect source code and DOM changes using DevTools
* Analyze input reflection points carefully
* Test payload variations in different contexts
* Understand *why* each payload works, not just *how*

---

## 📚 Suggested Knowledge Base

Before attempting advanced labs, it is recommended to understand:

* HTML injection basics
* JavaScript execution contexts
* DOM manipulation fundamentals
* Browser encoding behavior (HTML / URL / JS encoding)

---

## 🏁 Author Notes

This lab series was built to simulate real-world insecure patterns often found in:

* Legacy web applications
* Misconfigured sanitization libraries
* Client-side heavy frameworks with unsafe rendering logic

The goal is to build **intuition**, not just exploitation skill.

---
