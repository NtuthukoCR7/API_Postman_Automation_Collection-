Project background

This is an automation project that navigates to public API: https://reqres.in/ 

Functionality
Below are the calls perfomed by the API
- Perfoming an API request to produce a list of all users
- Perfoming an API request to return a single user
- Perfoming an API request to create a new user
- Perfoming an API request to update an existing user

Tests Perfomed using code
- Verifying that the status code is 200 for successful "GET" call
- Verifying that "Michael" is within the list
- Verifying Status code is 201 for successful "POST" call
- Verifying that the value of total_pages is 2
- Verifying Status code is 200 for successful "PATCH" call

How to run tests
- Launch Postman 
- Import the collection: Postman API Assesment.postman_collection
- Run the Collection
- Then wait until the tests finishes running the confirm they all passed
