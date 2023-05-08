Download Link: https://assignmentchef.com/product/solved-solved-hvm-wants-to-keep-a-list-of-their-customers
<br>
<p class="ui header product-top-header" title="HVM wants to keep a list of their customers Solution">HVM wants to keep a list of their customers. The information they store for each

HVM wants to keep a list of their customers. The information they store for each customer is their name, a customer identification number, their address, phone number, what boat number they own (which will correspond to the boat information in HVM’s boat and slip database) and the number of the slip they rent (which will correspond to their slip mooring information). (You can choose to leave the name field as one element storing names in the format “Last_name, First_name”; or you may choose to have one field for last name and one for first name.)

The information they need about each boat is a boat identification number, the width and length of the boat, the State registration number, the value of the boat, and the slip they rent. (Although in our demonstration software we could keep all the boat information within the customer object record, in order to keep true to object oriented [and relational database] principles, you will create a separate boat object.)

HVM also keeps track of the slips they have for mooring boats. Each slip is assigned an identification number and they have on record the width and length of the slip as well as the monthly fee charged for renting the slip. Also, you will need to keep track of whether a slip is currently rented, or whether it is available to be rented by a customer. (See Note #2 in Programming Notes below.)

– Note that each customer should own one boat (i.e. the ID number of the boat they own in the Customer instance should be associated with a valid boat identification number in the Boat instance). Also note that each customer will rent one slip (i.e. their slip rental number in the Customer instance should be associated with a valid slip identification number in the Slip instance). You may want to make sure the size of the boat will fit in the size of the slip; that will become an issue as this project progresses.

– Assumption: each customer will only be owner of one boat and will only rent one slip.

– As mentioned in previous Units, in a production program you would need robust error checking and user input validation, to provide your user with a complete menu system, and to make sure that there were no conditions in which your program would end unexpectedly (i.e. you would want to catch and handle all error conditions). However, this program is a prototype of various tasks, not a production program. At this point I do not expect advanced error checking, complicated menus, etc.; just carry out the tasks asked of you, based on the requirements of the program.

– You are expected to follow the “General Directions” found in the “Course Project Instructions” link on our course page.

Your tasks for Unit 3 are:

(1) Create Classes for each of the object types that need to be stored, as indicated above. (See Note #3 in Programming Notes below.)

(2) Create an array of Customer objects. You should populate the array with 4 to 6 customers, entering information into all fields of the Customer object. Again they should be created in “non-alphabetical” and “non-numeric” order as far concerns their last name and customer ID. . (Again, see Note #3 in Programming Notes below to understand how to populate Objects with data.)

Display the total number of customers that exist.

Print Customer information about each customer. You can either print all information (fields), or print customer ID, last name, first name, boat number, and slip number (excluding address and phone number).(See Notes #4 and #5 in Programming Notes below.)

(3) Create an array of Boat objects. You should populate the array with as many boats as you have customers (since we assume one boat per customer), entering information into all fields of the Boat object. (The boat numbers in the Customer and Boat objects should match.)

Present the “total” value of all boats moored at HVM as a sum (in dollar amount, formatted properly).

(4) Create an array of Slip objects. You should populate the array with 10 slips, entering information into all fields of the Slip object. (Make sure that all customers have a valid slip number in their information, and mark that slip as rented.)

Display the total number of slips that exist.

Print out all information for the slips that are currently rented (only).

Unit 3 Programming Notes:

Even though you will be submitting four separate .cs files (one for each class object and one “driver/test” program), it is suggested that you create them all as one Visual Studio Project, if that is what you are using for your C# *****

See this diagram of the objects in this project and their relationships: U3-Object-Diagram.png. However, please note that in this example we are *not* doing a relational database query (like an SQL statement) as we would if this were a true database implementation. We have not yet learned the features of C# (such as LINQ) that will allow us to easily do this

<span class="kksr-muted">Rate this product</span>

<button class="ui mini button product-like-wrap" data-key="KxfN" data-auth="false"><i class="heart icon"></i> <span class="likes">0</span></button>