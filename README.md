# Group Travel Expense Simplification Engine

A software engineering lab project for simplifying group travel expense management through expense recording, currency conversion, balance calculation, and optimal debt settlement.

## Problem Statement

Group travel expenses are often difficult to manage when multiple travelers pay for different expenses, use different currencies, and need to settle their balances efficiently.

The Group Travel Expense Simplification Engine provides a structured approach to recording expenses, converting currencies, calculating individual balances, and generating an optimized debt settlement plan.

## Project Objectives

- Record expenses incurred during group travel.
- Support expenses in different currencies.
- Convert foreign-currency expenses using applicable exchange rates.
- Calculate the net balance of each traveler.
- Compute an optimized debt settlement plan.
- Provide travelers and administrators with a clear settlement plan.

## Actors

- **Group Traveler** – Records expenses, views balances, and reviews settlement plans.
- **Trip Admin** – Manages and reviews group expenses, balances, and settlement information.
- **Daily Exchange Rate Service** – Provides applicable daily exchange rates for currency conversion.

## Use Cases

| Use Case ID | Use Case |
|---|---|
| UC-01 | Record Expense |
| UC-02 | Convert Currency |
| UC-03 | Calculate Traveler Balances |
| UC-04 | Compute Optimal Debt Settlement |
| UC-05 | View Settlement Plan |

## Use Case Relationships

- UC-01 **includes** UC-02
- UC-04 **includes** UC-03
- UC-05 **extends** UC-04

## Project Deliverables

1. Requirements Table
2. UML Use Case Diagram
3. Use Case Flow Specification

## Repository Contents

- `Requirements_Table.pdf` – Requirements specification
- `Use_Case_Diagram.pdf` – UML use case diagram
- `Use_Case_Flow.pdf` – Detailed use case flow specification

## Domain

**Retail, E-Commerce & Finance**

## Course

**Software Engineering Lab – Lab 1**

## Author

**Vismaya Harish**  
**SRN: PES2UG24CS598**  
**Class: 5J**
