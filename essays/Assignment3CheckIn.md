---
layout: essay
type: essay
title: Assignment 3 Check In
# All dates must be YYYY-MM-DD format!
date: 2020-12-3
labels:
  - Check In
---
## Assignment3 Check In
---

---
###Checkpoint A:
Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
---

I want to design my shopping cart as a separate page that the user can view and edit. When users choose a product, it will show up in the shopping cart and from there they can choose whether delete it or add another quantity by one. The page will then reload with their new totals. They will be able to go back to the products page if they wish to buy another product and add it to the cart, if not they can leave with the products in their shopping cart.   
---
###Checkpoint B:
Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will be used in $_SESSION.
---
  I will use sessions to add or delete product quantities in the shopping cart. I will use an array to store the data. The object will hold the product name and quantity to keep track of what the user decides to purchase. 

When adding items into the shopping cart it will increase the quantity under the product name. 

products = { prod1, prod2, prod3 prod4, prod5};

for (i = 0; i < products.length; i++){

	products[i].quantity = quantity[i]; //add the quantity the user wants to the object holding that product. 

 }

//in the shopping cart 
//display the product they chose to purchase. 
//Under the product have an option to increase or decrease the quantity by 1
if (user presses + button)
	product.quanitity++;
	document.write (`${product.name} + ${product.quantity}`);
else //user presses - button {
	product.quantity - -;
	document.write (`${product.name} + ${product.quantity}`);
}
---
###Checkpoint C:
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
---
I will avoid access to my application by not showing a real products page that the user can purchase from, until they sign in or register. Then they will be able to select their products. Security concerns are if the user can look at the url for the real products page and select products from there, so the next session they can skip over sign in and go straight to purchasing items.   

---
###Checkpoint D:
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):
---
I will change the name at the top of the page to say welcome ${user}.   

---
###Checkpoint E:
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
---
If I decide to work with partners I think each of use working to solve one problem at a time might be more efficient than handing out assignments and trying to get it all to fit together. That way we can have two people working on one problem and move onto the next instead of having multiple pages that don’t go together.    

---
###Checkpoint F:
How are you approaching Assignment 3 differently than Assignment 2?
---
I will approach assignment 3 differently by working on simple problems that I know how to solve, then work on the more difficult programming, like using the shopping cart. I will also ask for lots of help in advance from the professor on design of the program, so I don’t work on it and then get stuck and then have to restart and delete a lot of code because it was not a good way to handle the problem. 
