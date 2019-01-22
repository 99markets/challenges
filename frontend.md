# Ninety Nine Frontend Challenge

## Description

As **Ninety Nine** is a *fintech* company we want to create a frontend system that interacts and fetches info about the most important companies of the world.

To simulate one of our third party data providers we have created two endpoints to get the necessary information:

- GET List of Companies: https://dev.ninetynine.com/testapi/1/companies
- GET Company info by ID: https://dev.ninetynine.com/testapi/1/companies/{companyId}

Each time you call on any of this endpoints the company share price changes.

The frontend system you are going to build should be a **S**ingle-**P**age **A**pplication. We need to see a list of companies. We can also access the detail of the company in a new route. 

Your frontend system should expose in its own endpoints (using REST routes) the following info:

- Index of companies.
- Company detail.
- Generate a graph with the price in the detail of the company that is updated dynamically, at least every 15 seconds. The price changes in each detail request.

## Requirements

- The project must be done using either **React**.
- For Javascript, you should use **ECMAScript 6**.
- For styles, we like BEM and SASS, but you can use another alternative.
- For dependency management, we like **Yarn**, but you can use another alternative.
- Feel free to use any library, tool or pattern you usually use.

## The code should:

- Be written as production-ready code.
- *"Be clean, my friend"*.
- Think on code scalability and maintainability.
- Have detailed notes attached, explaining the solution, why certain things are included and why others are left out.

Last but not least, have fun and take your time to do it.
