# supply_chain_data_cleaning (Excel)
Data cleaning and validation of raw shipment data, ensuring consistency, completeness, uniqueness, and analytical readiness.

## Data Source:
This dataset was generated using AI for educational purposes, specifically to demonstrate data cleaning and preparation techniques.

## Overview
This repository contains a supply chain dataset and a complete data cleaning workflow performed using Microsoft Excel.
The dataset reflects common real-world data quality issues and is intended to demonstrate practical data preparation skills.

## Dataset Description
The dataset consists of **10,000 rows and 12 columns**.
It includes shipment, supplier, product, warehouse, cost, quantity, lead time, and date-related information.
The raw data contains inconsistencies in text formatting, duplicated business identifiers, invalid numeric values, and mixed date formats.

## Data Cleaning Scope
- The cleaning process focuses on:
- Defining the correct grain of the dataset
- Preserving raw data while creating cleaned columns
- Standardizing text fields
- Flagging and validating numeric values
- Converting date values stored as text into usable date formats
- Documenting all data quality issues and decisions

## Key Concepts Applied
- Dataset grain and line-level identification
- Use of surrogate keys
- Flag-first approach for numeric data
- Mapping tables for text standardization
- Quality checks and validation using Pivot Tables

## Tools Used
- Microsoft Excel
- Excel formulas (TRIM, CLEAN, PROPER, XLOOKUP, IF, ISNUMBER, SUBSTITUTE)
- Pivot Tables for validation
  
## Repository Contents
- Raw dataset
- Cleaned dataset
- Data Dictionary
- Data Issue Log
- Mapping table
- Data Cleaning Validation

## Purpose
The purpose of this repository is to showcase a clear, structured, and professional approach to cleaning supply chain data using Excel, following best practices commonly used in real data analyst roles.
