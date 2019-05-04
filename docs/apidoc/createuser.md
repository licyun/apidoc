### 创建新用户
#### Reuqest

- Method: **POST**
- URL: ```/v1.0/open/register```
- Headers： Content-Type:application/json
- Body:
```
{
    "phone" : "13511112222",
    "smsCode" : "730781",
    "email" : "crifan@webonn.com",
    "firstName" : "crifan",
    "lastName" : "Li",
    "password" : "654321",
    "facebookUserId" : "123907074803456"
}
```

#### Response
- Body
```
{
  "code": 200,
  "data": {
    "avatarUrl": "",
    "createdAt": "2016-10-24T20:39:46",
    "curRole": "IdleNoRole",
    "email": "crifan@webonn.com",
    "errandorRating": 0,
    "facebookUserId": "123907074803456",
    "firstName": "crifan",
    "id": "user-4d51faba-97ff-4adf-b256-40d7c9c68103",
    "isOnline": false,
    "lastName": "Li",
    "location": {
      "createdAt": null,
      "fullStr": null,
      "id": null,
      "latitude": null,
      "longitude": null,
      "shortStr": null,
      "updatedAt": null
    },
    "locationId": null,
    "password": "654321",
    "phone": "13511112222",
    "shareCodeCount": 0,
    "updatedAt": "2016-10-24T20:39:46"
  },
  "message": "new user has created"
}
```