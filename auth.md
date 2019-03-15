# Auth

- [Auth](#auth)
  - [LOGIN](#login)
    - [Login](#login)
    - [Login Verification (OTP)](#login-verification-otp)
    - [Login OTP Resend](#login-otp-resend)
  - [SIGNUP](#signup)
    - [Signup](#signup)
    - [Signup Verification (OTP)](#signup-verification-otp)
    - [Signup OTP Resend](#signup-otp-resend)
    - [Signup Profile Setup](#signup-profile-setup)

## LOGIN

### Login
**[POST] /login**

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
**[POST] /login/verify**

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

### Login OTP Resend
**[POST] /login/verify/resend**
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


## SIGNUP

### Signup
**[POST] /signup**

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

### Signup Verification (OTP)
**[POST] /signup/verify**

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

### Signup OTP Resend
**[POST] /signup/verify/resend**
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
### Signup Profile Setup
**[POST] /signup/profile**

Parameter
```json
{
    "name": "",
    "email": ""
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