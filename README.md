# Instagram Profile Text Parser (Python)

This project parses raw Instagram profile text data and converts it into structured Python dictionaries.

## Problem
Raw scraped Instagram profile data is unstructured, inconsistent, and contains missing fields.
Direct indexing often causes runtime errors.

## Solution
- Split profiles using blank lines
- Split profile content into lines
- Use defensive length checks
- Safely extract fields
- Skip malformed profiles

## Technologies Used
- Python 3
- String parsing
- List slicing
- Defensive programming

## Output Fields
- username
- number of posts
- followers
- following
- name
- page type
- bio

## Learning Outcome
This project demonstrates real-world text parsing, error handling, and data cleaning in Python.
