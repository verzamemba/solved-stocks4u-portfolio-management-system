Download Link: https://assignmentchef.com/product/solved-stocks4u-portfolio-management-system
<br>
OBJECTIVES

Add persistent data storage to your Week 5 Lab using the MySQL Database.

PROBLEM:  Stocks4U Portfolio Management System

The portfolio management system you developed for Stocks4U needs the ability to save and restore a user’s data from a MySql Database.

FUNCTIONAL REQUIREMENTS

<ul>

 <li>The functional requirements of the Stocks4U application have not changed, and the Graphical User Interface has not changed from Week 5.</li>

</ul>

<u>StockIO class</u>

Modify the StockIO class to read and write the stock information to and from a MySQL database.  Called “StocksDB”

This class should have two methods.

<ul>

 <li>getData—reads data from file, returns data in array list of stock objects</li>

 <li>saveData—writes data from an array list to the data base in proper format</li>

 <li>deleteStock—deletes the identified stock from the database</li>

 <li>updateStock—updates the identified stock in the database.</li>

</ul>

The database connection string will be stored as a constant in the StockIO class.

<u>GUI class</u>

Note that you will need to add an ArrayList to your GUI class to manage the data to/from the file. It will act as a parallel array to your DefaultListModel. Any time you add a stock, you must add it in BOTH places. Any time you remove a stock, you must remove it in BOTH places.

File—open should open the database, retrieve the existing records and display the existing records.

File—save should save all records, new and old, back to the database.

File—exit should exit the program.

The total value of the portfolio should be displayed at all times and updated anytime a stock is added or removed.

Sample GUI







RUBRIC

<table width="848">

 <tbody>

  <tr>

   <td>StockIO class·         getData method reads from database·         saveData method writes data to the database·         udpateStock method updates the identified stock to the database·         deleteStock method deletes the identified stock in the database</td>

   <td>40</td>

  </tr>

  <tr>

   <td>Code style</td>

   <td>5</td>

  </tr>

  <tr>

   <td>Lab Report</td>

   <td>10</td>

  </tr>

  <tr>

   <td>TOTAL</td>

   <td>55</td>

  </tr>

 </tbody>

</table>

CODE STYLE REQUIREMENTS

Include meaningful comments throughout your code.

Use meaningful names for variables.

Code must be properly indented.

Include a comment header at beginning of each file, example below.

/****************************************************Program Name: ProgramName.javaProgrammer’s Name: Student NameProgram Description: Describe here what this program will do***********************************************************/

DELIVERABLES

Submit as a SINGLE zip folder

<ul>

 <li>all Java files; and</li>

 <li>the Lab report.</li>

</ul>

Follow assignment specification regarding class/method names.

Note that your Java file name must match class name (DO NOT rename).


