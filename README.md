Download Link: https://assignmentchef.com/product/solved-cs217-assignment-3
<br>
<strong>Question 1: </strong>

<strong> </strong>

Implement a  structure Employee. An employee has a name (a char *) and a salary (a double). Write a default constructor, a constructor with two parameters (name and salary), and methods <strong>char* getName()</strong>  <strong>double  getSalary()</strong>  to return the name and salary.

Write a small global function <strong>TestEmployee()</strong> to test your structure.




Creating a new employee.

Please type the name:

Larry Bird

Please specify the salary: 200000 New employee has been created.

Name of employee: Larry Bird

Salary: 200000.0

Thank you for testing structure Employee.




<strong>Question 2: </strong>

Implement a structure Car with the following properties. A car has a certain fuel efficiency (measured in miles per gallon or liters per km <strong>pick one</strong>) of type <strong>float</strong> and a certain amount of fuel in the gas tank of type <strong>float</strong>. The efficiency is specified in the constructor, and the initial fuel level is 0. Supply a method <strong>drive (float)</strong> that simulates driving the car for a certain distance, reducing the fuel level in the gas tank, and methods




float <strong>getFuelLevel() </strong>returning the current fuel level, and  void <strong>tank(float)</strong>, to tank up.




Sample usage of the structure:

void main() {

Car myBeemer(29);

cout&lt;&lt;myBeemer.getFuelLevel()&lt;&lt;endl;    myBeemer.tank(20);

cout&lt;&lt;myBeemer.getFuelLevel()&lt;&lt;endl;    myBeemer.drive(100);

cout&lt;&lt; myBeemer.getFuelLevel()&lt;&lt;endl;

}

Should produce:




0.0

20.0

16.551724137931036




<strong>Question 3: </strong>




Implement a structure Circle (think of its data members) that has methods

<ul>

 <li>float <strong>getArea()</strong> and</li>

 <li>float <strong>getCircumference() </strong></li>

</ul>

In the constructor, supply the radius of the circle.




Please specify the radius of your circle: 1.0 Circle created.

Area: 3.141592653589793 Circumference: 6.283185307179586 Good-bye!




<strong>Question 4: </strong>

<strong> </strong>

Define a structure FlightInfo in C++ with following description:




<strong>Private Members</strong>

A data member <strong>FlightNumber</strong> of type integer

A data member <strong>Destination </strong>of type char*

A data member <strong>Distance</strong> of type float

A data member <strong>Fuel </strong>of type float




A member function void <strong>calFuel()</strong> to calculate the value of Fuel as per the following criteria and set its corresponding data member

Distance                                                          Fuel

&lt;=1000                                                            500             more than 1000  and &lt;=2000                         1100             more than 2000                                               2200 <strong> Public Members</strong>

A function void <strong>feedInfo()</strong> to allow user to enter values for Flight Number, Destination, Distance &amp; call function void <strong>calFuel()</strong> to calculate the quantity of Fuel

A function void <strong>showInfo()</strong> to allow user to view the content of all the data members A function float <strong>getFuel()</strong> that returns the current fuel value.




<strong>Question 5: </strong>

Implement a structure Employee2. An employee has a name (a char *) , HourlyWage (float) , WorkedHours(float) and ExtraHours(float).

<strong> </strong>

Write a function

float  <strong>wageCalculator()</strong>




that reads in the name and hourly wage of an employee. Then ask how many hours the employee worked in the past week. Be sure to accept fractional hours. Compute the pay. Any overtime work (over 40 hours per week) is paid at 150 percent of the regular wage. Print a paycheck for the employee.




Please enter employee’s name then press Enter : Larry Bird

Please enter hourly wage then press Enter : 12.50

Please enter hours worked then press Enter: 10

Paycheck for employee Larry Bird




Hours worked: 10.0

Hourly wage: 12.5




Total payment: 125.0







Please enter employee’s name then press Enter : Michael Jordan

