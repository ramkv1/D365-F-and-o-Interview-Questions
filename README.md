# D365-F-and-o-Interview-Questions

## Table of Contents

| No. | Questions                                                                                                                                                           |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Difference between CONDEL, CONINS, CONLEN, etc.?](#1-difference-between-container-operations)                                                                      |
| 2   | [Difference between edit and display method?](#2-difference-between-edit-and-display-method)                                                                        |
| 3   | [Difference between perspectives and table collection?](#3-difference-between-perspectives-and-table-collection)                                                    |
| 4   | [What are the 4 types of files we need to copy to the standard folder?](#4-types-of-files-to-copy-to-the-standard-folder)                                           |
| 5   | [Why do we use virtual companies?](#5-why-use-virtual-companies)                                                                                                    |
| 6   | [How can we restrict a class to be further extended?](#6-restricting-a-class-from-extension)                                                                        |
| 7   | [Which classes are used for data import/export?](#7-classes-for-data-importexport)                                                                                  |
| 8   | [From which table can you get the user permissions stored in AX?](#8-table-storing-user-permissions-in-ax)                                                          |
| 9   | [What should we do if we need the last record to be active when a form is opened?](#9-activating-the-last-record-on-form-open)                                      |
| 10  | [What is the sequence of events while a report is generated?](#10-sequence-of-events-while-generating-a-report)                                                     |
| 11  | [Name a few X++ classes related to queries?](#11-x-classescore-classes-related-to-queries)                                                                          |
| 12  | [What is an index?](#12-what-is-an-index)                                                                                                                           |
| 13  | [Define IntelliMorph](#13-define-intellimorph)                                                                                                                      |
| 14  | [Define MorphX](#14-define-morphx)                                                                                                                                  |
| 15  | [Define X++](#15-define-x)                                                                                                                                          |
| 16  | [Differentiate between refresh(), reread(), research(), and executeQuery()](#16-difference-between-refresh-reread-research-executequery)                            |
| 17  | [Define AOT](#17-define-aot)                                                                                                                                        |
| 18  | [Define AOS](#18-define-aos)                                                                                                                                        |
| 19  | [Difference between temp table and container](#19-difference-between-temp-table-and-container)                                                                      |
| 20  | [What is an EDT, Base Enum, and how can we use array elements of an EDT?](#20-edt-base-enum-and-their-usage)                                                        |
| 21  | [Definition and use of Maps, how AddressMap is used in standard AX?](#21-maps-and-addressmap-usage-in-ax)                                                           |
| 22  | [What is the difference between Index and Index hint?](#22-difference-between-index-and-index-hint)                                                                 |
| 23  | [How many types of data validation methods are written on table level?](#23-data-validation-methods-at-the-table-level)                                             |
| 24  | [How many types of relations are available in Axapta?](#24-types-of-relations-in-axapta)                                                                            |
| 25  | [When is the recId generated, and what is its utility?](#25-utility-of-recid)                                                                                       |
| 26  | [Difference between Primary & Cluster index](#26-difference-between-primary--cluster-index)                                                                         |
| 27  | [How many kinds of lookups can be made and how?](#27-types-of-lookups)                                                                                              |
| 28  | [How many types of Delete Actions are there in Standard AX?](#28-types-of-delete-actions-in-ax)                                                                     |
| 29  | [If any record is created in a table, how do you fetch the date & time stamp?](#29-fetching-date--time-stamp-on-record-creation)                                    |
| 30  | [What is the function of super()?](#30-function-of-super)                                                                                                           |
| 31  | [Utility and use of find method](#31-utility-and-use-of-find-method)                                                                                                |
| 32  | [What are the different types of Table groups defined on table properties?](#32-types-of-table-groups)                                                              |
| 33  | [Is multiple inheritance possible in X++?](#33-handling-lack-of-multiple-inheritance)                                                                               |
| 34  | [Do we need to write a main method?](#34-necessity-of-the-main-method)                                                                                              |
| 35  | [What is the difference between new() and construct() method?](#35-difference-between-new--construct-method)                                                        |
| 36  | [What is the utility of the RunOn property?](#36-utility-of-runon-property)                                                                                         |
| 37  | [What is the main class used in batch processing?](#37-main-class-for-batch-processes)                                                                              |
| 38  | [How can we make a batch job occur at regular intervals?](#38-regular-interval-batch-jobs)                                                                          |
| 39  | [What is the main utility of classes in standard AX?](#39-main-utility-of-classes-in-standard-ax)                                                                   |
| 40  | [Which class is called when we create a SO/PO?](#40-classes-called-during-sopo-creation)                                                                            |
| 41  | [What is the basic structure of a form?](#41-basic-structure-of-a-form)                                                                                             |
| 42  | [Properties of a form datasource](#42-properties-of-a-form-datasource)                                                                                              |
| 43  | [Where should we write validateWrite() method: form DS or table level?](#43-validatewrite-in-form-datasource-vs-table-level)                                        |
| 44  | [How can we call table-level methods from form DS?](#44-calling-table-level-methods-from-form-datasource)                                                           |
| 45  | [What is the difference between form init() and DS init()?](#45-difference-between-form-init--ds-init)                                                              |
| 46  | [When a form opens, what are the sequential methods called?](#46-sequential-methods-when-opening-a-form)                                                            |
| 47  | [Where is the best place to write code to perform filtering in a form?](#47-best-place-to-write-code-to-perform-filter-in-a-form)                                   |
| 48  | [What are the different types of menu items available?](#48-types-of-menu-items)                                                                                    |
| 49  | [Action type menu item is attached to a form but is not appearing in the dropdown; what could be the problem?](#49-action-type-menu-item-not-appearing-in-dropdown) |

# AX Interview Questions & Answers

## 1. Difference between container operations

- **condel**: Deletes one or more items from a container.
- **confind**: Locates a sequence of items in a container.
- **conins**: Inserts items into a container.
- **conlen**: Returns the number of items in a container.
- **connull**: Explicitly disposes of the contents of a container.
- **conpeek**: Extracts an item from a container and converts it into another data type.
- **conpoke**: Replaces an item in a container.

## 2. Difference between edit and display method

- **Display**: The method’s return value is displayed on a form or report and cannot be altered.
- **Edit**: The method’s return value can be used in a form field and is editable.

## 3. Difference between perspectives and table collection

- **Perspectives**: Used to organize information for a report model in the AOT, acting as a collection of tables.
- **Table Collection**: A group of tables shared across virtual companies.

## 4. Types of files to copy to the standard folder

- **.aod**: Application Object Data file.
- **.ahd**: Application Online Help Data file.
- **.ald**: Application Label Data file.
- **.add**: Application Developer Documentation Data file.

## 5. Why use virtual companies?

Virtual companies allow sharing data across multiple company accounts through specific tables.

## 6. Restricting a class from extension

Use the `final` keyword (e.g., `public final class <ClassName>`).

## 7. Classes for data import/export

- **SysDataImport**
- **SysDataExport**

## 8. Table storing user permissions in AX

- **AccessRightList** table.

## 9. Activating the last record on form open

Set the **StartPosition** property of the datasource table to **Last**.

## 10. Sequence of events while generating a report

- Init, Run, Prompt, Fetch, Send, Print.

## 11. X++ Classes/Core classes related to Queries

- **Query**
- **QueryRun**
- **QueryBuildRange**
- **QueryBuildDataSource**
- **QueryBuildLink**

## 12. What is an index?

An index is a database structure that speeds up row retrieval from a table and ensures unique records.

## 13. Define IntelliMorph

IntelliMorph controls the user interface in Microsoft Dynamics AX, allowing for easy modifications of forms, reports, and menus.

## 14. Define MorphX

MorphX is the IDE in Microsoft Dynamics AX for developing and customizing interfaces.

## 15. Define X++

X++ is the object-oriented programming language used in the MorphX environment.

## 16. Difference between refresh(), reread(), research(), executeQuery()

- **refresh()**: Refreshes the screen without re-reading the record from the database.
- **reread()**: Re-reads the current record from the database.
- **research()**: Reruns the form query, updating records and reflecting changes.
- **executeQuery()**: Refreshes the form based on modified queries.

## 17. Define AOT

The Application Object Tree (AOT) is a tree view of all application objects within Microsoft Dynamics AX.

## 18. Define AOS

The Application Object Server (AOS) is the second-tier server in the AX three-tier architecture.

## 19. Difference between temp table and container

- **Temp Table**: Allows indexed data retrieval and is passed by reference in method calls.
- **Container**: Stores data sequentially, is passed by value, and is slower for large datasets.

## 20. EDT, Base Enum, and their usage

- **EDT (Extended Data Type)**: Reuses properties across fields, supports dynamic relations.
- **Base Enum**: A list of literals with internal integer representation.

## 21. Maps and AddressMap usage in AX

Maps wrap table objects at runtime, allowing uniform access to fields with different names across tables. **AddressMap** accesses fields from multiple tables.

## 22. Difference between Index and Index hint

- **Index**: Specifies an order to be used in a select statement.
- **Index hint**: Forces the use of a specific index in database queries.

## 23. Data validation methods at the table level

- **validateField()**
- **validateWrite()**
- **validateDelete()**
- **aosvalidateDelete()**
- **aosvalidateInsert()**
- **aosvalidateRead()**
- **aosvalidateUpdate()**

## 24. Types of relations in Axapta

- **Normal Relation**: Enforces referential integrity.
- **Field Fixed**: Conditional relation based on an enum field’s value.
- **Related Field Fixed**: Filters related table records based on an enum field.

## 25. Utility of recId

A unique identifier generated by the kernel for each table record.

## 26. Difference between Primary & Cluster index

- **Primary Index**: Unique, non-null index for fast data retrieval.
- **Clustered Index**: Can be unique or non-unique, stored with the data.

## 27. Types of lookups

- Using table relations.
- Using EDT relations.
- Using MorphX and X++ (SysLookup class).

## 28. Types of Delete Actions in AX

- **None**
- **Cascade**
- **Restricted**
- **Cascade+Restricted**

## 29. Fetching date & time stamp on record creation

Use the system date and time functions or use the `CreatedDateTime` field if available.

## 30. Function of super()

Calls the parent class’s method, usually to instantiate variables or avoid code redundancy.

## 31. Utility and use of find method

Selects and returns a record matching a unique index, with an option to lock the record for updates.

## 32. Types of Table groups

- **Miscellaneous**
- **Parameter**
- **Group**
- **Main**
- **Transaction**
- **WorksheetHeader**
- **WorksheetLine**

## 33. Handling lack of multiple inheritance

X++ does not support multiple inheritance; interfaces are used instead.

## 34. Necessity of the main method

Required to open a class from an action menu item.

## 35. Difference between new & construct method

- **new()**: Creates an object instance.
- **construct()**: Static method to instantiate and return an object.

## 36. Utility of RunOn property

Defines the execution tier (client/server) for objects like reports, tables, and methods.

## 37. Main class for batch processes

- **RunBaseBatch** class.

## 38. Regular interval batch jobs

Use **RunBaseBatch** to set recurring intervals.

## 39. Main utility of classes in standard AX

Handles business logic.

## 40. Classes called during SO/PO creation

- **SalesFormLetter**
- **PurchFormLetter**

## 41. Basic structure of a form

- **Methods**
- **DataSources**
- **Design**

## 42. Properties of a form datasource

- **Name**
- **Table**
- **Index**
- **AllowCheck**
- **AllowEdit**
- **AllowCreate**
- **AllowDelete**
- **StartPosition**
- **JoinSource**
- **LinkType**

## 43. validateWrite() in form datasource vs table level

- **Form Datasource**: Use when validation is specific to a form.
- **Table Level**: Use for global validation across all forms.

## 44. Calling table-level methods from form datasource

Create a variable for the table and call the method using `tableVariable.methodName()`.

## 45. Difference between form init() & DS init()

- **Form init()**: Initializes the form’s runtime image.
- **DS init()**: Creates the query and sets up links for the form’s datasource.

## 46. Sequential methods when opening a form

- **Form init()**
- **DataSource init()**
- **Form run()**
- **DataSource executeQuery()**
- **canClose()**
- **close()**

## 47. Best place to write code to perform filter in a form

In **FormDataSource.executeQuery()** method, and call this method in the design field of the form.

## 48. Types of menu items

- **Display**: For forms.
- **Output**: For reports.
- **Action**: For classes.

## 49. Action type menu item not appearing in dropdown

Check if the action type menu item is properly configured and linked to the form.
