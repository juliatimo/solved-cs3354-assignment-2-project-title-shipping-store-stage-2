Download Link: https://assignmentchef.com/product/solved-cs3354-assignment-2-project-title-shipping-store-stage-2
<br>
<span class="kksr-muted">Rate this product</span>

<table>

 <colgroup>

  <col>

  <col>

 </colgroup>

 <tbody>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

Goal: The goal of this assignment is to help students familiarize themselves with the following Java

programming concepts:

• Object Oriented Design • Inheritance

<ul>

 <li>Java Exception Handling</li>

 <li>Java Object SerializationDescription:For the first assignment, you created a program that simulates a shipping store database. The shipping store has now decided to expand its business. It has decided to not just keep an inventory of the packages, but to also record user information and keep a record of the packages user ships with the store. To keep up with the new demands, the shipping store needs to expand its management software to support the new information. For every package, the software will store the same basic information as in assignment 1, plus some additional information:General information about all packages:</li>

</ul>

<ul>

 <li>Tracking number (string of length 5)</li>

 <li>Specification (string)</li>

 <li>Mailing Class (string)Depending on the specific type of package, the additional information that needs to be in the database is:</li>

</ul>

Type of Package

Additional Information Needed

Envelope

<ul>

 <li>Height (integer number) – in inches</li>

 <li>Width (integer number) – in inches</li>

</ul>

Box

<ul>

 <li>Largest dimension (integer number) – in inches</li>

 <li>Volume (integer number) – in inches3</li>

</ul>

Crate

<ul>

 <li>Maximum Load Weight (lb): float</li>

 <li>Content: string</li>

</ul>

Drum

<ul>

 <li>Material: string (Plastic, Fiber)</li>

 <li>Diameter: float – in inches</li>

</ul>

The database will still maintain records of the packages that are in the storage room. The shipping store now also keeps records of the users. The users are of two types, employees and customers.

• For all user types, the following information is kept in the system: • ID (unique number generated for each user): int• First Name: String• Last Name: String

In addition, the following information is kept for each user type.

• Employee

<ul>

 <li>Social Security Number: int</li>

 <li>Monthly salary: float</li>

 <li>Direct deposit bank account number: int• Customer</li>

 <li>Phone number: String</li>

 <li>Address: StringFinally, the shipping store records information about completed transactions (delivered packages). Eachcompleted transaction includes the following information:</li>

</ul>

<ul>

 <li>Customer id: int</li>

 <li>Package Tracking Number: String</li>

 <li>Shipping date: Date</li>

 <li>Delivery date: Date</li>

 <li>Cost of shipping: float</li>

 <li>Employee id (who completed the sale): intNote that the customer id, the employee id and the package tracking number included in a sale transaction, should match existing entries of customers, employees and packages already existing in the repository. New functionality of the shipping store system looks like this:</li>

</ul>

<ol>

 <li>Show all existing package records in the database (sorted by tracking number).</li>

 <li>Add new package record to the database.</li>

 <li>Delete package record from a database.</li>

 <li>Search for a package (given its tracking number).</li>

 <li>Show a list of users in the database.</li>

 <li>Add new user to the database.</li>

 <li>Update user info (given their id).</li>

 <li>Complete a shipping transaction.</li>

 <li>Show completed shipping transactions.</li>

 <li>Exit program.</li>

</ol>

For #2, when the user selects to add a new package to the database, they should be asked to specify the type of the package before they enter the package information. The same applies for #7 regarding the user types.

For #8, when a package is delivered, a new completed transaction record is created and the package is automatically deleted from the package inventory. The program should not allow a transaction to be completed if any of the packages or user does not exist in the database. A user has to be added to the database before a transaction can be completed.

Tasks:

<ol>

 <li>Create and object oriented Java program that implements the shipping store management software described above. Make use of the inheritance and polymorphism concepts that we saw in class. For example a print() method used to print information about a package or a user, may be defined multiple times in the different classes and subclasses used in the program.</li>

 <li>Try to make your program as robust as possible, by using Exception handling to deal with possible problems that may occur during the program execution. You may also create your own custom exception classes to handle bad input from the user, etc.</li>

 <li>This time do not save your data as text files, but as serializable objects. You may use more than one file to store your data, if it is more convenient to you.</li>

 <li>Print out the package and user information in a formatted manner. Output headers and make the data line up in columns under the headers.</li>

 <li>Use a standard Java coding style to improve your program’s visual appearance and make it more readable. I suggest the BlueJ coding style: http://www.bluej.org/objects- first/styleguide.html</li>

 <li>Use Javadoc is for every public class, and every public or protected member of such a class.</li>

 <li>Other classes and members still have Javadoc as needed. Whenever an implementation comment would be used to define the overall purpose or behavior of a class, method orfield, that comment is written as Javadoc instead. (It’s more uniform, and more tool- friendly.)</li>

</ol>

Notes:

This assignment should be done in pairs of two students. Please find a partner and send the names of your team members to our teaching assistantJunye Wen &lt;<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="87edd8f0b5b4b1c7f3fff4f3e6f3e2a9e2e3f2">[email protected]</a>&gt; by Tuesday, Sept. 26.

<ul>

 <li>You may use an IDE (BlueJ, Netbeans, etc) or just an editor and command lineoperations (javac, java) in Unix or Windows/DOS to develop your program.</li>

 <li>Use good design (don’t put everything in one class).</li>

 <li>Use a package for your classes and put your files in the appropriate directory structure.</li>

 <li>Be sure to validate the user input.</li>

</ul>

<ul>

 <li>You don’t need to create any GUI for this assignment. Command line operations are enough.</li>

 <li>Use a standard Java coding style to improve your program’s visual appearance and make it more readable. I suggest the BlueJ coding style:http://www.bluej.org/objects- first/styleguide.html</li>

 <li>Use javadoc comments for all of your classes and methods.Logistics: Please submit your files in a single zip file (assign1_xxxxxx_yyyyyy.zip). The xxxxxx and yyyyyyare your TX State NetIDs.Submit: an electronic copy only, using the Assignments tool on the TRACS website. Submit using the TRACS account of just ONE member of your partnership. State both names in the comments.Do NOT include executable .class or .jar files in your submission. Only .java files.</li>