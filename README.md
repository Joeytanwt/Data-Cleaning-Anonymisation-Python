# Data Cleaning & Anonymisation with python

## Overview
This project demonstrates data cleaning and anonymisation using python for a synthetic customer dataset containing sensitive identifiers (e.g., NRIC, personal names, and birth dates).

## Steps
* Consolidates multi-source tables with inconsistent columns (e.g., Member_Name vs Given/Family vs First/Last) into a unified schema.
* Cleans outliers and placeholders (e.g., Purchases and Amount Spent with 9999 sentinels; zero-amount edge cases) with targeted rules.
* Applies hashing to produce Hashed_NRIC and Hashed_Name fields for anonymity.

## Outputs
* Clean, anonymized table
* Look up table for decrypting hashed values.
