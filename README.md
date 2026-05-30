# 🛡️ XSS Labs — Cross-Site Scripting Practice Environment

A hands-on collection of **9 XSS challenges** designed to help developers and security enthusiasts understand, identify, and exploit Cross-Site Scripting vulnerabilities in a safe, controlled environment.

---

## 📋 Overview

This project covers three core XSS attack vectors across three difficulty levels:

| Type | Description |
|------|-------------|
| **Reflected XSS** | User input is immediately reflected back in the server response |
| **DOM-Based XSS** | Vulnerability exists entirely in client-side JavaScript |
| **Filter Bypass** | Techniques to evade common input sanitization mechanisms |

---

## 🗂️ Labs

### 🟢 Easy
| # | Lab | Type |
|---|-----|------|
| 1 | Reflected XSS — Basics | Reflected |
| 2 | Reflected XSS — Template Literal | Reflected |
| 3 | DOM-Based XSS | DOM |

### 🟡 Medium
| # | Lab | Type |
|---|-----|------|
| 4 | Filter Bypass — Tags | Bypass |
| 5 | DOM XSS in `document.write` | DOM |
| 6 | Reflected XSS with HTML Tag Filtering | Reflected |

### 🔴 Hard
| # | Lab | Type |
|---|-----|------|
| 7 | Reflected XSS in a JavaScript URL with some characters blocked | Reflected |
| 8 | Reflected XSS into `href` attribute with angle brackets HTML-encoded | href |
| 9 | SVG & Script Injection | SVG |

---

## 🎯 Learning Objectives

By completing these labs, you will:
- Understand how Reflected, DOM-Based, and Stored XSS vulnerabilities arise
- Learn to bypass common input filters and HTML sanitizers
- Gain familiarity with injection via HTML attributes, `href`, `document.write`, and SVG
- Build intuition for secure coding patterns that prevent XSS

---

## ⚠️ Disclaimer

This project is intended **strictly for educational purposes**.  
All labs are self-contained and must only be used in a local or authorized environment.  
Do not use these techniques against systems you do not own or have explicit permission to test.

---

## 🚀 Getting Started

https://the0x-pwn.github.io/lab-xss/



