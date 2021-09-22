# Technical Requirements

### User Story <br><br>
- As a user when I click the submit button I should get a confirmation message

### Code Requirements <br><br>

#### Code:
- Github repo: github.com/tech-reqs

### Query Parameters <br><br>


### Route requirements 
- return 401 when the request has not been applied because it lacks valid authentication credentials for the target resource.
- return 400 when the server could not understand the request due to invalid syntax.


### Response Oblect

```
{ 
    "data": 
    [ {
        "firstName":"Nick",
        "lastName": "Thompson,
        "age": "34" 
        } 
    ] 
}


```

### Tests
- Location: **tests.js**
- Tests should cover the 401 Bad Request statuses listed above
- Tests should cover the format of the response object, not the data itself.