Please enter hourly wage then press Enter : 10

Please enter hours worked then press Enter: 50

Paycheck for employee Michael Jordan




Hours worked: 50.0

Hourly wage: 10.0




Overtime hours: 10.0

Overtime hourly wage: 15.0




Total payment: 550.0




<strong>Question 6: </strong>

<strong> </strong>

Implement a structure Address. An address has

<ul>

 <li>a <strong>HouseNumber (int)</strong>,</li>

 <li>a <strong>street (int)</strong>,</li>

 <li>an optional <strong>ApartmentNumber (int)</strong>,</li>

 <li>a <strong>city(char*)</strong>,  a <strong>state(char*)</strong></li>

 <li><strong>PostalCode(int)</strong>.</li>

</ul>

write two constructors:

<ul>

 <li>one with an ApartmentNumber  and one without.</li>

 <li>Write a <em>void</em> <strong>print()</strong> function that prints the address with the street on one line and the city, state, and postal code on the next line.</li>

 <li>Write a method <em>bool</em> <strong>compareTo()</strong> that tests whether one address comes before another when the addresses are compared by postal code</li>

</ul>




<strong>Question 7: </strong>

Implement a structure Account. An account has data member:




<ul>

 <li>a <strong>balance(float)</strong>,</li>

</ul>




and member functions  void <strong>deposit(float)</strong> add money bool <strong>withdraw(float)</strong> withdraw money after checking conditions float <strong>inquire ()</strong> returns the current balance.







<ul>

 <li>Pass a value into a constructor to set an initial balance.</li>

 <li>If no value is passed the initial balance should be set to $0.</li>

 <li>Charge a $5 penalty if an attempt is made to withdraw more money than available in the account.</li>

</ul>




<strong>Question 8 </strong>




Create a Class named <em>Student</em> with following private data members

<ul>

 <li>Roll Number(char *)</li>

 <li>Name(char *)</li>

 <li>Batch(int)</li>

 <li>An Array named Courses_Code(int) of length 5, containing course code of the registered courses</li>

 <li>An Array named Courses_Name(char *) of length 5, containing course name of the registered courses</li>

 <li>An Array named Courses_Grades(char) of length 5, containing course grades of the registered courses</li>

 <li>CGPA(float)</li>

 <li>Degree(char *)</li>

 <li>Date of Birth(char *)</li>

</ul>




The class should have following functions

<ul>

 <li><strong>setValues(),</strong> to set values of the variables</li>

 <li>A default constructor to initialize all data members to some initial value</li>

 <li>An overloaded constructor which is passed values of all data members as argument</li>

 <li>9 different functions to update/change value of each of the data member</li>

 <li>A display function to display transcript of the student in following format (including box)</li>

</ul>




Create an instance of the above structure in function named studentDemo void <strong>studentDemo() </strong>and demonstrate use of all member function of the structure.







<strong>Question</strong><strong> 9: </strong>

<strong> </strong>

Write the definition for a class called <strong>Rectangle</strong> that has floating-point data members length and width. The class has the following member functions:

<strong> </strong>

<ul>

 <li><strong>void setLength(float)</strong> to set the length data member</li>

 <li><strong>void setWidth(float)</strong> to set the width data member</li>

 <li><strong>float perimeter()</strong> to calculate and return the perimeter of the rectangle</li>

 <li><strong>float area()</strong> to calculate and return the area of the rectangle</li>

 <li><strong>void show()</strong> to display the length and width of the rectangle</li>

 <li><strong>int sameArea(Rectangle)</strong> that has one parameter of type Rectangle. sameArea() returns 1 if the two Rectangles have the same area, and returns 0 if they don’t.</li>

</ul>

<strong> </strong>

<strong> </strong>































<strong>Question</strong><strong> 10: </strong>




Implementation of Array Class Your goal is to implement a generic “<strong>Array</strong>” class. Your implemented class must fully provide the definitions of following class (interface) functions given in the code snippets below:


