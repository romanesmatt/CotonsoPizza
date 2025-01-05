# ContosoPizza API

A RESTful API using ASP.NET Core to manage a pizza inventory system. Implemented full CRUD operations (Create, Read, Update, Delete) following Microsoft's official learning path. This project demonstrates my journey learning C# web development and API design principles using industry-standard practices.

## Features

- Create new pizzas with customizable properties
- Retrieve individual or list all pizzas
- Update existing pizza details 
- Delete pizzas from inventory
- HTTP response codes following REST standards
- Stateless API design

## Technologies

- ASP.NET Core 8.0
- C# 
- REST Architecture
- HttpRepl for testing

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /pizza | Get all pizzas |
| GET | /pizza/{id} | Get pizza by ID |
| POST | /pizza | Create new pizza |
| PUT | /pizza/{id} | Update existing pizza |
| DELETE | /pizza/{id} | Delete pizza |

## Learning Resources

This project was built following the [Create web APIs with ASP.NET Core controllers](https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/) learning module from Microsoft.
