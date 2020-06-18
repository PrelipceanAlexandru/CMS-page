I developed a content management system application using Rails 5 used for: 

* generating PDF for gas verification of central heating systems,
* generating PDF for periodic technical verification form
* managing customers

The application was hosted on Amazon EC2 Instance

## Customer

CRUD operation for customers

![](images/Customer.png)

On show page we can manage customer's VTPs, Gas verification, addresses, combustion plants and gas installations.

![](images/Customer-show.png)

VTP CRUD opperations

![](images/Customer-all-vtp.png)

VTP form(snippet)

![](images/Customer-create-vtp.png)

Generated PDF after the form is completed(snippet)

![](images/VTP-pdf.png)

Gas Veriffication CRUD opperations

![](images/Customer-gas-v-show.png)

Gas Veriffication form(snippet)

![](images/Customer-gas-verification.png)

Generated PDF after the form is completed(snippet)

![](images/pdf-gas-v.png)

## Users

In this application I added 2 types of users
  * Admin user
  * Normal user
  
As admin you can see and modify everything in the applicatino

As normal user you can modify customer details, add and modify VTP and Gas Veriffication

**as admin user**

![](images/user.png)

**as normal user**

![](images/user-no.png)

## Analyzer

This is a tool used to verify gas instalation 

CRUD opperations for analizer

![](images/Analizer.png)

## Company

Company details 

![](images/Company.png)








