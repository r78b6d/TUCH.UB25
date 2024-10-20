java cTECH.UB.25: Intro to Python Programming: Assignment # 4
 
Scenario:  Campus Pizza is really taking off and your co-founders love the programs you have built.  They want you to build an object-oriented program for their beverages.   Campus pizza has two beverage options: Soda from the soda fountain, and home-made lemonade which is available as sweetened or unsweetened.   Both beverages are $1.50 for a small, $1.75 for a medium and $2.00 for a large.  
 
Program Guidelines: 
1) Superclass: Create a superclass called “Beverage” that has two attributes: “size” and “price”.  “Beverage” should also have a method called “display” that prints out a statement of the size and price of the drink.  
 
2) Subclasses: 
a) Soda Subclass: Create a subclass “Soda” that inherits all the attributes and methods of Beverage.  
b) Lemonade Subclass: Create a subclass “Lemonade” that inherits all the attributes of subclass, but add an attribute called “sugar” for whether the customer wants the lemonade sweetened or unsweetened.  Additionally, edit the display function so that it also shows the sugar status.   
 
3) Functions: Outside of the classes, create the following functions:
a) Title: Create a function called “title” that prints the title “The Beverage Program”  
b) Closing: Create a function called “closing” that prints the number of drinks created and thanks them for using the program 
c) Getting Size:  Create a function called “get_size” that asks the user what size beverage the user wants (S, M, L) and assigns it to a variable called “size_input”.   If the user enters an invalid value, assume the size is a Small.  Based on their input, return a variable called “size” from the function. 
d) Get Sugar:  Create a function called “get_sugar” that asks the users who want a lemonade whether they would like their lemonade Sweetened or Unsweetened (S or U) and assigns it to a variable called “sugar_input”.  Return a variable called sugar with the phrase “Sweetened or Unsweetened” based on user status.  If the user doesn’t put an “S”, default to Unsweetened.   
e) Get Price:  Create a function called “get_price” that returns a variable called “price” based on the si代 写TUCH.UB25、python
代做程序编程语言ze of the drink.  
 
4) Main: 
- Nest all your functions inside a main function. 
- Start by creating an empty list called “drinks.” 
- Create a loop that allows the user to create orders for multiple drinks.  
- Ask the user to create a drink by asking for the drink type, “S” for soda, “L” for lemonade, “0” to exit, and then proceed to get the size of the drink. (The reason this needs to be inside the main function vs. its own function is because the “0” will break the main program loop). 
- If the user enters an incorrect value for the drink type or size, end the program and ask them to run it again.  
- If the drink is a lemonade, ask the user if they would like it sweetened “S” or unsweetened “U”. If the user enters something else, assume it is unsweetened.  
- After the user has created all of the drink, assign it to an object.  Add this object to the “drinks” list.  
- When the user enters “0” and is done creating new drinks,  print all the objects in the “drinks” list.  For each drink in the list “drinks”, show the drink number, type, price and sweetness (for lemonades).  
- Finally, close the program and show the user the number of drinks they created.   
 
Program Console: 
______________________
The Beverage Program
 
Soda or a lemonade? Enter S, L or 0 for no drinks: S
What size would you like?  Enter S, M or L: M
Would you like to create another drink? y/n? y
 
Soda or a lemonade? Enter S, L or 0 for no drinks: Q
Incorrect drink type.  Please enter S or L: L
What size would you like?  Enter S, M or L: L
Sweetened or Unsweetened?  Enter S or U: U
Would you like to create another drink? y/n? y
 
Soda or a lemonade? Enter S, L or 0 for no drinks: L
What size would you like?  Enter S, M or L: S
Sweetened or Unsweetened?  Enter S or U: S
Would you like to create another drink? y/n? n
 
Drink 1: Soda
Size: Medium   Price: $1.75
 
Drink 2: Lemonade
Size: Large   Price: $2.00    Sugar: Unsweetened
 
Drink 3: Lemonade
Size: Small   Price: $1.50    Sugar: Sweetened
 
You created 3 drink orders. Thanks for using this program!

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
