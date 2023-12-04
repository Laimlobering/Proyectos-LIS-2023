# Estimation by the COSMIC method
## Sprint: Testing the requirements, UI and UX of the software
## PHASE 1
### Purpose
Measuring this Sprint will help us identify the effort required for its completion. With the approximate functional size of the software, the key objective of this record will be to calculate the cost and time needed to develop the software.

### Scope
The scope of the tests to be carried out in the application will be restricted to the functions visible to the common user of the system.

### Identification of user functions
**Functional user(s) are identified:**
The user we will use for measuring the Sprint functionalities will be individuals. Since the purpose is to measure the functional size of the software, the users will be the individuals conducting tests on the user functionalities to validate them and ensure their implementation in the software is appropriate.

## PHASE 2
**User Function Identification:**
*List of user functions:*

Processes:

* User registration to the system
* User login
* Edit user profile information
* Remove ingredients
* Save/Delete favorite recipes
* Search recipes by ingredient
* Recipe consultation
* Plan recipes based on routine

## PHASE 3

*Subprocesses of user functions and their classification:*

**Process: User registration to the system**
Subprocesses:

1. Information input (Entry)
2. Create account (Write)

**Process: User login**
Subprocess:

1. Information input (Entry)
2. Log in (Read)

**Process: Edit user profile information**
Subprocess:

1. Information input (Entry)
2. Option to save changed information (Write)

**Process: Remove ingredients**
Subprocess:

1. Information input (Entry)
2. Information input (Read)
3. Ingredient (Exit)
4. Message "No results" (Exit)

**Process: Save/Delete favorite recipes**
Subprocess:

1. Selection (Entry)
2. Recipe (Write)

**Process: Search recipes by ingredient**
Subprocess:

1. Information input (Entry)
2. Information input (Read)
3. Ingredient (Exit)
4. Selection (Entry)
5. *Deselect (Exit)
6. Search recipes (Entry)
7. Recipes (Read)
8. Recipe results (Exit)

**Process: Recipe consultation**
Subprocess:

1. Click on the recipe (Entry)
2. Recipe information (Read)
3. Recipe information (Exit)

**Process: Plan recipes based on routine**
Subprocess:

1. Information input (Entry)
2. Recipes in the planned schedule (Exit)
3. *Delete recipe plan (Entry)
4. Save changes (Write)

**Process: Recipe Consultation**
Subprocess:

1. Click on the recipe (Entry)
2. Recipe information (Read)
3. Recipe information (Exit)

**Process: Recipe Planning Based on Routine**
Subprocess:

1. Information input (Entry)
2. Recipes in the planned schedule (Exit)
3. *Delete recipe plan (Entry)
4. Save changes (Write)

### Sum of user functionalities:
![](https://github.com/Laimlobering/Proyectos-LIS-2023/blob/PD-3/Assets/Suma%20CFP.png)
## Effort Estimation

Assigning one Cosmic Function Point (CFP) for each subprocess, we estimate a total of 27 CFPs for the sprint.

## Time Estimation

Considering that the sprint involves informal testing, we estimate that the duration for each Cosmic Function Point (CFP) will be approximately 5 minutes. The total time for the sprint is calculated by multiplying the number of Cosmic Function Points by the duration per function point, resulting in 135 minutes, approximately 2.25 hours.

## Cost Estimation

For this sprint, the team is divided into two roles: testers and UI/UX designers. Testers are responsible for ensuring that user interfaces meet the requirements, while UI/UX designers handle the design of the interfaces and future corrections.

### Junior Testers
Average hourly salary in Mexico: $80

Team members:

- Tzab Tzab Ary Obed
- Domínguez Franco Cesar Adrián
- Martínez Montemayor Karen Patricia

### UX/UI Designers
Average hourly salary in Mexico: $111

Team members:

- Montero Uc José Francisco
- Rodríguez Aguirre Mauricio Eduardo
- Aviles Castillo Jesús Alberto
### Salary table
![](https://github.com/Laimlobering/Proyectos-LIS-2023/blob/PD-3/Assets/Tabla%20salarios.png)

We can conclude that the cost of this sprint will be approximately $1289.25 according to the data found.

## Salary References

Salario medio para diseñador UX UI en México 2023. talent.com. 2023. https://mx.talent.com/salary?job=dise%C3%B1ador+ux+ui  

Salario promedio para tester jr en México 2023. talen.com. 2023. https://mx.talent.com/salary?job=de+tester+jr#:~:text=%C2%BFCu%C3%A1nto%20gana%20un%20De%20tester%20jr%20en%20M%C3%A9xico%3F&text=El%20salario%20de%20tester%20jr,a%C3%B1o%20o%20%24%2080%20por%20hora.  

