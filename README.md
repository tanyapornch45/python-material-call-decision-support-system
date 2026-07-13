# Material Call Decision Support System

## Overview

This project is a simple decision support system developed in Python for material call planning in a semiconductor supply chain.

The main purpose of this project is to help planners check material availability and suggest the next action based on stock, open purchase orders, and SLOC priority. Instead of checking multiple Excel files manually, the program combines the information and provides a recommendation automatically.

This project was developed as part of my Python and Pandas learning journey.

---

## Features

- Check material availability from current stock
- Calculate remaining shortage quantity
- Check Open PO information
- Allocate stock based on SLOC priority
- Generate a simple transfer plan
- Provide recommendation for each material

Example recommendations:

- Transfer Stock
- Wait for Open PO
- Call Material
- Push ETA

---

## Workflow

Input Excel Files

↓

Read Data with Pandas

↓

Material Availability Check

↓

Open PO Analysis

↓

SLOC Priority Allocation

↓

Generate Recommendation

↓

Output Report

---

## Technologies

- Python
- Pandas
- Microsoft Excel
- Jupyter Notebook

---

## Input Files

The system uses four worksheets.

- Shortage
- Stock
- Open_PO
- SLOC_PRIORITY

---

## Output

The output report includes:

- Material
- Required Quantity
- Available Stock
- Remaining Quantity
- Recommendation
- Transfer Plan

---

## Future Improvements

Some features can be added in the future, such as:

- Demand forecasting
- Safety stock calculation
- Dashboard visualization
- AI-based recommendation
- Automatic report generation

---

## Author

This project was created as a practice project to improve my Python and data analysis skills, while applying them to a real supply chain planning scenario.

