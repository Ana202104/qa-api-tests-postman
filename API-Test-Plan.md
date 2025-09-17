# API Test Plan – Sample Project

This project validates a public REST API (JSONPlaceholder) using Postman.

## Objectives
- Verify success responses for valid requests
- Validate error handling for invalid requests
- Keep tests organized and reproducible

## Scope
- `GET /users`
- `GET /users/{{userId}}`
- `POST /users`
- `PUT /users/{{userId}}`
- `DELETE /users/{{userId}}`

## Tools
- Postman Collection + Environment
- Variables: `baseUrl`, `userId`

## Execution
1. Import collection and environment into Postman
2. Select **Sample-Env**
3. Run the Collection

## Deliverables
- Collection JSON
- Environment JSON
- This Test Plan

## Skills Demonstrated
API Test Design • REST Validation • Documentation • Detail Orientation
