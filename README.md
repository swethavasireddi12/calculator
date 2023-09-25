
# Flask Calculator
The container will expose port **5000**

**API**

POST - /add

POST - /subtract

POST- /multiply

POST- /division

send POST request to the endpoints with a JSON in the body

x is the first variable

y is the second variable

Sample JSON:
```JSON
{
    "x":193,
    "y":657
}
```
Sample Response:
```JSON
{
    "Message": -464,
    "Status Code": 200
}
```
