# Trello REST API Testing with Postman

## Project Overview

This personal project focuses on testing the Trello REST API using Postman. It covers API requests for creating, retrieving, updating, and deleting Trello resources.

## Objectives

- Validate API responses and HTTP status codes.
- Verify response data and resource IDs.
- Organize requests into a structured test execution workflow.
- Use JavaScript assertions in Postman to validate responses.
- Reuse resource IDs through collection variables.

## Tools and Technologies

- Postman
- Trello REST API
- JavaScript
- JSON
- HTTP methods: GET, POST, PUT, DELETE

## Test Coverage

The collection includes requests for the following resources:

- Boards
- Lists
- Cards
- Checklists

Tests validate response status codes, response data, and resource IDs, as applicable to each request.

## Project Structure

- `Trello API Testing.postman_collection.json` — Postman requests and test scripts.
- `README.md` — Project overview and execution instructions.

## Prerequisites

- A Postman account or Postman desktop application.
- A Trello account.
- A Trello API key and token configured locally in Postman.

## How to Run the Tests

1. Import the Postman collection into Postman.
2. Configure your own Trello API credentials in a local environment or collection variables.
3. Select the required environment.
4. Run the requests in the appropriate order, starting with resource creation.
5. Review the response status codes and the test results in Postman's Test Results panel.

## Security

API credentials are not included in this repository. Use your own Trello API key and token, and do not share them publicly.

## Author

Personal QA portfolio project demonstrating REST API testing with Postman.
