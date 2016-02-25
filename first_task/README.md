University

field:

-	name
-	budget
-	faculties
-	rector

Faculties

field:
-	name
-	numberOfStudents
-	departments
-	numberOfLectors

Deparments (enum with min five instance)

Person

field:
-	name
-	age
-	EGN
-	sex


Teacher (abstract class) (inherited Person)

field:
-	courses
-	department

Lectors (inherited Teacher)

field:
-	degree
-	studets
-	assistants

Assistant (inherited Teacher)

field:
-	group
-	students (can't have more students from his lector)

Course (enum with min five instance)


Student (inherited Person)

field:
-	fn
-	specialty

Specialty (enum with min five instance)