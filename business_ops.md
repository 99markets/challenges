# Ninety Nine Business Operations Challenge

## **Description**

Congratulations! As the new member of the **Ninety Nine Business Operations** team, you are trusted with the implementation and maintenance of the internal tools that allow the company to operate on a daily basis.

The objective for this exercise is to create a simple dashboard with the information of a new product that has been added to our apps: cryptocurrencies. This will allow other teams to understand status of the assets and fluctuation in price at the end of the day that might require changes in the offering.

To obtain the raw data, you will be able to use Coincap, an open data API that provides lots of info about crypto: https://docs.coincap.io/

## **Requirements**

- Create a simple, static dashboard displaying the top 10 cryptos by market cap in USD. Include for each crypto (always use 2 decimals):
   1) Name
   2) Market cap
   2) Last price in USD
   3) Last price in EUR
- Use the following stack: MongoDB as the database, a service in Kotlin or Node, and Vue.js or React as the front end framework.
- We don't want to rely in Coincap stability: all data should be first persisted in the DB and read from there.
- Add a basic layer of tests you would consider important (no need to be comprehensive, we just want to understand how you would structure them)
- No need to do any complex implementations, if you feel creative add a Readme file with things you would include in a second iteration.

## **Deliverables**

- Zip file or private repo with code and Docker to run the dashboard, plus Readme with how to run it.

We hope you have fun! We appreciate your time completing this exercise.