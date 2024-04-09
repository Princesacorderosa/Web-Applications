#-----------
# 6. Saved.md

## Context
Users can save and view products they are interested in buying later.

## Responsibility of the micro-frontend
This micro-frontend oversees the management of saved items, ensuring efficient storage and retrieval of user-selected content.

## Decision
This list is different from the main product list, containing only the products the users are interested in. This micro-frontend enables users to save products for later viewing, facilitating easy access to items of interest. Can be reused in other applications that allow users to create a list of items of interest.
The team working on this would have to create a design that enables the user to manage its personal saved list (add or delete a product), without impacting the ‘products’ micro-frontend.
