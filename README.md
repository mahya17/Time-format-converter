# Time Format Converter

## About
A Python program that converts working hours from the 12-hour format (AM/PM) to the 24-hour format. It supports times with or without minutes and validates the input format.

## How It Works
- Accepts a time range in one of the supported formats, such as `9 AM to 5 PM` or `9:30 AM to 5:30 PM`.
- Converts each time to the 24-hour format.
- Preserves the minutes when they are provided.
- Raises a `ValueError` if the input format is invalid or a time is out of range.
- Supports working hours that cross midnight.

## Example

**Input:**
```text
Hours: 9:00 AM to 5:00 PM
```

**Output:**
```text
09:00 to 17:00
```

## What I Practiced
- String processing
- Regular expressions
- Input validation
- Exception handling
- Writing tests with `pytest`

## Technologies
- Python
- `re`
- `pytest`

## Course
Harvard CS50's Introduction to Programming with Python (CS50P).
