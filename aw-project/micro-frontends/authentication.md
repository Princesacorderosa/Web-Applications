ADR:

#-----------
# 1. Authentication.md

## Context
To use the app, the user needs to authenticate. Either by logging into an existing account or registering.

## Responsibility of the micro-frontend
This micro-frontend has the responsibility to handle the authentication services, such as login (email and password), password recovery, and registration of new users.

## Decision
This micro-frontend allows for a simple and easy way to manage the authentication services. It can be reused by other apps that require login of the user in order to be accessed.
would be needed a team specialized in the development and management of authentication services, that would handle the login data (email and password) (check if the input corresponds to a valid existent user).

