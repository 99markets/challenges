# Ninety Nine Backend Challenge

## Description

As **Ninety Nine** is a *fintech* company we want to create a backend system that interacts and fetches info about the most important companies of the world.

To simulate one of our third party data providers we have created two endpoints to get the necessary information:

- GET List of Companies: https://dev.ninetynine.com/testapi/1/companies
- GET Company info by ID: https://dev.ninetynine.com/testapi/1/companies/{companyId}

Each time you call on any of this endpoints the company share price changes.

The backend system you are going to build should create background jobs to get the information about the companies. As each company *share* price changes almost in real time, the company info should be refreshed at least every 20 secs in order to show the current real *share* price.

Your backend system should expose in its own endpoints (using REST routes) the following info using the JSON:API standard:

- List of companies
- Info by company
- Time series of the company share price. It should support hourly, daily and weekly time series.

## Requirements

- The project must be done using either **Java** or **Kotlin**.
- Use any framework you are confortable with, we usually use **Hibernate** and **Micronaut**.
- Feel free to use any library, tool or pattern you usually use.
- At ninety nine we make use of **Rx**, it would be a plus if you show us how you use it.

## The code should:

- Be written as production-ready code.
- *"Be clean, my friend"*.
- Think on code scalability and maintainability.
- Have detailed notes attached, explaining the solution, why certain things are included and why others are left out.

Last but not least, have fun and take your time to do it.
