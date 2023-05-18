# Stock Management System
The Stock Management System is a web-based application built using Spring Boot. It provides a set of RESTful endpoints to manage stocks, including retrieving stocks by type, price, and date, updating stock information, inserting new stocks, and deleting stocks based on owner count.

## Framework
The Stock Management System is developed using the following technologies and frameworks:
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- RESTful API

## Endpoints
The Stock Management System exposes the following endpoints:
- **GET /stock/type/{stockType} -** Retrieves stocks based on the specified stock type.
- **GET /stock/abovePrice/price/{price}/lowerData/date/{date} -** Retrieves stocks above a certain price and lower than a specific date.
- **GET /stock/cap/{capPercentage} -** Retrieves all stocks above a certain market cap percentage.
- **POST /stock/ -** Inserts new stocks into the system.
- **PUT /stock/marketCap/{marketCap}/id/{id} -** Updates the market cap of a stock by its ID.
- **PUT /stock/stock/type/id -** Updates the stock type of a stock by its ID.
- **PUT /stock/stock/{id} -** Updates stock information by its ID.
- **DELETE /stock/ownerCount/{count} -** Deletes stocks based on the owner count.

## How to Use
To use the Stock Management System, follow these steps:
- Clone the repository or download the project files.
- Import the project into your preferred Java development environment.
- Set up the necessary dependencies and configurations (e.g., database configuration).
- Build and run the application.
- Access the endpoints using an HTTP client (e.g., cURL, Postman, or a web browser) by sending requests to the appropriate URL and HTTP method.
- Make sure to provide the required request parameters and payload as specified in the endpoint documentation.

## Summary
The Stock Management System is a Spring Boot application that provides a RESTful API for managing stocks. It allows users to retrieve stocks based on type, price, and date, update stock information, insert new stocks, and delete stocks based on owner count. By following the provided endpoint documentation and using the appropriate HTTP methods and request parameters, users can interact with the system to perform various stock management operations.
