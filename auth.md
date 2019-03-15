### Login
#### [POST] /login

Parameter
```json
{
    "phoneNumber": "082143688959"
}
```
Response
```json
{
    "error": false,
    "errorMessage": null,
    "success": true,
}
```

### Login Verification (OTP)
#### [POST] /login/verify

Parameter
```json
{
    "phoneNumber": "082143688959",
    "otp": "123456"
}
```
Response
```json
{
    "error": false,
    "errorMessage": null,
    "success": true,
    "token": "asdjkasdjkasdjk"
}
```

### Login OTP Resent
#### [POST] /login/verify/resend
Parameter
```json
{
    "phoneNumber": "082143688959"
}
```
Response
```json
{
    "error": false,
    "errorMessage": null,
    "success": true
}
```