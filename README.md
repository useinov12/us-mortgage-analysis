## Project Goals

This project explores the U.S. mortgage landscape from 2008 to 2022, focusing on three key questions: (1) What percentage of households have a mortgage, and what share of their income goes toward mortgage payments? (2) How does house availability differ across housing types (single-family vs. multi-family)? (3) What is the effect of interest rate changes on mortgage affordability and house values? By answering these questions, the project aims to provide insights into the financial burden of housing in the U.S.

## Data Description

This analysis uses data from **IPUMS USA** and **FRED**, covering the period from 2008 to 2022:

- **IPUMS USA Household Survey**: Provides data on household income (`HHINCOME`), mortgage payments (`MORTAMT1`), and mortgage status (`MORTGAGE`).
- **FRED 30-Year Fixed Mortgage Rate** (`MORTGAGE30US`): Historical mortgage interest rates for the U.S.
- **FRED Median Sales Price of Houses** (`MSPUS`): Median sales prices for homes in the U.S.
- **FRED New Housing Starts** (`HOUST`): Data on the number of new housing units being built.

Each dataset contributes to understanding how mortgage costs, income allocation, and housing availability have evolved over the analysis period.


| Variable  | Columns | Len | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 2014 | 2015 | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2022 |
|-----------|---------|-----|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|
| YEAR      | H 1-4   | 4   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| SAMPLE    | H 5-10  | 6   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| SERIAL    | H 11-18 | 8   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| CBSERIAL  | H 19-31 | 13  |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| HHWT      | H 32-41 | 10  |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| CLUSTER   | H 42-54 | 13  |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| STRATA    | H 55-66 | 12  |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| GQ        | H 67    | 1   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| OWNERSHP  | H 68    | 1   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| OWNERSHPD | H 69-70 | 2   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| MORTGAGE  | H 71    | 1   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| MORTAMT1  | H 72-76 | 5   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
| HHINCOME  | H 77-83 | 7   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |  X   |
