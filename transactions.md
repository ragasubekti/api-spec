# Transactions

- [Transactions](#transactions)
    - [Transactions List](#transactions-list)
      - [[GET] /transactions](#get-transactions)
    - [Transaction Detail](#transaction-detail)
      - [[GET] /transaction/:id](#get-transactionid)

### Transactions List
#### [GET] /transactions

```json
{
    "error": false,
    "errorMessage": null,
    "data": [
        {
            "id": "",
            "type": "PAY",
            "title": "Pembayaran Something",
            "product": {
                "id": "",
                "type" : "PLN"
            },
            "status": "success",
            "total": 12000.0,
            "date": "2019-03-15T07:05:24.482Z"
        },
    ],
    "pagination": {
        "total": 120,
        "count": 10,
        "currentPage": 1,
    }
}
```

### Transaction Detail
#### [GET] /transaction/:id

Bill Example, Please note that additional data is dynamic, so it can contain different data as in example

```json
{
    "error": false,
    "errorMessage": null,
    "data": 
        {
            "id": "",
            "code": "PPLN-123649438743",
            "type": "PAY",
            "title": "Pembayaran Something",
            "product": {
                "id": "",
                "type" : "PLN"
            },
            "reff": "12837827318",
            "additionalData": {
                "id": "",
                "name": "",
                "period": "",
                "admin": 2500.0
            },
            "status": "success",
            "total": 12000.0,
            "discount": 0.0,
            "date": "2019-03-15T07:05:24.482Z"
        },
        
}
```

Purchase Example

```json
{
    "error": false,
    "errorMessage": null,
    "data": 
        {
            "id": "",
            "code": "BPTSEL-123649438743",
            "type": "BUY",
            "title": "Pulsa Telkomsel 5000",
            "product": {
                "id": "",
                "type" : "Pulsa"
            },
            "reff": "082143688959",
            "additionalData": {
            },
            "status": "failed",
            "total": 7000.0,
            "discount": 0.0,
            "date": "2019-03-15T07:05:24.482Z"
        },
}
```
