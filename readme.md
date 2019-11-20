### ###################################################### ###
### ################### ARCHITECTURE ##################### ###
### ###################################################### ###

. Frameworks - ReactJs, MongoDB, Mongoose, Express
. Security - Token authentication int browser cookie
. Create-react-app used for front end template
. node-express-mongo used to back end template
. react-bootstrap and bootstrap will be used for styling components
. React application request to Express server using Mongoose to interact with mongodb

### INTRODUCTION ###

. This piece of software is used to create, view, edit and delete invoices. 
. Invoices are linked to customers which has addresses
. Email functionality will be implemented 

### ###################################################### ###
### ################### REQUIREMENTS ##################### ###
### ###################################################### ###

### FUNCTIONAL REQUIREMENTS ###
. Create customer
. Edit customer
. Create invoice
. Edit invoice
. Delete invoice
. View invoices
. Login - facebook, google, local
. send invoice as email (not required for now)
. user login
. user register

### USER STORIES ###

. Customer
    . as a user, i want to capture the following details for the customer:
        . name
        . company name
        . vat number
        . contact numbers
        . account number        
        . date created
        . _id created
        . invoce number _id,
        . bill to address
        . deliver to address
        . emal
        to create a customer

    . as a user i want to edit a customers details
    . as a user, i want to view a list of customers
    . as a user, i want to search a customer

. Invoice 
    . as a user, i want to capture the following details for an invoice:
        . date created
        . invoice number _id
        . invoice item id
        . nett price
        . vat 
        . total amount,
        to create an invoice

    . as a user, i want to delete an invoice
    . as a user, i want to search for a invoice
    . as a user, i want to edit an invoice

. Invoice Item
    . as a user, i want to capture the following details for an invoice item:
        . invoice id
        . item description        
        . unit price
        . quantity
        . nett price       
        . vat 
        . total amount
    . as a user, i want to delete a line item
    . as a user, i want to edit a line item
        
. User
    . as a user, i want the following details captured:
        . user id _id
        . first name
        . last name
        . created date
        . role
        . email
        . contact number
        
    . as a user, i want to login using google, facebook, local
    . as a user, i want to be registered if i dont exist
    . as a user, if i dont have a company name and address, i need to be prompt to insert these


### NON FUNCTIONAL REQUIREMENTS ###
. Deploy to Heroku