ADR:

#-----------
# 4. QR_Scanner.md

## Context
The QRscanner can be used to scan the code of a product in order to obtain its detailed informations. 

## Responsibility of the micro-frontend
This micro-frontend has the responsability to manage the scanning of QR codes and to display the product associated and its detailed information.

## Decision
This micro-frontend serves as a simple and quick way for users to obtain information about a specific product. It is only focused on scanning qr codes and display the associated product details, which can also be reused in other features or products that require a QRcode scan. To work in this micro-frontend, we could have a team specialized in camera integration and image processing to be responsible for its development and maintenance. It can be deployed independently, allowing for any update or bug fixes without impacting the other features of the app. Also, it has the flexibility to adopt other (more advanced) scanning technologies.