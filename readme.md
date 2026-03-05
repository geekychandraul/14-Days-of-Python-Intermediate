# 🚀 14 Days of Python Intermediate

Welcome to **Phase 2** of your Python journey!

If you have conquered the basics (Variables, Loops, Functions), this course is designed to turn you into a **Professional Developer**. Here, we move away from simple scripts and start building real-world applications, working with files, APIs, and Object-Oriented Programming (OOP).

> **Pre-requisite:** You must have completed [14-Days-of-Python-Basics](https://github.com/YOUR-USERNAME/14-Days-of-Python-Basics) or have equivalent knowledge.

---

## 📂 Repository Structure
This repository is organized to help you code along and check your work.

```text
14-Days-of-Python-Intermediate/
│
├── 01_Project_ATM_Controller.ipynb    <-- Start Here (Daily Lessons)
├── 02_List_Comprehensions.ipynb
├── ...
│
├── 📂 resources/                      <-- Support files (CSVs, TXTs, Images)
│   ├── data.csv
│   └── config.json
│
├── 📂 solutions/                      <-- Stuck? Find answers here
│   ├── 01_solution_atm.py
│   └── ...
│
└── README.md

```

---

## 📅 The Intermediate Syllabus

### Week 1: Professional Python 💼

*Writing efficient, clean, and modular code.*

| Day | Topic | What You Will Learn |
| --- | --- | --- |
| **01** | [List Comprehensions](https://www.google.com/search?q=./02_List_Comprehensions.ipynb) | Writing "Pythonic" one-liners. |
| **02** | [Modules & PIP](https://www.google.com/search?q=./06_Modules_and_PIP.ipynb) | Installing libraries, Virtual Environments, Imports. |
| **03** | [File Handling](https://www.google.com/search?q=./03_File_Handling_Read_Write.ipynb) | Reading & Writing `.txt` files (Persistent Storage). |
| **04** | [Data Formats](https://www.google.com/search?q=./04_Handling_JSON_and_CSV.ipynb) | Working with real data (`.csv` and `.json`). |
| **05** | [Functional Python](https://www.google.com/search?q=./05_Lambda_Map_Filter.ipynb) | Anonymous functions (`lambda`) and `map/filter`. |
| **06** | [Dates & Automation](https://www.google.com/search?q=./07_DateTime_and_OS.ipynb) | Automating file tasks, Timestamps, `os` module. |
| **07** | [Debugging & Handling Errors](https://www.google.com/search?q=./07_DateTime_and_OS.ipynb) | raise Exception, assert, Debugging tips. |

### Week 2: Object-Oriented Programming & The Web 🌐

*Building the engines that power modern software.*

| Day | Topic | What You Will Learn |
| --- | --- | --- |
| **08** | [OOP Part 1](https://www.google.com/search?q=./08_OOP_Classes_and_Objects.ipynb) | The Blueprint: Classes, Objects, `__init__`, `self`. |
| **09** | [OOP Part 2](https://www.google.com/search?q=./09_OOP_Inheritance.ipynb) | Parent/Child classes, Super(), Overriding methods. |
| **10** | [OOP Part 3](https://www.google.com/search?q=./10_OOP_Advanced_Dunder.ipynb) | Magic Methods (`__str__`, `__len__`) & Operator Overloading. |
| **11** | [APIs & Requests](https://www.google.com/search?q=./11_APIs_and_Requests.ipynb) | Fetching live data from the internet (Weather/Crypto). |
| **12** | [Web Scraping](https://www.google.com/search?q=./12_Web_Scraping_BeautifulSoup.ipynb) | Extracting data from websites using HTML parsing. |
| **13** | [Generators](https://www.google.com/search?q=./13_Generators_and_Yield.ipynb) | Advanced memory management with `yield`. |
| **14** | [Final Capstone](https://www.google.com/search?q=./14_Final_Project_Weather_App.ipynb) | **The Big Finish:** Build a live Weather App using OOP & APIs. |

to be added
type hinting
decorators on day5
sorting using sorted in session 13 with generators

New flow:
Modules & PIP| Installing libraries, Virtual Environments, Imports. |
File Handling| Reading & Writing `.txt` files (Persistent Storage). |
Working with CSV and JSON | Working with real data (`.csv` and `.json`). |
Dates & Automation| Automating file tasks, Timestamps, `os`, shutil & Pathlib module. |
Functional Python and Generators | Advanced memory management with `yield`. |
List, dict, tuple, set Comprehensions| Writing "Pythonic" one-liners. |
Debugging & Handling Errors| raise Exception, assert, Debugging tips. |

decorators and type hinting
OOP Part 1 | The Blueprint: Classes, Objects, `__init__`, `self`. |
OOP Part 2 | Parent/Child classes, Super(), Overriding methods. |
OOP Part 3 | Magic Methods (`__str__`, `__len__`) & Operator Overloading. |
APIs & Requests | Fetching live data from the internet (Weather/Crypto). |
Web Scraping | Extracting data from websites using HTML parsing. |
multithreading and multiprocessing and oncurrent.futures


---

## 🛠️ How to Use the `resources` Folder

Some lessons (like Day 03 and Day 04) require external files to read data from.

* We have placed all necessary files in the `resources/` folder.
* In your code, you will access them like this:
```python
with open("resources/sample.txt", "r") as file:
    content = file.read()

```



## 🕵️ Stuck? Check `solutions`

Every daily notebook contains 5 Levels of Activities.

* Try to solve them yourself first!
* If you get stuck, open the corresponding file in the `solutions/` folder to see the answer key.

---

## 🚀 What's Next?

Completing this course means you are no longer a beginner. You are a **Python Developer**.
From here, you can specialize in:

* **Web Development:** Django or FastAPI
* **Data Science:** Pandas & NumPy
* **AI/ML:** PyTorch or TensorFlow

**Happy Coding! 🐍**
