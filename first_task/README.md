University

field:

-	name
-	budget
-	faculties
-	rector

methods:
-	get and set methods (where we need them)
-	electionForRector
-	increaseBudget - we can increase the budget with 1000 BGN, 10 000 BGN and 50 000 BGN
-	addFaculty

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

methods:
-	setName
-	getName
-	setAge
-	getAge
-	getEGN
-	getSex


Teacher (abstract class) (inherited Person)

field:
-	courses
-	department

methods:
-	get and set 
-	addCourse
-	print 
Lectors (inherited Teacher)

field:
-	degree
-	students
-	assistants

methods:
-	get and set
-	changeDegree
-	addStudent
-	addStudents
-	addAssistant
-	addAssistants
-	removeStudent
-	removeAssistant
-	recommendAssistant

Assistant (inherited Teacher)

field:
-	group
-	students (can't have more students from his lector)

methods:
-	get and set
-	checkHomework

Course (enum with min five instance)


Student (inherited Person)

field:
-	fn
-	specialty

methods:
-	get and set

Specialty (enum with min five instance)