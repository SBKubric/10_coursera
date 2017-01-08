# Coursera Dump
## Description
This script parses the [XML feed] (https://www.coursera.org/sitemap~www~courses.xml) of Coursera's site
and flushes the data about courses to the XML file.
## Installation
Install the packages from requirements.txt using pip:
```
pip install -r requirements.txt
```
**IMPORTANT**: best practice is to use virtualenv. See here: [Link](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
## Example
**Input:**

```python
python3 coursera.py
```

**Output:**

```
Getting courses urls...
Collecting info about courses...
Creating xlsx file...
Saved to courses.xlsx
```

For complete reference run the script with -h (--help) argument.
# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
