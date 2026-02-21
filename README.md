# 🌐 Selenium WebDriver — Complete Training Course

A comprehensive, **19-day training course** covering every major feature of **Selenium WebDriver** with Java. From basic locators to advanced topics like Shadow DOM, JavaScriptExecutor, and cross-browser configuration.

---

## 📖 Overview

This repository is a hands-on Selenium WebDriver training organized by days, covering 60+ automation concepts with practical Java examples. Each day introduces new topics, building a complete skill set for web automation testing.

---

## 📚 Topics Covered

| Day | Topics |
|-----|--------|
| **Day 1** | First Test Case, Browser Setup |
| **Day 2** | Locators (ID, Name, Class, Tag, Link Text) |
| **Day 3** | CSS Selectors |
| **Day 4** | XPath Fundamentals |
| **Day 5** | XPath Axes (Parent, Child, Sibling, Ancestor) |
| **Day 6** | Browser Methods, Get Methods, Conditional Methods |
| **Day 7** | Waits — Implicit, Explicit, Fluent, Page Load, Sleep |
| **Day 8** | Browser Windows, Navigational Commands |
| **Day 9** | Checkboxes, Dropdowns (with/without Select tag) |
| **Day 10** | Alerts, Frames, Authenticated Popups |
| **Day 11** | Dropdowns — Select, Hidden, Bootstrap, Auto-Suggest |
| **Day 12** | Static Tables |
| **Day 13** | Dynamic Pagination Tables |
| **Day 14** | Date Pickers |
| **Day 15** | Actions — Mouse Hover, Right Click, Double Click, Drag & Drop |
| **Day 16** | Keyboard Actions, Tabs & Windows, Sliders |
| **Day 17** | JavaScriptExecutor, File Upload, Scrolling, Zoom |
| **Day 18** | Chrome Options — Headless, Incognito, SSL, Screenshots, Ad Blocking, Extensions |
| **Day 19** | Broken Links, Shadow DOM, SVG Elements |

---

## 📂 Project Structure

```
SeleniumWebDriver/
├── pom.xml
├── src/test/java/
│   ├── day_1/ to day_19/              # Progressive training modules
│   ├── assignment/                     # Dropdown assignment
│   ├── assignment2/                    # Tables & dynamic content
│   ├── assignment3/                    # E2E ticket booking
│   └── assignment4/                    # Drag & Drop practice
└── target/                            # Compiled test classes
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Java** | Programming language |
| **Selenium WebDriver** | Browser automation |
| **TestNG** | Test runner |
| **Maven** | Build & dependency management |
| **ChromeDriver** | Chrome browser driver |

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 11+
- Maven 3.x
- Chrome browser installed
- Any IDE (IntelliJ IDEA / Eclipse)

### Installation
```bash
git clone https://github.com/Shubham00117/SeleniumWebDriver.git
cd SeleniumWebDriver
mvn clean install
```

### Running Tests
```bash
mvn test -Dtest=day_2.LocatorsDemo
```

---

## 📜 License

This project is open source and available for educational purposes.
