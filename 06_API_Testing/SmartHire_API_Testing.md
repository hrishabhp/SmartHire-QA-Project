# APIs Covered

- Login API → POST → /login
- Register API → POST → /register
- Jobs API → GET → /jobs
- Apply Job API → POST → /apply
- Interview API → POST → /schedule-interview

---

# API Test Scenarios

## Login API
- Verify login with valid credentials
- Verify login with invalid password
- Verify response status code
- Verify token generation

## Register API
- Verify registration with valid details
- Verify duplicate email restriction
- Verify mandatory field validation

## Job List API
- Verify jobs list retrieval
- Verify response data structure
- Verify status code 200

## Apply Job API
- Verify successful job application
- Verify duplicate application restriction

## Schedule Interview API
- Verify successful interview scheduling
- Verify validation for past dates