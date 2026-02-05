#### SQL Command Languages (For Data Engineers) #########
Structured Query Language (SQL) commands are categorized based on their functionality. Below are the most commonly used SQL command types with clear explanations.

### `Table Management — DDL (Data Definition Language)` #########
**Purpose:** DDL commands define and manage database structures such as tables and schemas.

### `CREATE TABLE`
**Purpose:** Creates a new table in the database.

### `DROP TABLE`
**Purpose:** Permanently deletes a table and its data.

### `ALTER TABLE`
**Purpose:** Modifies an existing table structure (add/remove columns, change data types).

### `TRUNCATE TABLE`
**Purpose:** Removes all records from a table quickly without logging individual row deletions.

### `RENAME TABLE`
**Purpose:** Renames an existing table.

### `Data Manipulation — DML (Data Manipulation Language)` #########
**Purpose:** DML commands are used to insert, update, and delete data inside tables.

### `INSERT`
**Purpose:** Adds new records into a table.

### `UPDATE`
**Purpose:** Modifies existing records in a table.

### `DELETE`
**Purpose:** Removes specific records from a table.

### `MERGE`
**Purpose:** Inserts or updates records based on a matching condition (UPSERT logic).

### `Data Querying — DQL (Data Query Language)` #########
**Purpose:** DQL commands are used to retrieve and analyze data.

### `SELECT`
**Purpose:** Retrieves data from one or more tables.

### `DISTINCT`
**Purpose:** Removes duplicate rows from query results.

### `WHERE`
**Purpose:** Filters rows based on conditions.

### `ORDER BY`
**Purpose:** Sorts query results in ascending or descending order.

### `GROUP BY`
**Purpose:** Groups rows for aggregation (COUNT, SUM, AVG, etc.).

### `LIMIT / TOP / FETCH`
**Purpose:** Restricts the number of rows returned.

### `OFFSET`
**Purpose:** Skips a specified number of rows (used for pagination).


### `Access Control — DCL (Data Control Language)` #########
**Purpose:** DCL commands manage user permissions and security.

### `GRANT`
**Purpose:** Gives specific permissions to users or roles

### `REVOKE`
**Purpose:** Removes previously granted permissions.


### `Transactions — TCL (Transaction Control Language)` #########
**Purpose:** TCL commands manage database transactions and ensure data consistency.


### `BEGIN / START TRANSACTION`
**Purpose:** Starts a new transaction.


### `COMMIT`
**Purpose:** Saves all changes made during the transaction.


### `ROLLBACK`
**Purpose:** Undoes changes made in the current transaction.


### `SAVEPOINT`
**Purpose:** Creates a checkpoint to roll back part of a transaction.


