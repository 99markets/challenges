# Ninety Nine Mobile Challenge

## Description

Congratulations! As the new member of the **Ninety Nine** iOS/Android team, you are in charge of implementing one of the new features that will drive millions of users into our *fintech* app. 

This feature contains 2 screens to:

a) List the stocks the user has stored as favorites.

b) Show the details for one favourite stock.

To retrieve the information, you can use these two REST endpoints created by the Backend team:

- https://challenge.ninetynine.com/favorites
- https://challenge.ninetynine.com/favorites/123

Your job is to create an app from scratch that:

- Shows the list of favorites, and when the user taps on one, shows its details. This list must include name and the indicator for hot stocks.
- Implement a mem-cache for offline cases *(extra points)*
- Add one button to each cell to delete a favorite. If you press that button your favorite will not be shown anymore in your list (no need to persist the deletion). *(extra points)*

## **Requirements**

- The exercise must be done in **Swift** for **iOS** positions and **Kotlin** for **Android** positions
- Feel free to use any library, tool or pattern you usually use
- Extra kudos if you use **Courutines**/**Combine**/**Rx** (We use it extensively)

## **The code should:**

- Be written as **production-ready** code, think about what are the minimum requirements to deploy a proyect to production
- *"Be clean, my friend"*
- Feel free to add a Readme file explaining the solution, why certain things are included and why others are left out

We hope you have fun! We appreciate your time completing this exercise.
