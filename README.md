# DDL & DML Exercises

This repository contains SQL exercises demonstrating Data Definition Language (DDL) and Data Manipulation Language (DML) operations.

## INSTRUCTOR Table Operations

### Table Structure
The `INSTRUCTOR` table has the following schema:
- `ins_id` INTEGER (Primary Key, Not Null)
- `lastname` VARCHAR(15) (Not Null)
- `firstname` VARCHAR(15) (Not Null)
- `city` VARCHAR(15)
- `country` CHAR(2)

### SQL Operations Included

#### DDL (Data Definition Language)
- **Create Table**: Creates the INSTRUCTOR table structure
- **Drop Table**: Removes the existing table (if any) before creation

#### DML (Data Manipulation Language)
- **INSERT**: Adds new records to the table
  - Single row insertion for Rav Ahuja
  - Multiple rows insertion for Raul Chong and Hima Vasudevan
- **SELECT**: Retrieves data from the table
  - Select all columns
  - Select specific columns with WHERE clause
- **UPDATE**: Modifies existing data (changes city for Rav)
- **DELETE**: Removes specific records (deletes Raul Chong)

### Sample Data
Initial data after insertion:
| ins_id | lastname  | firstname | city    | country |
|--------|-----------|-----------|---------|---------|
| 1      | Ahuja     | Rav       | Toronto | CA      |
| 2      | Chong     | Raul      | Toronto | CA      |
| 3      | Vasudevan | Hima      | Chicago | US      |

### Usage
Run the SQL commands in sequence to see how each DDL and DML operation affects the database table.

## Technologies
- SQL
- Database Management Systems

<img width="200" height="200" alt="Upwork" src="https://github.com/user-attachments/assets/d067e215-eb8f-4d4b-a153-bc4aa76ce221" />

