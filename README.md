# ERP-School-Africa
Data Warehousing Team Members Individual Tasks Outline

Everyone should create all Schemas (ODS, STG, EDW, EDM) and Grant access to schemas on our various machines.

Data Warehousing Team Members = 7

A = Mubarak
B = Dipo
C = Mushefiu
D = Segun
E = Kunle
F = Henry
G = Emmanuel

Number of ODS Tables = 13

We can all create the various ODS tables by writing our individal scripts or by using the scripts in the txt document (ODS Tables).

Everyone should import data into their various ODS tables from the excel file (data source) containing all Hospitals Record.

CHECK the data in the ODS tables to see consistency with the excel file (data source). 

Everyone should perform Data cleansing on their various ODS tables.



In our various STG schemasLet's Create sequences as specified in txt document (STG Objects).



Number of EDW Dimensionn TABLES = 10 TABLES

EVERYONE SHOULD CREATE ALL THE Dimensions TABLES IN EDW (We have ready scripts for all tables in the txt document (EDW Dimensions Tables).

We are to Create a Package containing procedures that will lift data from the ODS tables to populate the EDW dimension tables
so we all will create pocedures that will lift data from the ODS tables and populate their corresponding EDW dimension tables we will be tasked with.
#Make use of the sequences created in stg where necessary.


A = HOSPITAL_CHALLENGES_DIM, HOSPITAL_FACILITIES_DIM
B = Check Procedures
C = HOSPITALS_DIM, HOSPITAL_SERVICES_DIM
D = LGA_DIM,TOWN_CITY_DIM
E = YEAR_DIM, S_DISTRICT_DIM
F = HOSPITAL_EMPLOYEES_DIM, NGO_DIM
G = Check Procedures

Create 1 procedure for populating each table assigned to you. ie. each person will have to create 2 procedures for both tables.

Test-run your procedures. If it populates the Dimension tables, submit it in the data warehousing group.

We all should CHECK the data in EDW against the data in ODS to see consistency.

Number of EDW Fact TABLES = 5 TABLES

We all all should Create all Facts tables in EDW (We have ready scripts for all tables in the txt document (EDW Facts Tables).


A = All Fcat Tables
B = Check
C = All Fcat Tables
D = All Fcat Tables
E = All Fcat Tables
F = All Fcat Tables
G = Check
 
We are to create a PARAMETERIZED Procedure to lift data from the EDW DIMENSION Tables, ODS Tables and populate the EDW FACTS Tables (Using 'Year' as parameter).

Test-run your procedures. If it populates the Fact tables.

CHECK the data in the EDW DIMENSION tables and ODS Tables against the data in EDW FACTS tables to see consistency.

EVERYONE SHOULD SUBMIT their procedures on the data warehousing group.

EVERYONE SHOULD Create Indexes on RELEVANT Columns in the entire database.

EVERYONE SHOULD Create views of all EDW DIMENSION Tables and EDW DIMENSION Tables in EDM Schema.
