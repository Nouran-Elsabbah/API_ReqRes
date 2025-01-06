# ReqRes.in API Testing Collection

## Overview
This repository contains a comprehensive Postman collection for testing the ReqRes.in API endpoints. The collection includes various API requests covering user management, resource handling, authentication, and error scenarios.

## Collection Structure
The collection is organized into two main folders:
1. *Passed Requests* - Contains successful API scenarios
2. *Failed Requests* - Contains negative test cases

### Endpoints Covered

#### Successful Scenarios
- List Users (GET)
- List Single User (GET)
- List All Resources (GET)
- List Single Resource (GET)
- Create User (POST)
- Update User (PUT)
- Patch User (PATCH)
- Delete User (DELETE)
- User Registration (POST)
- User Login (POST)
- Delayed Response (GET)

#### Error Scenarios
- Non-existent User Request
- Non-existent Resource Request
- Unsuccessful Registration
- Unsuccessful Login

## Test Coverage

The collection includes extensive test scripts that verify:
- Status codes
- Response times
- JSON schema validation
- Data type validation
- Header validation
- Required field presence
- Specific value validation

### Key Test Assertions
- Response time checks (< 500ms for most requests)
- Status code validation
- JSON schema structure
- Content-Type header verification
- Cache-Control header verification
- Data field validation

## Prerequisites
- Postman
- Environment with base_url variable set to the ReqRes.in API endpoint

## Environment Variables
- base_url: The base URL for the ReqRes.in API
- userid: User ID variable (used in some requests)

## How to Use
1. Import the collection into Postman
2. Set up the environment variables
3. Run individual requests or use the collection runner for full test execution

## Test Execution
All requests include pre-written test scripts that automatically validate the responses. Tests verify:
- Correct HTTP status codes
- Response structure
- Data integrity
- Performance metrics

## Contributing
Feel free to contribute to this collection by:
1. Forking the repository
2. Creating your feature branch
3. Committing your changes
4. Creating a pull request

## License
This project is open-source and available under the MIT License.
