 

 

# Test Case Specification

**For Team 2**

April 17, 2020



















Prepared by:

Adami Christian, Bothalage Nimesh, El Amry Ilias, Lucchese Riccardo, Magrinelli Simone, Piccoli Davide, Rossignolo Davide, Segala Federico











**Table of Contents****
**

**1  INTRODUCTION.……..…….……………………………………….4**

**2**   **TEST CASES: iOS Application, Android Application, Site…...……………..4***
*



*Revision History*

| **Version** | **Date**   | **Name**                                                     | **Description**  |
| ----------- | ---------- | ------------------------------------------------------------ | ---------------- |
| 1           | 17/04/2020 | Adami Christian, Bothalage Nimesh, El Amry Ilias, Lucchese Riccardo, Magrinelli Simone, Piccoli Davide, Rossignolo Daivide, Segala Federico | Initial Document |





1. **Introduction**



This document provides the test cases to be carried out for the Recipe.me application. Each item to be tested is represented by an individual test case.  Each case details the input and expected outputs.





1. **Test Cases: iOS Application, Android Application, Site**

| Test ID          | 2.1                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Correct Login                                                |
| Feature          | Login to www.recipe.me with Recipe.me application.           |
| Objective        | Confirm that proper user id and password yields access to the website. |
| Setup            | The Recipe.me application is ready to run on IOS device and Android device. |
| Test Actions     | You start Recipe.me application, select Sign in option and then enter with login information. |
| Expected Results | System makes you see, comment and order the recipes you want. |





| Test ID          | 2.2                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Incorrect Password                                           |
| Feature          | Login to www.recipe.me with Recipe.me application.           |
| Objective        | If the user id is correct but the password is not the access to the website is denied. |
| Setup            | The Recipe.me application is ready to run on IOS device and Android device. |
| Test Actions     | You start Recipe.me application, you select Sign in optionand then enter invalid login information. |
| Expected Results | System displays error message with option to try again.      |



| Test ID          | 2.3                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Incorrect User E-Mail                                        |
| Feature          | Login to www.recipe.me with Recipe.me application.           |
| Objective        | If the user id isn’t correct the access to the website is denied. |
| Setup            | The Recipe.me application is ready to run on IOS device and Android device. |
| Test Actions     | You start Recipe.me application, you select Sign in optionand enter invalid login information. |
| Expected Results | System displays error message with option to try again.      |





| Test ID          | 2.4                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Select Option See Receipe.                                   |
| Feature          | Display recipes you want to see.                             |
| Objective        | A list of recipes must appear to the user.                   |
| Setup            | The Recipe.me application is ready to run on IOS device and Android device. |
| Test Actions     | You start Recipe.me application and select See Recipe option. |
| Expected Results | System displays list of recipes.                             |





| Test ID          | 2.5                                                          |
| ---------------- | ------------------------------------------------------------ |
| Title            | Select Option Order Ingredients.                             |
| Feature          | Display the ingredients you want to order.                   |
| Objective        | Confirm that order made rightly.                             |
| Setup            | The Recipe.me application is ready to run on IOS device and Android device. |
| Test Actions     | You start Recipe.me application, select See Recipe option and select Order Ingredients option. |
| Expected Results | System must orders the ingredients you choose for the recipe. |