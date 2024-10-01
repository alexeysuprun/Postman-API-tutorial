Here is your test task:
1. API
    a. Write positive and negative test cases for the API endpoints:
        i. POST - endpoint, that creates a new and unique user in the database:
            1. URL: https://gorest.co.in/public-api/users
            2. Method: POST
            3. Headers:
                a. "Accept" = "application/json"
                b. “Content-Type” = "application/json"
            4. Body (example JSON):
 



            5. Endpoint requires Authentication, by Bearer Token (‘TEST_TOKEN’) that can be generated on https://gorest.co.in/access-token after а successful login to the site.




 
        ii. GET - endpoint, that returns the user by the id:
            1. URL: https://gorest.co.in/public-ap...{USER_ID}
            2. Method: GET
            3. In the URL the USER_ID must be sent after ...users/
 
