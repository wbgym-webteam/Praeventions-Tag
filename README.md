# Praeventions-Tag
This is the repository for the management of the "Präventionstag" at the Weinberg Secondary School Kleinmachnow. 


What is presendet by the admin:
- the course list in .csv with the course name, discription (nullable), max people, room, block (Integer), Column Name
- the list of studends, with there emails, class

How the System Works:
- There are Columns and each studends ranks inside each Column all courses by there likeness
- The User submits his wishes
- The system determines what studend visits what course (each person has to have a course from every Column) and when he visits, like in what block/session he visits it

Output:
- A list for each room, showing who is gonna be in this room and in what block
- Either an Email or an easy to Cut Document showing the studend name, and when he has what courses and in what room
-> Email when possible
-> if not then with the Document
