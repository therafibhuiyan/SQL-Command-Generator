# SQL Command Generator

## Overview

The SQL Command Generator is a web application that allows users to dynamically generate SQL commands for creating tables in a database. It simplifies the process of creating tables by providing a user-friendly interface for defining table names, database names, and custom columns.

## Features

- **Easy-to-Use Interface:** Simple and intuitive UI for entering table and database names, as well as adding custom columns.

- **Dynamic Column Types:** Users can select from various data types (INT, VARCHAR, TEXT, DATE, DATETIME, FLOAT, DOUBLE, BOOLEAN) for their custom columns.

- **Automatic Default Columns:** The application automatically includes default columns (id, created_at, updated_at) in the generated SQL commands. These default columns are included only once.

- **SQL Command Preview:** Users can preview the generated SQL commands before using them in their database.

## How to Use

1. Enter the desired table name and database name.
2. Add custom columns using the "Add Column" button.
3. Specify the column name and choose the data type from the dropdown.
4. Optionally, remove columns using the "Remove Column" button.
5. Click the "Generate SQL Commands" button to generate the SQL commands.
6. Copy and use the generated SQL commands in your database.

## Getting Started

To run the SQL Command Generator locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sql-command-generator.git

