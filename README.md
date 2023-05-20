# node-register-login

A basic full lifecycle website for registering and logging in

## Lifecycle for register

- check if the incoming email belong to the user list

- bcrypt the password sent from the client

- create the user, save to the user list or database

## Lifecycle for login

- find the user from list or database by its email

- bcrypt.compare( user.password, incomingPassword)

- send token back to user if it's legit
