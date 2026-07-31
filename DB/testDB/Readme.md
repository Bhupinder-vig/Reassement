# Test Database

## Overview

This repository contains a sample MySQL database that can be used for testing database applications and server setups.

The database is designed to provide a large amount of realistic test data, allowing developers to test queries, database performance, and application functionality.

## Database Information

The original dataset was created by researchers at Siemens Corporate Research and later converted into a relational database format for MySQL usage.

The database contains:

* Approximately 300,000 employee records
* Over 2.8 million salary records
* Multiple related tables for testing database relationships and queries

The dataset is large enough to provide meaningful testing while still being suitable for development environments.

## Requirements

To use this database, the following are required:

* MySQL Server 5.0 or above
* A database user with permissions to create, modify, and access tables

Required permissions include:

* SELECT
* INSERT
* UPDATE
* DELETE
* CREATE
* DROP
* ALTER
* INDEX
* CREATE VIEW
* LOCK TABLES

## Installation

To install the database:

1. Download or clone the repository.
2. Open a terminal in the project directory.
3. Import the SQL file into MySQL using:

```bash
mysql < employees.sql
```

For the partitioned database version, use:

```bash
mysql < employees_partitioned.sql
```

## Testing the Database

After installation, the database can be tested using the provided test scripts.

Run:

```bash
mysql -t < test_employees_md5.sql
```

or:

```bash
mysql -t < test_employees_sha.sql
```

These tests compare the installed database against expected results to ensure that all tables and records have been imported correctly.

## Database Contents

The database includes several related tables, including:

* Employees
* Departments
* Department Managers
* Department Employees
* Titles
* Salaries

These tables allow testing of database relationships, queries, and reporting features.

## Notes

The dataset was generated for testing purposes. Some inconsistencies may exist within the data, which can be useful for practising database validation and data-cleaning techniques.

## License

This database is distributed under the Creative Commons Attribution-Share Alike 3.0 Unported License.
