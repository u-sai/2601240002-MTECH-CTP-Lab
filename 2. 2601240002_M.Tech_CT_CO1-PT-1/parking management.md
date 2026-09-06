# Parking Management System

## Overview

The Parking Management System is a Python console application designed to manage a parking area with 100 parking slots.

The system tracks available and occupied slots, allocates slots to vehicles, validates vehicle numbers, releases slots when vehicles leave, calculates parking charges, and identifies when the parking area is full.

## Features

- Manage 100 parking slots
- Show available parking slots
- Allocate a parking slot
- Validate vehicle numbers
- Prevent the same vehicle from being parked twice
- Release a parking slot when a vehicle leaves
- Calculate parking charges
- View occupied slots
- Search for a parked vehicle
- Show complete parking status
- Identify when the parking area is full

## Requirements

- Python 3.x
- No external libraries are required

## How to Run

1. Install Python 3.x.
2. Save the program as `parking_management.py`.
3. Open a terminal or command prompt.
4. Run:

```bash
python parking_management.py
```

## Menu Options

| Option | Description |
|---|---|
| 1 | Show Available Slots |
| 2 | Allocate Parking Slot |
| 3 | Release Parking Slot |
| 4 | View Occupied Slots |
| 5 | Parking Status |
| 6 | Search Vehicle |
| 7 | Exit |

## Parking Rules

- The parking area contains 100 slots.
- Each vehicle receives the first available slot.
- A vehicle number must be valid before allocation.
- A vehicle cannot occupy more than one slot.
- When a vehicle leaves, its slot becomes available.
- Parking charges are calculated at ₹30 per hour.
- Any partial hour is charged as a full hour.
- A minimum of one hour is charged.

## Parking Charge Calculation

```text
Duration = Exit Time - Entry Time

Charged Hours = Duration rounded up to the next whole hour

Parking Charge = Charged Hours × ₹30
```

## Full Parking Detection

The system counts occupied slots.

```text
Available Slots = 100 - Occupied Slots
```

When:

```text
Occupied Slots = 100
```

the system displays:

```text
PARKING AREA FULL
```

When a vehicle leaves, its slot is released and becomes available again.

## Concepts Used

- Dictionaries
- Functions
- Loops
- Conditional statements
- User input
- Date and time handling
- Validation
- Searching
- Arithmetic calculations

## Python Module Used

The program uses Python's built-in `datetime` module to record vehicle entry and exit times.

## Project Type

**Python Console Application**

## Learning Objective

This project demonstrates how Python can be used to create a real-world parking management system using data structures, functions, validation, and time-based billing.
