## Day 1 Assignments

1) Identify the various classes, attributes, methods and the relationships between the classes for the below use case. Create appropriate class diagrams to depict the relationships.
- A company wants to build an application to store the details of their meeting rooms. There are two types of meeting rooms - one with Zoom calling facility and the second without Zoom calling facility. 
  - All meeting rooms are identified using a unique identifier. The application should also maintain the information about the capacity of each meeting room and the floor in which it is located. 
  - For meeting rooms with Zoom calling facility, the application must also maintain related information like Zoom device id and Zoom account id. 
  - Employees can book meeting rooms by providing the following information - employee id, meeting date, meeting time, and duration of meeting. 
  - All meeting bookings are also stored by the application and employees can get meeting information by providing the date of the meeting.

2) Write a method which accepts the name of a person as a parameter returns and returns a simple welcome message to the person. This method must be invoked by the main method and its output should be displayed. E.g. If the person enters “Naveen” then the method should return “Hello Naveen, Welcome to Java World! “

3) Write a method that accepts 3 numbers as parameters and returns the largest number among them.

4) Write a method which accepts a 3 digit number and prints it’s digits in words
  E.g. If the input number is 951, then the output should be “Nine Five One”

5) Implement the following methods in a class. public void add (int a, int b)
```public void add (long a, long b)
public void add (float a, float b)
public void add (short a, short b)
```
Invoke these methods by passing appropriate parameters and display the output in the main method.
Hint: To call `add(short a, short b)` method, you may need to use `add((short)5,(short)6)`

6) Implement appropriate versions of the `add()` method in a class so that 
  - `add(10,20)` returns 30
  - `add(10,20,30)` returns 60
  - `add(10.5, 20.1)` returns 30.6
  - `add(“Hello”,20)` returns “Hello 20”

7) Define a class Student with the following attributes
  - studentId of type integer
  - studentName of type String
  - city of type String
  - marks1 of type integer
  - marks2 of type integer
  - marks3 of type integer
  - feePerMonth of type float
  - isEligibleForScholarship of type boolean

Implement the following methods in addition to the setter and getter methods for the various attributes
  - getAnualFee() which returns the product of feePerMonth and 12
  - getTotalmarks() which returns the sum of marks1, marks2 and marks3
  - getAverage() which returns the average of marks1, marks2 and marks3
  - getResult() which returns “pass” if the person has scored more than 60 in each subject, or returns “fail” otherwise

Create another class TestMain with the main() method which performs the following actions
  - Creates three Student objects
  - Populates the objects using the setter methods
  - Displays the name of the Student who has the highest total marks
  - Prints the name and fee of the Student who pays the least monthly fee
  - Prints the name, total marks , average marks , result, and “Scholarship available” or “Scholarship not available” based on the student’s eligibility for every student.
