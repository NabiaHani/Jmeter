
# Books API JMeter Test Plan

## Endpoints Used
- POST /books/authToken
- GET /books
- POST /books
- PUT /books/{id}
- DELETE /books/{id}

## Base URL
http://localhost:3000

## Files Included
- test-plan.jmx (JMeter test plan)
- data.csv (Data-driven POST input)
- post-book.json (Sample JSON payload)

## How to Run
1. Open `test-plan.jmx` in JMeter
2. Update Thread Group settings if needed
3. Ensure server name and port match API
4. Run the test & view results

## Description
This JMeter test automates full CRUD flow with token authorization and CSV-based data testing.
