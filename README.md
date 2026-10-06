# HeapOfStudent

# Heap Of Students

## Description

Program used to manage student records.

The system uses data normalization by separating data into:

1. Student
2. Address
3. Date

Each student owns one Address object and two Date objects.

## Classes

### Address

Stores:

- street
- city
- state
- zip

Can print a formatted address.

### Date

Stores:

- month
- day
- year

Can parse a date string in the format:

mm/dd/yyyy

Can print dates in a friendly format:

January 27, 1997

### Student

Stores:

- first name
- last name
- Address
- birth date
- graduation date
- credit hours

Can print a complete student record.

## Algorithms

### Date::init()

Input:

01/27/1997

Algorithm:

1. Split string using '/'
2. Convert first token to month
3. Convert second token to day
4. Convert third token to year
5. Store values

### Student::init()

Input:

CSV line

Algorithm:

1. Split line at commas
2. Extract fields
3. Store first and last name
4. Initialize Address object
5. Initialize birth Date
6. Initialize graduation Date
7. Convert credits to integer
``
