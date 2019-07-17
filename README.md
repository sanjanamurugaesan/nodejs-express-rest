# Node.js Express REST API

Once cloned the github, 
1. npm install
2. server is listening to 3002
3. Try in postman  http://localhost:3002/api/v1/parse
    Input  Request Body
    {
      data: “JOHN0000MICHAEL0009994567”
    }
4. output :
    {
    statusCode: 200,
    data:  {
        firstName: “JOHN0000”,
        lastName: “MICHAEL000”,
        clientId: “9994567”
    }
}

5. Try in postman  http://localhost:3002/api/v2/parse
6. {
    statusCode: 200,
    data:  {
        firstName: “JOHN”,
        lastName: “MICHAEL”,
        clientId: “999-4567”
    }
}


