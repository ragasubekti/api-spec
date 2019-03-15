## Topup Bank
**[POST] /topup/bank**
Params
```json
{
    "bankId": 1,
    "amount": 50000.0
}
```
Response
```json
{
    "error": false,
    "errorMessage": null,
    "data": {
        "bank": {
            "id": "12",
            "name": "KEB HANA BANK"
        },
        "account": {
            "id": "232332",
            "name": "RAGA"
        },
        "amount": 50214.0,
        "expires": "2019-03-15T07:05:24.482Z",
        "status": 1
    }
}
```


[Example of Status](https://github.com/ragasubekti/api-spec/blob/master/transactions.md#example-of-status)