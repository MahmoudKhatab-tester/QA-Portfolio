# Book Store API Testing Project

## Overview
This project demonstrates API testing for a Book Store application using Postman.  
It covers multiple modules including products, cart, orders, and authentication.

## Scope
- Products APIs
- Cart APIs
- Orders APIs
- Authentication APIs

## APIs Tested
- Get all products
- Get single product
- Create cart
- Add item to cart
- Update and delete cart items
- Create order
- Get order details
- API authentication

## Testing Activities
- Validated status codes (200, 201, 204)
- Verified response body and data correctness
- Implemented automated test scripts using Postman
- Used collection variables for dynamic data handling (Cart ID, Item ID, Token)
- Executed end-to-end scenario (Create cart → Add item → Create order)

## Automation
- Added test scripts to validate:
  - Response status
  - Response structure
  - Business logic (e.g. created = true)
- Used Postman Collection Runner for execution

## Tools Used
- Postman
- JavaScript (for test scripts)

## Key Features
- Dynamic variables handling
- API chaining (linking multiple requests together)
- Authentication using Bearer Token
- End-to-end testing scenario

## How to Run
1. Import the collection into Postman
2. Set the Base URL
3. Run the collection using Collection Runner

