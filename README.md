# Advanced Spreadsheet Application

This project implements a web-based spreadsheet application that mimics the core functionalities and user interface of Google Sheets. It provides a dynamic and interactive spreadsheet environment with features for data entry, manipulation, and analysis.

## Features

**Core Spreadsheet Features:**

* Spreadsheet Interface:
    * Mimics Google Sheets UI with a familiar grid layout, toolbar, and formula bar.
    * Drag-and-drop functionality for cell content and formulas.
    * Accurate cell dependencies and updates.
    * Basic cell formatting (bold, italics).
    * Adding, deleting, and resizing rows and columns.
* Mathematical Functions:
    * `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`
* Data Quality Functions:
    * `TRIM`, `UPPER`, `LOWER`
* Data Entry and Validation:
    * Supports various data types (numbers, text, dates).
    * Basic data validation checks.

**Advanced Features:**

* Toolbar:
    * Buttons for adding rows/columns, removing duplicates, find and replace, and applying bold/italic formatting.
* Resize Handles:
    * Interactive resize handles for adjusting row and column dimensions.
* Find and Replace:
    * Functionality to find and replace specific text within the spreadsheet.

## Technologies Used

* HTML: Structures the web page and the spreadsheet grid.
* CSS: Styles the appearance of the spreadsheet and its elements.
* JavaScript: Implements the spreadsheet's logic, including:
    * Dynamic table creation.
    * Data storage and manipulation.
    * Formula evaluation.
    * Event handling for user interactions.

## Data Structures

* `data` Object: A JavaScript object used to store the cell data. Keys are cell IDs (e.g., "A1"), and values are the cell contents.
* `selectedCells` Array: Stores the IDs of the currently selected cells.

## How to Run

1.  Save the code as an HTML file (e.g., `spreadsheet.html`).
2.  Open the HTML file in a web browser.

## Usage

* Data Entry: Click on a cell to enter data or formulas.
* Formulas: Use the "=" sign to start a formula (e.g., `=SUM(A1:A5)`).
* Cell Selection: Click to select a single cell, or Shift-click to select a range.
* Drag-and-Drop: Drag and drop cell content to move it.
* Toolbar: Use the toolbar buttons for additional functions.
* Resize: Drag the resize handles to adjust row and column sizes.

## Future Enhancements

* Implement additional mathematical and data quality functions.
* Add support for more complex formulas and cell referencing.
* Allow users to save and load their spreadsheets.
* Incorporate data visualization capabilities (charts, graphs).
* Improve data validation and error handling.
