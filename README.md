I developed a content management system application using Rails 5 used for: 

* generating PDF for gas verification of central heating systems,
* generating PDF for periodic technical verification form,
* managing customers

## Customers

Implemented CRUD operations for customers.

![](images/Customer.png)

On the show page, we can manage customer's VTPs, gas verifications, addresses, combustion plants, and gas installations.

![](images/Customer-show.png)

Implemented CRUD operations for VTP.

![](images/Customer-all-vtp.png)

Implemented VTP form(snippet)

![](images/Customer-create-vtp.png)

Generated PDF after the form is completed(snippet)

![](images/VTP-pdf.png)

Implemented CRUD operations for gas verification  

![](images/Customer-gas-v-show.png)

Implemented gas verification form(snippet)

![](images/Customer-gas-verification.png)

Generated PDF after the form is completed(snippet)

![](images/pdf-gas-v.png)

## Users

In this application, I added two types of users
  * Admin user
  * Normal user
  
As an admin, you can see and modify everything in the application

As a normal user, you can modify customers details, add and edit VTP and gas verification

**as an admin user**

![](images/user.png)

**as a normal user**

![](images/user-no.png)

## Analyzers

This is a tool used to verify the gas installation 

Implemented CRUD operations for analyzer

![](images/Analizer.png)

## Companies

Company details 

![](images/Company.png)








