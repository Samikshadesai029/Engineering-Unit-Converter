# Engineering Unit Converter (Java)

## 📌 Project Overview
A Java Command Line Interface (CLI) application developed to perform high-precision unit conversions for engineering applications. This tool focuses on units commonly used in Mechanical and Thermal Engineering.

## ⚙️ Technical Features
* *Precision Handling:* Uses double data types and printf formatting for 4-decimal accuracy.
* *Control Logic:* Implemented switch-case structures for efficient menu navigation.
* *Mathematical Constants:* Utilizes specific conversion factors for Pascal, Horsepower, and Kelvin scales.

## 🛠️ How to Run
1. Compile: javac Converter.java
2. Run: java Converter
   
## 🧪 Quality Assurance (QA) & Testing
To ensure engineering-grade accuracy, the following test cases were performed using the system's logic:

| Test Case | Input Category | Input Value | Expected Result |
| :--- | :--- | :--- | :--- |
| T1 | Pressure (Pa) | 100,000 | 14.5038 PSI |
| T2 | Power (Watts) | 745.7 | 1.00 hp |
| T3 | Temperature (C)| 25 | 298.15 K |

*Testing Methodology:* Accuracy was verified against standard physical constants. Precision is maintained up to 4 decimal places for Pressure calculations.
## 🤖 Future AI Integration
Planned features include using Natural Language Processing (NLP) to allow users to type "Convert 50 Pascals to PSI" directly, rather than using a menu system, improving user efficiency.
