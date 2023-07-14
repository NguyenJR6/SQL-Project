**Currently ongoing Project**

Creating a large database based on an action-role-playing game: Final Fantasy VII - Squaresoft

Pulling data by specific tables from the database and converting them into .csv files to create a visualization off of Microsoft Power BI

Testing and executing queries such as joining tables, selecting specific columns from tables, etc.

Here's a sample template of the database documentation for the ARPG project:

Database Design

• The ARPG database has 17 tables:  Accessory, Armor, Attributes, Bosses, Characters, Command_Materia, Enemies, Enemy_Skills, Final_Fantasy_VII, Independent Materia, Items, Limit_Breaks, Magic_Materia, Summon_Materia, Support_Materia, Weapons, World_Map_Locations

• The Characters table stores information about the individual's attributes and background, including their name, age, height, etc.

• The Weapon table stores information on the weapon's stats, including who is capable of the owner's rightful weapons, attack percentage, etc.


Data Dictionary 

Table: Characters

-     "Name" VARCHAR(255), Age VARCHAR(255), Height VARCHAR(255), Birthplace VARCHAR(255), DOB VARCHAR(255), High_Attributes VARCHAR(255), Low_Attributes VARCHAR(255), Job_Class VARCHAR(255), Weapon VARCHAR(255), Limit_Break VARCHAR(255), Blood_Type VARCHAR(50), Best_Traits VARCHAR(255), Worst_Traits VARCHAR(255)
  
Table: Weapons

-     "Character" VARCHAR(255), "Name" VARCHAR(255), Attack INT NOT NULL, "Attack_%" INT NOT NULL, Magic INT NOT NULL, Ability_Points VARCHAR(255), Materia_Slots VARCHAR(255), Materia_Growth VARCHAR(255), Special VARCHAR(255), Price INT NOT NULL, "Location" VARCHAR(255)
