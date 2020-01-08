# **Requirements for Recip.me project**

**Table of Contents**

[1   Introduction.. 4](#_Toc84330316)

[1.1    Overview.. 4](#_Toc84330317)

[1.2    Goals and Objectives. 4](#_Toc84330318)

[1.3    Scope. 4](#_Toc84330319)

[1.4    Definitions. 5](#_Toc84330320)

[1.5    Document Conventions. 5](#_Toc84330321)

[1.6    Assumptions. 5](#_Toc84330322)

[2   General Design Constraints.. 6](#_Toc84330323)

[2.1    Product Environment 6](#_Toc84330324)

[2.2    User Characteristics. 6](#_Toc84330325)

[2.3    Mandated Constraints. 6](#_Toc84330326)

[2.4    Potential System Evolution. 6](#_Toc84330327)

[3   Nonfunctional Requirements.. 7](#_Toc84330328)

[3.1    Operational Requirements. 7](#_Toc84330329)

[3.2    Performance Requirements. 7](#_Toc84330330)

[3.3    Security Requirements. 7](#_Toc84330331)

[3.4    Safety Requirements. 7](#_Toc84330332)

[3.5    Legal Requirements. 7](#_Toc84330333)

[3.6    Other Quality Attributes. 7](#_Toc84330334)

[3.7    Documentation and Training. 7](#_Toc84330335)

[3.8    External Interface. 7](#_Toc84330336)

[3.8.1    User Interface. 8](#_Toc84330337)

[3.8.2    Software Interface. 8](#_Toc84330338)

[4   System Features.. 8](#_Toc84330339)

[4.1    Feature: Recipes Visualization. 8](#_Toc84330340)

[4.1.1    Description and Priority. 8](#_Toc84330341)

[4.1.2    Use Case: Unregisterd User Visits Website. 8](#_Toc84330342)

[4.1.3    Additional Requirements. 9](#_Toc84330343)

[4.1.4    Description and Priority. 9](#_Toc84330344)

[4.1.5    Use Case: User Visits Recip.me. 9](#_Toc84330345)

[4.1.6    Additional Requirements. 9](#_Toc84330346)

[4.2    Feature: Registration and Login Process. 10](#_Toc84330350)

[4.2.1    Description and Priority. 10](#_Toc84330351)

[4.2.2    Use Case: Enter Registration Information. 10](#_Toc84330352)

[4.2.3    Additional Requirements. 11](#_Toc84330353)

[4.2.4    Description and Priority. 11](#_Toc84330354)

[4.2.5    Use Case: Login Process. 11](#_Toc84330355)

[4.2.6    Additional Requirements. 11](#_Toc84330356)

[4.3    Feature: Recipe Submission, Download and Selection. 11](#_Toc84330357)

[4.3.1    Description and Priority. 11](#_Toc84330358)

[4.3.2    Use Case: Recipe Submission. 12](#_Toc84330359)

[4.3.3    Additional Requirements. 12](#_Toc84330360)

[4.3.4    Description and Priority. 12](#_Toc84330361)

[4.3.5    Use Case: Recipe Download. 12](#_Toc84330362)

[4.3.6    Additional Requirements. 13](#_Toc84330363)

[4.3.7    Description and Priority. 13](#_Toc84330364)

[4.3.8    Use Case: Recipe Selection. 13](#_Toc84330365)

[4.3.9    Additional Requirements. 13](#_Toc84330366)

Authors

Adami Christian, Lucchese Riccardo, Segala Federico, Rossignolo Davide, Magrinelli Simone, Piccoli Davide, Bothalage Nimesh, El Amri Ilias

# 1      Introduction

## 1.1  Overview

Recip.me is a website that allows users and food fans to communicate with each other by sharing recipes and rate them. Recip.me distinguishes itself from the other food web-services for the openness and the wide choice that it offers product-wise. The project is going to expand itself in order to welcome food providers and producers.

## 1.2  Goals and Objectives

The main goals of this application will be to develop a recipe database that will provide the following:

1. Collect recipes that the users will upload.
2. Allow users to submit feedback and change the recipes.
3. Allow users to order the products directly from the website.
4. Allow users to create a personal customed account.
5. Allow user to change temporarily the ingredients of a recipe     while performing the order.

## 1.3  Scope

Recip.me will collect recipes into a SQL server and users through the websites will be able to retrieve it and rate it. Also every user will have its own account saved by the server. The website will also collect and redirect the orders to a certified food provider.

## 1.4  Definitions

**Use case** – describes a goal-oriented interaction between the system and an actor. A use case may define several variants called scenarios that result in different paths through the use case and usually different outcomes.

**Scenario** – one path through a use case

**Actor** – user or other software system that receives value from a use case.

**Role** – category of users that share similar characteristics.

**Product** – what is being described here; the software system specified in this document.

**Application** – what is being described here; the software system specified in this document.

**Project** – activities that will lead to the production of the product described here. Project issues are described in a separate project plan.

## 1.5  Document Conventions

No document conventions needed.

## 1.6  Assumptions

In order to use the website the user must have a functioning browser and a proper internet connection.



# 2   General Design Constraints

## 2.1  Product Environment

The product will be hosted by altervista.org and the data will be stored into an SQL server.

## 2.2  User Characteristics

In order of increasing priority, the following categories of users can be distinguished for this website:

·     Website Administrators, who will control and manage the website in order to keep it up and running.

·     Users, who will upload and view recipes.

·     Guests, who will view the recipes.

## 2.3  Mandated Constraints

The following constraints have been identified for this project:

- The application needs to be written in HTML, CSS, PHP and SQL.

## 2.4  Potential System Evolution

The system will probably welcome food providers and producers and it will let the user decide which one they’ll order from.



# 3   Nonfunctional Requirements

## 3.1  Operational Requirements

- The application has to allow different users to view and submit     recipes, while allowing them to order products and rate the previously     mentioned recipes. 

## 3.2  Performance Requirements

No performance requirements have been identified for this application.

## 3.3  Security Requirements

Safe connections and data storage will be implemented in order to ensure privacy.

## 3.4  Safety Requirements

No safety requirements won’t be implemented.

## 3.5  Legal Requirements

Data will be gathered only with the consent of the user and it will be stored with the utmost security and discretion. The website will follow the current privacy law.

## 3.6  Other Quality Attributes

The application also needs to possess the following attributes:

o  The website will adapt the recipes to the users information entered during the registration process.

## 3.7  Documentation and Training

A small and quick tutorial will be presented to the users after the registration process.

## 3.8  External Interface

### 3.8.1  User Interface

The registration and account settings will be modified through a simple form implemented through HTML. Recipes will also use forms to be submitted and consequently posted.

Comments will be posted through a form under the recipe page.

### 3.8.2  Software Interface

The web pages will be hosted and managed through altervista.org.



# 4   System Features

## 4.1  Feature: Recipes Visualization

### 4.1.1  Description and Priority

Cost: null

Risk: low

Value: high

### 4.1.2  Use Case: Unregistered User Visits Website

**Actors:** Guest

**Description:** This case happens when an unregistered user visits and uses the website

**Basic Path:** 

1. The website lets the guest view     the recipes.
2. In case of other actions, the     website will redirect the user to the login page.

### 4.1.3  Additional Requirements

No additional requirements needed.

### 4.1.4  Description and Priority

Cost: null

Risk: low

Value: high

### 4.1.5  Use Case: User visits Recip.me

**Actors:** Registered user

**Description:** The user tries to view, modify, submit and rate recipes.

**Basic Path:** 

1. After the login or registration     process, the user is able to do the actions mentioned before.

## 4.2  Feature: Registration and Login Process

### 4.2.1  Description and Priority

Cost: medium

Risk: low

Value: high

### 4.2.2  Use Case: Enter Registration Information

**Actors:** Unregistered user

**Description:** This happens when a user registers themselves for the first time. 

**Basic Path:** 

1. The web user will enter a valid     e-mail and password.

### 4.2.3  Additional Requirements

The database will remember the user by saving its information.

### 4.2.4  Description and Priority

Cost: null

Risk: low

Value: high

### 4.2.5  Use Case: Login Process

**Actors:** Registered user

**Description:** A registered user wants to access its account. 

**Basic Path:** 

1. The user access the login page and     inserts its account information: e-mail and password.

**Alternate path:**

1. If the user tries to edit     information on a house that is not in the database, the application will     return an error and prompt him/ her to enter information on the house     first.

### 4.2.6  Additional Requirements

No additional requirements needed.

## 4.3  Feature: Recipe Submission, Download and Selection

### 4.3.1  Description and Priority

Cost: null

Risk: low

Value: high

### 4.3.2  Use Case: Recipe Submission

**Actors:** Registered User

**Description:** The user wants to add a recipe. 

**Basic Path:** 

1. The user clicks onto the specific     button and he is redirected to the specific form. The database then registers the recipe     and an additional page is created.

### 4.3.3  Additional Requirements

N/A

### 4.3.4  Description and Priority

Cost: medium

Risk: low

Value: high

### 4.3.5  Use Case: Download Recipes

**Actors:** Registered user

**Description:** The user decides to download a recipe. 

**Basic Path:** 

1. The user clicks onto the special     button and the recipe is automatically downloaded.
2. The user can also save the recipe     through another special button.

### 4.3.6  Additional Requirements

N/A

### 4.3.7  Description and Priority

Cost: medium

Risk: low

Value: high

### 4.3.8  Use Case: Recipe Selection

**Actors:** Registered user.

**Description:** The user decides to order the recipe. 

**Basic Path:** 

1. The user clicks onto the order button and the ingredients (changed or not) are put into their cart.

### 4.3.9  Additional Requirements

No additional requirements needed.

 

 
