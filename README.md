# Python 401d1818

## Lab 17: Web Scraper

### Author:

Emily Landers

## Lab: 17

### Feature Tasks and Requirements

Scrape a Wikipedia page of your choosing and record which passages need citations.
E.g. History of Mexico has a few “citations needed”.
Your web scraper should report the number of citations needed.
Your web scraper should identify those cases AND include the relevant passage.
E.g. Citation needed for “lorem spam and impsum eggs”
Consider the “relevant passage” to be the parent element that contains the passage, often a paragraph element.

### Implementation Notes

Implementation Notes
Module must be named scraper.py
Create function named get_citations_needed_count
takes in a url string and returns an integer.
Create function named get_citations_needed_report
takes in a url string and returns a report string
the string should be formatted with each citation listed in the order found.

### User Acceptance Tests:

None