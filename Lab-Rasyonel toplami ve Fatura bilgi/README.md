1. Step
	Create a class called Invoice that a hardware store might use to represent an invoice for an item sold at the store. An Invoice should include four pieces of information as either instance variables or automatic properties�a part number (type string), a part description (type string), a quantity of the item being purchased (type int) and a price per item (decimal). Your class should have a constructor that initializes the four values. Provide a property with a get and set accessor for any instance variables. For the Quantity and PricePerItem properties, if the value passed to the set accessor is negative, the value of the instance variable should be left unchanged. Also, provide a method named GetInvoiceAmount that calculates the invoice amount (i.e., multiplies the quantity by the price per item), then returns the amount as a decimal value. Write a test application named InvoiceTest that demonstrates class Invoice�s capabilities.

2. Step
	Create class Rectangle. The class has attributes length and width, each of which defaults to 1.  It has read-only properties that calculate the Perimeter and the Area of the rectangle. It has properties for both length and width. The set accessors should verify that length and width are each floating-point numbers greater than 0.0 and less than 20.0. Write an application to test class Rectangle.

3. Step
	Create a class called Rational for performing arithmetic with fractions. Write an application to test your class. Use integer variables to represent the private instance variables of the class�the numerator and the denominator. Provide a constructor that enables an object of this class to be initialized when it�s declared. The constructor should store the fraction in reducedform. The fraction 2/4 is equivalent to 1/2 and would be stored in the object as 1 in the numerator and 2 in the denominator.  Provide a parameterless constructor with default values in case no initializers are provided. Provide public methods that perform each of the following operations (all calculation results should be stored in a reduced form):

* Add two Rational numbers.
* Subtract two Rational numbers.
* Multiply two Rational numbers.
* Divide two Rational numbers.
* Display Rational numbers in the form a/b, where a is the numerator and b is the denominator.
* Display Rational numbers in floating-point format. (Consider providing formatting capabilities that enable the user of the class to specify the number of digits of precision to the right of the decimal point.)
