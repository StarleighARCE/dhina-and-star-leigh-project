
ACTIVITY 1. 
![image](https://github.com/user-attachments/assets/f40fc35a-7bcd-4a6e-a2e7-4ce059d466a5)
![image](https://github.com/user-attachments/assets/08644575-a2c1-4076-a798-b5cc2365adbf)


Introduction:
The provided PHP code demonstrates how to define a simple class to manage product data in an e-commerce or inventory system. This code leverages object-oriented programming (OOP) principles to organize and display the key details of a product, such as its name, description, price, category, and stock availability. By encapsulating product-related information and behavior in a single class, the code simplifies the process of managing product data in a structured and maintainable way. In this report, we will break down the code step by step, explain its functionality, and analyze its key components.

Body:
Class Definition (Product Class): The code begins by defining a class named Product. A class in object-oriented programming is like a blueprint that describes how an object should be created and what properties and methods it will have. The Product class is designed to hold information about a product and has the following public properties:

$name: This property stores the name of the product (e.g., "SmartPhones").
$description: This property stores a description of the product (e.g., "Touchscreen display").
$price: This property stores the price of the product (e.g., "15,999").
$category: This property stores the product’s category (e.g., "Midrange smartphones").
$stock: This property keeps track of the number of units available for sale (e.g., "56").
Method 1: setProduct(): The setProduct() method is used to set the values for the properties of the Product class. It accepts five parameters: $name, $description, $price, $category, and $stock. These parameters are then assigned to the corresponding properties of the class using the $this keyword, which refers to the current instance of the class. The purpose of this method is to allow the creation of a Product object with specific values assigned to its properties.

How It Works:
When a new Product object is created, the setProduct() method is called with specific details about the product. These details are then stored in the object’s properties.
Method 2: getProductInfo(): The getProductInfo() method retrieves the product’s details in a readable format. It concatenates the product’s properties into a single string, including the product name, description, price, category, and stock. The method uses the return statement to send this formatted string back to the calling code.

How It Works:

After the product’s properties are set, calling the getProductInfo() method generates a formatted output that can be easily displayed. This output includes the product’s key information in a human-readable form.
Creating an Object and Using the Methods:

An object of the Product class is created using $product = new Product();. This creates a new instance of the Product class.
The setProduct() method is called on the $product object to assign specific values to the product’s properties. For example, the name is set to "SmartPhones," the description to "Touchscreen display," and so on.
The getProductInfo() method is called to retrieve the formatted product details, which are then displayed using the print() function.
How It Works:

By creating a new Product object and setting its properties, the product information is stored within the object. The getProductInfo() method is then used to fetch this data and display it.
Conclusion:
In conclusion, this PHP code provides a simple but effective way to model and manage product information using object-oriented programming. By defining a Product class with methods for setting and retrieving product details, the code achieves clear data organization and encapsulation. The use of methods like setProduct() and getProductInfo() allows for easy management of product data and simplifies the process of displaying that data in a user-friendly format. This basic structure could easily be expanded to handle additional features such as updating product prices, validating inputs, or handling more complex product information. Overall, this code serves as a solid foundation for managing products in an e-commerce or inventory system.


  ACTVITY 2. The Movie ClasS
  ![image](https://github.com/user-attachments/assets/97088622-f8ad-452f-910d-73e1e04e9e52)
  ![image](https://github.com/user-attachments/assets/f3532ba2-2c23-4c4c-a7d6-984a64c8f9ab)



  Introduction
This report discusses a PHP script that implements a simple Movie class. The class stores and displays movie details such as title, director, genre, year of release, and rating, demonstrating object-oriented programming (OOP) principles in PHP.

Body
The script defines a Movie class with five properties: $title, $director, $genre, $year, and $rating. It includes two methods:

setMovie($title, $director, $genre, $year, $rating): Sets the values for the movie's properties.
getMovieInfo(): Returns a formatted string containing the movie's details.
A Movie object is created, and the setMovie() method is used to assign values for a specific movie, "The Summer That I Turned Pretty." The getMovieInfo() method displays the movie’s information in a readable format.

Conclusion
The script demonstrates basic OOP concepts in PHP, showing how to create and manage a class, set and retrieve object data, and display it dynamically. It highlights the power of PHP in building structured, reusable web applications.

Submitted by:
Starleigh Arce
Dina Respicio
  



