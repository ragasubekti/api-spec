# Profile

- [Profile](#profile)
    - [User Profile](#user-profile)
      - [/user/profile](#userprofile)
    - [User Balance](#user-balance)
      - [/user/balance](#userbalance)

### User Profile
#### /user/profile

```json
{
    "error": false,
    "errorMessage": null,
    "data": {
        "name": "",
        "phoneNumber": "",
        "email": "",
        "address": {
            "home": "Jl...",
            "province": {
                "id": "",
                "name": "Jawa Timur"
            },
            "city": {
                "id": "",
                "name": "Malang"
            },
            "regency": {
                "id": "",
                "name": "Blimbing"
            }
        },
        "dob": "2019-03-15T07:05:24.482Z",
        "birthplace": {
            "provinceId": "",
            "cityId": "",
            "name": "Malang"
        },
        "avatar": "https://raga.wtf",
        "fullService": 0
    }
}
```

### User Balance
#### /user/balance


```json
{
    "error": false,
    "errorMessage": null,
    "data": {
        "name": "",
        "phoneNumber": "",
        "balance": 120000.0
    }
}
```