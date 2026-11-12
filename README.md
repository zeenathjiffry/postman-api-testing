# Postman API Testing

API tests for the Restful Booker API using Postman and Newman.

## What is tested
- Token authentication
- Create, read, update and delete bookings
- Negative cases: missing token (403), deleted booking (404)

## Tools used
- Postman (collections, environments, JavaScript test scripts)
- Newman CLI with HTML reports

## How to run
1. Install Node.js
2. Run `npm install -g newman newman-reporter-htmlextra`
3. Run `newman run collection.json -e environment.json -r htmlextra`

## Test report
(screenshot coming soon)
