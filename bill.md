# Bill (Tagihan)

### [POST] Check Bill

***Contoh Request TOKEN PLN***

Request:
```json
{
    "type": "TOKEN_PLN",
    "reff": "123456"
}
```

Response:
```json
{
    "error": false,
    "errorMessage": "",
    "data": {
        "id": 12343435,
        "name": "RAGA",
        "additionalInformation": {
            "tariff": "R1",
            "power": "900",
        }
    }
}
```

***Contoh Request Tagihan PLN***

Request:
```json
{
    "type": "TAGIHAN_PLN",
    "reff": "123456"
}
```

Response:
```json
{
    "error": false,
    "errorMessage": "",
    "data": {
        "id": 12343435,
        "name": "RAGA",
        "additionalInformation": {
            "tariff": "R1",
            "power": "900",
            "period": "1",
            "admin": 2000.0,
            "amount": 250000.0
        }
    }
}
```
