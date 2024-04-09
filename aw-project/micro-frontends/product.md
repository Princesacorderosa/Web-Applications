ADR:

#-----------
# 5. Products.md

## Context
The user can be informed about the best-rated products, and search in a specific supermarket for the available products, organized by categories. They can select a product to obtain more details, view feedback from other users, and contribute with their rating. 

## Responsibility of the micro-frontend
This micro-frontend is responsible for managing the list of products available. Displaying in the highlights section the best-rated ones, and organizing by categories the products available by store.   
Display more detailed information about the selected product, providing the possibility for the user to save the product and/or see and give feedback (rating).

## Decision
This micro-frontend is an easy way to organize the products and facilitates the user search for the desired product.
This can be reused by applications that have their content stored in databases, and require a UI (user interface) for users to view the database items in an organized way.
For this micro-frontend a product management team would be responsible for organizing and displaying the products in a structured way, constantly updating the product information and availability list. 


