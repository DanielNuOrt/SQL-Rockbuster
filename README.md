# Rockbuster Stealth — PostgreSQL analysis

A SQL analysis project based on the fictional Rockbuster Stealth movie-rental business scenario. The exercise explores rental activity, revenue and customer geography to support decisions around a proposed online rental service.

## Business questions

The original brief asks questions including:

- Which films contribute most and least to revenue?
- What is the average rental duration?
- Where are customers located?
- Where are customers with higher lifetime value based?
- Do sales vary across geographic regions?

## Work represented in this repository

The current repository contains:

- SQL query files covering rental summaries, rental duration and revenue calculations, including aggregation by film rating.
- A review of inconsistencies identified in the rental table.
- An Excel analysis workbook.
- The Rockbuster data dictionary in PDF format.

The query files currently have descriptive filenames without `.sql` extensions. The repository also includes the analysis workbook and data dictionary; the source database itself is not bundled here.

## Tools and techniques

- PostgreSQL
- SQL joins and aggregations
- Date/time interval analysis with `EXTRACT(EPOCH FROM ...)`
- Descriptive statistics and revenue summaries
- Data-quality review

## Presentation

[Rockbuster Stealth — Tableau story](https://public.tableau.com/app/profile/daniel7968/viz/RockbusterStealthLLCProject/Story1)

## Dataset

The project uses the sample DVD rental database distributed for PostgreSQL learning and analysis. The scenario is fictional and should not be interpreted as commercial work for a real rental company.

## Project context

This is an earlier analytical portfolio project. It demonstrates foundational SQL and business-analysis work; it is not intended to represent the scope of my more recent data engineering projects.
