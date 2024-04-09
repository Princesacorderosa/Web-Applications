#-----------
ADR:
# 2. User_profile.md

## Context
The user profile stores and displays the user information, there the user can update their account details, contact the support, or manage the session (log-out).

## Responsibility of the micro-frontend
This micro-frontend is responsible for storing the user data securely, allowing the user to manage their account details. As well as providing the contact of support.

## Decision
The user profile micro-frontend allows for a simple and easy way to manage the authentication services. It can be reused by other apps that want the information of the user to be displayed.
The team in this micro-frontend would be responsible for deciding what information is displayed in the profile and updating it if the users change any personal details. They are also responsible for having the availability and the responsibility to act on the problem, providing user support in case they request it.
