Download Link: https://assignmentchef.com/product/solved-csi121-lab3-inheritance-polymorphism-and-interface
<br>
<strong>Objectives</strong>

<ul>

 <li>Familiar with Inheritance, Polymorphism and interface.</li>

</ul>

<strong>Task 1: </strong>

The student record application is described as follows.

Student class (abstract class)

<ul>

 <li>Name (first and last name)</li>

 <li>DOB</li>

 <li>Address</li>

 <li>Mobile number</li>

 <li>Student ID</li>

</ul>

Undergraduate Student class

<ul>

 <li>Name (first and last name)</li>

 <li>DOB</li>

 <li>Address</li>

 <li>Mobile number</li>

 <li>Student ID</li>

 <li>Current course</li>

 <li>Expected completed session (session, year)</li>

</ul>

Post-Graduate Student class

<ul>

 <li>Name (first and last name)</li>

 <li>DOB (date)</li>

 <li>Address</li>

 <li>Mobile number</li>

 <li>Student ID</li>

 <li>Current course</li>

 <li>Expected completed session (session, year)</li>

 <li>Previous degree</li>

 <li>Date of Completion of the previous degree (date)</li>

</ul>




Address class

<ul>

 <li>Street number</li>

 <li>Street name</li>

 <li>City</li>

 <li>State</li>

 <li>Postcode</li>

 <li>Country</li>

</ul>




Student System class

<ul>

 <li>students (ArrayList&lt;Student&gt;)</li>

</ul>




Test Code class

<ul>

 <li>Test the program (main())</li>

</ul>

Draw UML class diagrams and write java program with the below instructions.

<ol>

 <li>From the above information, draw the UML class diagram of the classes and the relationship between the classes.</li>

 <li>Write java program to construct the above class. Design your own methods for each class using the concept of OOP design principle.</li>

 <li>Design a StudentSystem class that keep the record of all students (i.e., an Arraylist of Student objects). In the StudentSystem class, design a student search method that takes an int (Student id) as the input and print all information of the student (overwrite toString() method for the printing).</li>

 <li>Write test code in the main method in the TestCode Class with the following steps:

  <ol>

   <li>create an object of StudentSystem;</li>

   <li>create one undergraduate student (Student ID:100000) and one postgraduate student</li>

  </ol></li>

</ol>

(Student ID:200000) objects and add the two student objects to the student arraylist;

<ol>

 <li>use the student search method to search and print (using toString() and polymorphism) the information of the two students;</li>

 <li>use a for loop to go through the student arraylist and update the undergraduate student’s expected completion session to “Spring 2022”, and update the postgraduate student’s previous degree to “Bachelor of Math”(using instanceof and downcasting);</li>

 <li>use another for loop to print the updated information of the two students.</li>

</ol>

<strong>Task 2: </strong>

The University online shopping members system is briefly described in the below UML class diagram. Please complete the UML class diagram and write a java program following the below instructions.

<ol>

 <li>Write all the code to construct the below class in the diagram. Design your own methods for each class using the concept of OOP design principle.</li>

 <li>Implement all clone() methods (deep clone) for all classes that implements Clonable interface.</li>

 <li>Write test code in the main method in the TestCode Class and create a PhD object and a Undergraduate object and testing the clone() methods with this two objects.</li>

</ol>








