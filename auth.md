# Auth

- [Auth](#auth)
  - [LOGIN](#login)
    - [Login](#login)
      - [[POST] /login](#post-login)
    - [Login Verification (OTP)](#login-verification-otp)
      - [[POST] /login/verify](#post-loginverify)
    - [Login OTP Resend](#login-otp-resend)
      - [[POST] /login/verify/resend](#post-loginverifyresend)
  - [SIGNUP](#signup)
    - [Signup](#signup)
      - [[POST] /signup](#post-signup)
    - [Signup Verification (OTP)](#signup-verification-otp)
      - [[POST] /signup/verify](#post-signupverify)
    - [Signup OTP Resend](#signup-otp-resend)
      - [[POST] /signup/verify/resend](#post-signupverifyresend)
    - [Signup Profile Setup](#signup-profile-setup)
      - [[POST] /signup/profile](#post-signupprofile)

## LOGIN

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

### Login OTP Resend
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


## SIGNUP

### Signup
#### [POST] /signup

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
#### [POST] /signup/verify

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
#### [POST] /signup/verify/resend
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
#### [POST] /signup/profile

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