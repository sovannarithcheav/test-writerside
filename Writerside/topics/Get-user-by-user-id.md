# Find user by Id

<api-endpoint openapi-path="./../openapi.yaml" endpoint="/user/{id}" method="get">
    <response type="default">
        <sample>
            {
              "id": 11,
              "username": "theUser",
              "firstName": "John",
              "lastName": "Doe",
              "email": "john@email.com",
              "password": "12345",
              "phone": "12345",
              "userStatus": 13
            }
        </sample>
    </response>
</api-endpoint>
