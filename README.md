# Applying Regex to Parse Clinical Reports

An advanced Python Regex project for extracting structured information from realistic and messy clinical reports.

## Project Overview

Clinical reports usually contain information in unstructured text. This project uses Python Regular Expressions to identify and extract important clinical fields and convert them into structured data.

The parser was tested on multiple reports with different formatting styles, including variations in `:` and `=` separators.

## Features

* Extract patient name, MRN, age, and sex
* Extract vital signs
* Extract laboratory results with values and units
* Extract diagnosis information
* Extract medication name, dose, and frequency
* Handle different text formatting styles
* Use advanced Regex techniques
* Parse multiple clinical reports
* Convert extracted data into a Pandas DataFrame
* Validate missing and complete fields

## Regex Concepts Used

* Named Groups
* Alternation
* Positive Lookahead
* Positive Lookbehind
* Flexible separators
* `re.search()`
* `re.finditer()`
* Reusable Regex patterns

## Extracted Clinical Information

| Category   | Fields                                                    |
| ---------- | --------------------------------------------------------- |
| Patient    | Name, MRN, Age, Sex                                       |
| Vitals     | Blood Pressure, Heart Rate, Temperature, Respiratory Rate |
| Laboratory | Glucose, HbA1c, Cholesterol                               |
| Assessment | Diagnosis                                                 |
| Medication | Name, Dose, Frequency                                     |

## Project Workflow

1. Created realistic clinical reports.
2. Extracted basic patient information.
3. Used named groups for structured extraction.
4. Extracted vital signs.
5. Extracted laboratory results using `finditer()`.
6. Applied alternation for multiple clinical terms.
7. Practiced lookahead and lookbehind.
8. Extracted diagnosis and medication information.
9. Built a reusable clinical report parser.
10. Tested the parser with messy formatting.
11. Parsed multiple reports.
12. Converted the results into a Pandas DataFrame.
13. Performed final validation.

## Validation

The final parser was tested on 2 clinical reports.

* Total records: **2**
* Complete records: **2**
* Missing required fields: **0**

## Technologies

* Python
* Regular Expressions (`re`)
* Pandas
* Google Colab

## Project Structure

```text
clinical-report-regex-parser/
│
├── Applying_Regex_to_Parse_Clinical_Reports.ipynb
├── README.md
└── requirements.txt
```

## Learning Outcomes

Through this project, I practiced how to:

* Work with realistic unstructured clinical text
* Design Regex patterns for different data formats
* Use advanced Regex features
* Build reusable text parsers
* Handle formatting variations
* Convert unstructured text into structured records
* Validate extracted data before further processing

## Note

This project is for learning and text-processing practice. It is not intended for clinical diagnosis or medical decision-making.
