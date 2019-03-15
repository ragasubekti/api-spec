- [Products](#products)

### Products
**[GET] /products**
Query Params
```yaml
type: "BUY",
tag: "pulsa"
```


```json
{
    "error": false,
    "errorMessage": null,
    "data": [
        {
            "id": "",
            "name": "TELKOMSEL 5000",
            "description": "Pulsa Telkomsel",
            "prices": {
                "silver": 5200,
                "gold": 5150,
                "platinum": 5100,
            },
            "tag": [
                "pulsa", "telkomsel"
            ]
        }
    ],
    "pagination": {
        "total": 120,
        "count": 10,
        "currentPage": 1,
    }
}
```