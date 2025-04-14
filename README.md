# Healthcare API Testing Project

This project simulates API testing for a healthcare backend system that manages patients, appointments, and authentication.

## Project Overview

The goal of this project is to demonstrate skills in:
- REST API validation
- Testing authentication and authorization
- Schema validation and error handling
- Using Postman and Newman for testing
- Backend data verification with SQL

## Tools & Technologies

- Postman (collections and test scripts)
- Swagger (API documentation reference)
- JSON, JavaScript (Postman tests)
- SQL (backend validation – not included in repo)
- GitHub

## Sample Test Scenarios

- Valid login with auth token
- Invalid login (wrong password, missing token)
- Get patient by ID
- Create patient with missing fields
- Unauthorized access to protected endpoints

## How to Run

1. Import the collection `PatientAPI.postman_collection.json` into Postman  
2. Set environment variables if needed (e.g., `base_url`, `token`)  
3. Click “Run” in Collection Runner  
4. For CLI: use Newman  
```bash
newman run PatientAPI.postman_collection.json
