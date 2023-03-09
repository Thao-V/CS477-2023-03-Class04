# CS477-2023-03-Class04
## Create a server using Express to satisfy the following conditions
1. The server listens on port 3000
2. If clients send a GET request 'http://localhost:3000/count?string='AbceDE', the server will reply with the number of the upper letters
3. If clients send a GET request 'http://localhost:3000/reverse/AbceDE, the server will recognize 'AbceDE' as the params 'string', it will reverse all letters of that string and return the result to clients
4. If clients send a POST request 'http://localhost:3000/upper with the body {"string": "abc"}, the server will convert the string to a capital string and return that to the client
5. Write a middleware to ensure all incoming requests only contain the string without numeric letters 
