# 🥘 PAN Analyzer for Cook++

## Project Title
**Cook++: A Mini Programming Language for Cooking Recipes**  
**Tool:** PAN Analyzer (Parser and Syntax Checker)  
**Language Used:** Python  

---

## Overview
Cook++ is a domain-specific programming language designed to represent cooking instructions in a structured and programmable way.  
The **PAN Analyzer** serves as the syntax analyzer that validates Cook++ programs, ensuring that each statement follows the language’s grammar rules.

**Input:** A Cook++ source code file (`.cook` or `.txt`)  
**Output:** A message indicating whether the syntax is valid or showing detailed error messages with line numbers.

---

## How to Run the Analyzer

### Step 1: Open the Notebook
Open the file `syntax_analyzer_v3.ipynb` in **Jupyter Notebook** or **Google Colab**.

### Step 2: Run All Cells
Execute all code cells in order.  
If the analyzer initializes successfully, you will see a message like:  
> Server running... PAN Analyzer is ready.

### Step 3: Test Your Cook++ Program
Enter your Cook++ code into the analyzer input field, or modify the provided sample program.

#### Example Input:
```cook
procedure lutongUlam(sangkap) {
    chop sangkap;
    fry sangkap 10;
    mix;
    return;
}

lutongUlam(gulay);
serve;
```

---

## Sample Test Programs

You may test using these examples:

- **test1_basic.cook** → Simple cooking actions  
- **test2_procedure.cook** → Procedure and function call  
- **test3_ifelse.cook** → Conditional statements  
- **test4_loop.cook** → Loop structures  
- **test5_combined.cook** → Full recipe with variables, loops, and conditionals  

Each test covers one or more grammar features.

---

## 👨‍🍳 Roles of Members 

| Member | Role | Responsibilities |
|---------|------|------------------|
| Bernabe, Jan Allen | Project Lead / Documentation Head | Led the team by assigning tasks and managing timelines, oversaw project development progress, prepared and formatted the design documentation, and ensured the completeness of deliverables. |
| Labasan, Jessa Mae | System Developer / Analyzer Implementer | Developed the full PAN Analyzer program, implemented the lexer, parser, and syntax validation logic, and conducted debugging and testing to ensure analyzer accuracy and stability. |
| Tiu, Christian Harold | Concept Designer / Grammar Architect | Originated the core concept of Cook++, designed the BNF grammar structure, formulated the language use cases, and defined the syntax and semantics of the language. |

---

## Acknowledgment

Developed for the **Programming Languages** course — Final Project.  
**Instructor:** Ms. Armida P. Salazar  
**Institution:** National University  
**Semester:** S.Y. 2025 - 2026
"""
