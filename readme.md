
Title 
  Create a Java console program to manage Candidates of company.
Background Context
Candidate management system project in java is basically developed for manage the candidate of HR (Human Resource) management. In all company the candidate management is very important and it is not easy to handle it manually. So a candidate management system project is make as computerized. By making system is computerized it make possible to overcome the problem and work is efficient.

Program Specifications
Candidate management system includes some functions are work for creating, updating, deleting as well as searching. 
Create three classes with three kinds of candidate: Experience, Fresher, Intern
All Candidates have common attributes: Candidate Id, First Name, Last Name, Birth Date, Address, Phone, Email and Candidate type. There are three value of candidate type:
-	0: for Experience
-	1: for Fresher candidate
-	2: for Intern candidate
However, each kind of candidate has addition different attributes: 
-	Experience candidate: year of experience (ExpInYear), Professional Skill (ProSkill). 
-	Fresher candidate has addition attributes: graduated time (Graduation_date), Rank of Graduation (Graduation_rank) and university where student graduated (Education)
-	Intern candidate: Majors, Semester, University name

1.	Main Screen as below:

CANDIDATE MANAGEMENT SYSTEM
1.	Experience
2.	Fresher
3.	Internship
4.	Searching
5.	Exit
 (Please choose 1 to Create Experience Candidate, 2 to Create Fresher Candidate, 3 to Internship Candidate, 4 to Searching and 5 to Exit program).

2.	Function details:
2.1.	 Create Candidate and store in ArrayList. 
Requirements: 
-	The program have to check valid data for: Date of Birth, Phone, Email, Year of Experience, Rank of Graduation.
o	Birth Date : is number with length is 4 character (1900..Current Year)
o	Phone: is number with minimum 10 characters
o	Email: with format <account name>@<domain>. (eg: annguyen@fpt.edu.vn)
o	Year of Experience : is number from 0 to 100
o	Rank of Graduation: with one of 4 values (Excellence, Good, Fair, Poor)
-	From “Main Screen”, use select one item (1,2,3) to create candidate. After each candidate is created, the system shows message: Do you want to continue (Y/N)?. User chooses Y to continues, if you chooses N, the program returns main screen and display all candidates who are created.
2.2.	Search function
-	User select item 4, the program displays all candidates and requires user inputting Candidate name (First Name or Last Name) and type of candidate.  The program will search and display result with: Candidate name (First Name + Last Name), Birth Date, Address, Phone, Email and Candidate type. For example:

List of candidate:
===========EXPERIENCE CANDIDATE============
Aelbrecht Stefan
Aguirre Eva
Ahlgren Maria
Antošová	Adeleva
==========FRESHER CANDIDATE==============
Barbosa De Souza
Cabrera Cornide
Calderon Cuevas
Casulari Motta 
===========INTERN CANDIDATE==============
Maria Madeleine
Csokán	Babett
Joana Filipa
Patricia Carine

Input Candidate name (First name or Last name): eva
Input type of candidate: 0

The candidates found:
Aguirre Eva | 1990 | Sao paulo| 940394 | eva@asante.com | 0 
Antošová Adeleva | 1989 | Rio de janero | 984933| adelave@janeo.com | 0
   
Technical Requirements
1. Using Object-Oriented programming style: inheritance 
2. Use only core Java functions and classes.




Guidelines

Slot	Task	Description
1	-	Code Design
-	Create Experience Candidate	Should create Candidate as a SuperClass. Experience, Fresher and Internship Candidate as SubClasses that extend Candidate
Should 
2	-	Create Fresher Candidate	Should use ArrayList to store Fresher Candidate
3	-	Create Intern Candidate	Should use ArrayList to store Fresher Candidate
4	-	Search candidate	
5	-	Review program	

