# Student_Data_Array_of_Objects

**Main Class (Main.java):**
1. main(String[] args): The main method containing the menu-driven logic for interacting with the StudentManager class.

**Student Class (Student.java):**
1. Student(String prn, String name, String dob, double marks): Constructor for creating a new Student object with provided attributes.
2. getPRN(): Getter method to retrieve the PRN (Permanent Registration Number) of the student.
3. getName(): Getter method to retrieve the name of the student.
4. getDOB(): Getter method to retrieve the date of birth of the student.
5. getMarks(): Getter method to retrieve the marks of the student.
6. setMarks(double marks): Setter method to update the marks of the student.
7. toString(): Overrides the toString method to provide a string representation of the Student object.

**StudentManager Class (StudentManager.java):**
1. StudentManager(): Constructor for initializing the StudentManager object with an empty list of students and a scanner object.
2. addStudent(): Method to add a new student to the list by prompting the user for input.
3. displayAllStudents(): Method to display all the students currently stored in the list.
4. searchByPRN(): Method to search for a student by PRN (Permanent Registration Number) and display their details if found.
5. searchByName(): Method to search for a student by name and display their details if found.
6. searchByPosition(): Method to search for a student by their position in the list and display their details if the position is valid.
7. updateStudent(): Method to update the marks of a student by searching for them via their PRN and modifying their marks.
8. deleteStudent(): Method to delete a student from the list by searching for them via their PRN and removing them if found.
