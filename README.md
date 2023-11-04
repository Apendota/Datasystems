# Datasystems
# Construction Business Data Entities

This repository contains data entities for a construction business, including tables, CSV files, and XML files for the entities.

## Entity Descriptions

1. Projects - Refers to the various construction projects the company is undertaking.
2. Employees - Represents the individuals working for the company.
3. Equipment - Refers to the machinery and tools used in construction.
4. Clients - Represents the organizations or individuals hiring the construction company.
5. Materials - Refers to the various materials used in construction.

## Entity Tables

1. Projects
    - ProjectID (Integer)
    - ProjectName (VarChar)
    - StartDate (Date)
    - EndDate (Date)
    - Budget (Float)

2. Employees
    - EmployeeID (Integer)
    - FirstName (VarChar)
    - LastName (VarChar)
    - Position (VarChar)
    - Salary (Float)

3. Equipment
    - EquipmentID (Integer)
    - Name (VarChar)
    - Status (VarChar)

4. Clients
    - ClientID (Integer)
    - ClientName (VarChar)
    - ContactPerson (VarChar)
    - ContactNumber (VarChar)
    - Email (VarChar)

5. Materials
    - MaterialID (Integer)
    - Name (VarChar)
    - Quantity (Integer)

## Files

The repository contains CSV and XML files for each entity, containing example data for each entity.

- Projects.csv and Projects.xml
- Employees.csv and Employees.xml
- Equipment.csv and Equipment.xml
- Clients.csv and Clients.xml
- Materials.csv and Materials.xml

Feel free to use this data as a reference for a construction business or modify it to suit your specific needs.

