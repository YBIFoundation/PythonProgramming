# **Object Oriented Programming**

The books and other publications, which a library offers, are like the data in an object-oriented program. 
Access to the books is restricted like access to the data is restricted in OOP. 
Getting or returning a book is only possible via the staff. 
The staff functions like the methods in OOP, which control the access to the data. So, the data, - often called **attributes**, - 
in such a program can be seen as being hidden and protected by a shell, and it can only be accessed by special functions, usually called **methods** in the OOP context. 
Putting the data behind a "shell" is called **Encapsulation**. So a library can be regarded as a **class** and a book is an **instance or an object** of this class. 
Generally speaking, an object is defined by a class. A class is a formal description of how an object is designed, i.e. which attributes and methods it has. 
These objects are called instances as well. The expressions are in most cases used synonymously. 
A class should not be confused with an object.


Data Abstraction, Data Encapsulation and Information Hiding are often synonymously used in books and tutorials on OOP. However, there is a difference. Encapsulation is seen as the bundling of data with the methods that operate on that data. Information hiding on the other hand is the principle that some internal information or data is "hidden", so that it can't be accidentally changed. Data encapsulation via methods doesn't necessarily mean that the data is hidden. You might be capable of accessing and seeing the data anyway, but using the methods is recommended. Finally, data abstraction is present, if both data hiding and data encapsulation is used. In other words, data abstraction is the broader term:

**Data Abstraction = Data Encapsulation + Data Hiding**

Encapsulation is often accomplished by providing two kinds of methods for attributes: The methods for retrieving or accessing the values of attributes are called getter methods. Getter methods do not change the values of attributes, they just return the values. The methods used for changing the values of attributes are called setter methods.
