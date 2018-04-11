### user
admin: admin@gmail.com
pswd: 12345678
```json
{
    "token": "JWT eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI1YWNlNjBmYmE5OGZkNjI1NGJjOGUwMzIiLCJlbWFpbCI6ImFkbWluQGdtYWlsLmNvbSIsImlzTWFpbiI6dHJ1ZSwiYWN0aXZlIjpmYWxzZSwicm9sZSI6IlNlbGxlciIsInByb2ZpbGUiOnsidW5pdCI6Im1ldHJpYyJ9LCJ1cGRhdGVkQXQiOiIyMDE4LTA0LTExVDE5OjI0OjQzLjY4N1oiLCJpYXQiOjE1MjM0NzQ2ODMsImV4cCI6MTUyNDA3OTQ4M30.UYQOMAyByPSU2osMG96T0C_peNkcxZGokG2eiM5I4PY",
    "user": {
        "_id": "5ace60fba98fd6254bc8e032",
        "email": "admin@gmail.com",
        "isMain": true,
        "active": true,
        "role": "Admin",
        "profile": {
            "unit": "metric"
        },
        "updatedAt": "2018-04-11T19:24:43.687Z"
    }
}
```

#### seller
```json
seller@gmail.com
12345678
{
    "token": "JWT eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI1YWNlNjYwOGE5OGZkNjI1NGJjOGUwNzQiLCJlbWFpbCI6InNlbGxlckBnbWFpbC5jb20iLCJpc01haW4iOnRydWUsImFjdGl2ZSI6ZmFsc2UsInJvbGUiOiJTZWxsZXIiLCJwcm9maWxlIjp7InVuaXQiOiJtZXRyaWMifSwidXBkYXRlZEF0IjoiMjAxOC0wNC0xMVQxOTo0NjoxNi45OTFaIiwiaWF0IjoxNTIzNDc1OTc3LCJleHAiOjE1MjQwODA3Nzd9.cDmO0vec8cCzT6WcLsA97tpNG7cSozMu8OeJPk6ohSk",
    "user": {
        "_id": "5ace6608a98fd6254bc8e074",
        "email": "seller@gmail.com",
        "isMain": true,
        "active": false,
        "role": "Seller",
        "profile": {
            "unit": "metric"
        },
        "updatedAt": "2018-04-11T19:46:16.991Z"
    }
}
```

#### buyer
```json
buyer@gmail.com
12345678
{
    "token": "JWT eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI1YWNlNjYyNGE5OGZkNjI1NGJjOGUwNzUiLCJlbWFpbCI6ImJ1eWVyQGdtYWlsLmNvbSIsImlzTWFpbiI6dHJ1ZSwiYWN0aXZlIjpmYWxzZSwicm9sZSI6IkJ1eWVyIiwicHJvZmlsZSI6eyJ1bml0IjoibWV0cmljIn0sInVwZGF0ZWRBdCI6IjIwMTgtMDQtMTFUMTk6NDY6NDQuODMwWiIsImlhdCI6MTUyMzQ3NjAwNCwiZXhwIjoxNTI0MDgwODA0fQ.Y_T8XxE9RA2eU2Ge20qbEucJkXfEC3sUoNSQoU8Nx6s",
    "user": {
        "_id": "5ace6624a98fd6254bc8e075",
        "email": "buyer@gmail.com",
        "isMain": true,
        "active": false,
        "role": "Buyer",
        "profile": {
            "unit": "metric"
        },
        "updatedAt": "2018-04-11T19:46:44.830Z"
    }
}
```
---

### area
```json
{
    "area": {
        "_id": "5ace631da98fd6254bc8e033",
        "name": "Los Angeles",
        "description": "Los Angeles"
    }
}
```

---

### category
```json
{
    "category": {
        "_id": "5ace6353a98fd6254bc8e034",
        "name": "Mi",
        "description": "Mi",
        "basicCommission": 0.05,
        "updatedAt": "2018-04-11T19:34:43.437Z"
    }
}

{
    "category": {
        "_id": "5ace6477a98fd6254bc8e036",
        "name": "Oz",
        "description": "Oz",
        "basicCommission": 0.05,
        "updatedAt": "2018-04-11T19:39:35.525Z"
    }
}

{
    "category": {
        "_id": "5ace6493a98fd6254bc8e037",
        "name": "Au",
        "description": "Au",
        "basicCommission": 0.15,
        "updatedAt": "2018-04-11T19:40:03.842Z"
    }
}
```

### delivery
```json
{
    "deliverer": {
        "_id": "5ace6375a98fd6254bc8e035",
        "name": "US UPS inland delivery",
        "source": "4px",
        "location": null,
        "warehouseCode": "USLA",
        "areaCode": "US",
        "carrierCode": "LAUPS",
        "productCode": "G9",
        "cargoType": "P",
        "updatedAt": "2018-04-11T19:35:17.374Z"
    }
}
```

---

### Warehouse
```json
{
    "warehouse": {
        "_id": "5ace6540a98fd6254bc8e038",
        "active": false,
        "code": "ASD123",
        "name": "4PX in Los Angeles",
        "description": "4PX in Los Angeles",
        "owner": {
            "_id": "5ace60fba98fd6254bc8e032",
            "email": "admin@gmail.com",
            "profile": {
                "unit": "metric"
            }
        },
        "storage": "5000*5000ft",
        "company": "4px",
        "area": {
            "_id": "5ace631da98fd6254bc8e033",
            "name": "Los Angeles"
        },
        "categories": [
            {
                "category": {
                    "_id": "5ace6353a98fd6254bc8e034",
                    "name": "Mi",
                    "description": "Mi"
                },
                "_id": "5ace6540a98fd6254bc8e073"
            },
            {
                "category": {
                    "_id": "5ace6477a98fd6254bc8e036",
                    "name": "Oz",
                    "description": "Oz"
                },
                "_id": "5ace6540a98fd6254bc8e072"
            },
            {
                "category": {
                    "_id": "5ace6493a98fd6254bc8e037",
                    "name": "Au",
                    "description": "Au"
                },
                "_id": "5ace6540a98fd6254bc8e071"
            }
        ],
        "deliverers": [
            {
                "deliverer": {
                    "_id": "5ace6375a98fd6254bc8e035",
                    "name": "US UPS inland delivery",
                    "source": "4px"
                },
                "_id": "5ace6540a98fd6254bc8e070",
                "default": false
            }
        ],
        "storage_charge": "3.0/RMB/CBM/",
        "sku_charge": [],
        "package_charge": [
            {
                "weight": 0.25,
                "fee": 0.6,
                "_id": "5ace6540a98fd6254bc8e06f"
            },
            {
                "weight": 0.5,
                "fee": 0.76,
                "_id": "5ace6540a98fd6254bc8e06e"
            },
            {
                "weight": 0.75,
                "fee": 0.91,
                "_id": "5ace6540a98fd6254bc8e06d"
            },
            {
                "weight": 1,
                "fee": 0.91,
                "_id": "5ace6540a98fd6254bc8e06c"
            },
            {
                "weight": 2,
                "fee": 1.21,
                "_id": "5ace6540a98fd6254bc8e06b"
            },
            {
                "weight": 3,
                "fee": 1.51,
                "_id": "5ace6540a98fd6254bc8e06a"
            },
            {
                "weight": 4,
                "fee": 1.82,
                "_id": "5ace6540a98fd6254bc8e069"
            },
            {
                "weight": 5,
                "fee": 2.12,
                "_id": "5ace6540a98fd6254bc8e068"
            },
            {
                "weight": 6,
                "fee": 2.42,
                "_id": "5ace6540a98fd6254bc8e067"
            },
            {
                "weight": 7,
                "fee": 2.73,
                "_id": "5ace6540a98fd6254bc8e066"
            },
            {
                "weight": 8,
                "fee": 3,
                "_id": "5ace6540a98fd6254bc8e065"
            },
            {
                "weight": 9,
                "fee": 3.33,
                "_id": "5ace6540a98fd6254bc8e064"
            },
            {
                "weight": 10,
                "fee": 3.64,
                "_id": "5ace6540a98fd6254bc8e063"
            },
            {
                "weight": 11,
                "fee": 3.94,
                "_id": "5ace6540a98fd6254bc8e062"
            },
            {
                "weight": 12,
                "fee": 4.24,
                "_id": "5ace6540a98fd6254bc8e061"
            },
            {
                "weight": 13,
                "fee": 4.55,
                "_id": "5ace6540a98fd6254bc8e060"
            },
            {
                "weight": 14,
                "fee": 4.85,
                "_id": "5ace6540a98fd6254bc8e05f"
            },
            {
                "weight": 15,
                "fee": 5.15,
                "_id": "5ace6540a98fd6254bc8e05e"
            },
            {
                "weight": 16,
                "fee": 5.45,
                "_id": "5ace6540a98fd6254bc8e05d"
            },
            {
                "weight": 17,
                "fee": 5.76,
                "_id": "5ace6540a98fd6254bc8e05c"
            },
            {
                "weight": 18,
                "fee": 6.06,
                "_id": "5ace6540a98fd6254bc8e05b"
            },
            {
                "weight": 19,
                "fee": 6.36,
                "_id": "5ace6540a98fd6254bc8e05a"
            },
            {
                "weight": 20,
                "fee": 6.66,
                "_id": "5ace6540a98fd6254bc8e059"
            },
            {
                "weight": 21,
                "fee": 6.96,
                "_id": "5ace6540a98fd6254bc8e058"
            },
            {
                "weight": 22,
                "fee": 7.27,
                "_id": "5ace6540a98fd6254bc8e057"
            },
            {
                "weight": 23,
                "fee": 7.57,
                "_id": "5ace6540a98fd6254bc8e056"
            },
            {
                "weight": 24,
                "fee": 7.87,
                "_id": "5ace6540a98fd6254bc8e055"
            },
            {
                "weight": 25,
                "fee": 8.18,
                "_id": "5ace6540a98fd6254bc8e054"
            },
            {
                "weight": 26,
                "fee": 8.48,
                "_id": "5ace6540a98fd6254bc8e053"
            },
            {
                "weight": 27,
                "fee": 8.79,
                "_id": "5ace6540a98fd6254bc8e052"
            },
            {
                "weight": 28,
                "fee": 9.09,
                "_id": "5ace6540a98fd6254bc8e051"
            },
            {
                "weight": 29,
                "fee": 9.39,
                "_id": "5ace6540a98fd6254bc8e050"
            },
            {
                "weight": 30,
                "fee": 9.69,
                "_id": "5ace6540a98fd6254bc8e04f"
            },
            {
                "weight": 31,
                "fee": 10,
                "_id": "5ace6540a98fd6254bc8e04e"
            },
            {
                "weight": 32,
                "fee": 10.3,
                "_id": "5ace6540a98fd6254bc8e04d"
            },
            {
                "weight": 33,
                "fee": 10.6,
                "_id": "5ace6540a98fd6254bc8e04c"
            },
            {
                "weight": 34,
                "fee": 10.9,
                "_id": "5ace6540a98fd6254bc8e04b"
            },
            {
                "weight": 35,
                "fee": 11.21,
                "_id": "5ace6540a98fd6254bc8e04a"
            },
            {
                "weight": 36,
                "fee": 11.51,
                "_id": "5ace6540a98fd6254bc8e049"
            },
            {
                "weight": 37,
                "fee": 11.81,
                "_id": "5ace6540a98fd6254bc8e048"
            },
            {
                "weight": 38,
                "fee": 12.12,
                "_id": "5ace6540a98fd6254bc8e047"
            },
            {
                "weight": 39,
                "fee": 12.42,
                "_id": "5ace6540a98fd6254bc8e046"
            },
            {
                "weight": 40,
                "fee": 12.72,
                "_id": "5ace6540a98fd6254bc8e045"
            },
            {
                "weight": 41,
                "fee": 13.03,
                "_id": "5ace6540a98fd6254bc8e044"
            },
            {
                "weight": 42,
                "fee": 13.33,
                "_id": "5ace6540a98fd6254bc8e043"
            },
            {
                "weight": 43,
                "fee": 13.64,
                "_id": "5ace6540a98fd6254bc8e042"
            },
            {
                "weight": 44,
                "fee": 13.94,
                "_id": "5ace6540a98fd6254bc8e041"
            },
            {
                "weight": 45,
                "fee": 14.24,
                "_id": "5ace6540a98fd6254bc8e040"
            },
            {
                "weight": 46,
                "fee": 14.54,
                "_id": "5ace6540a98fd6254bc8e03f"
            },
            {
                "weight": 47,
                "fee": 14.84,
                "_id": "5ace6540a98fd6254bc8e03e"
            },
            {
                "weight": 48,
                "fee": 15.15,
                "_id": "5ace6540a98fd6254bc8e03d"
            },
            {
                "weight": 49,
                "fee": 15.45,
                "_id": "5ace6540a98fd6254bc8e03c"
            },
            {
                "weight": 50,
                "fee": 15.76,
                "_id": "5ace6540a98fd6254bc8e03b"
            }
        ],
        "material_charge": [
            {
                "volume": 12.5,
                "fee": 1.2,
                "_id": "5ace6540a98fd6254bc8e03a"
            },
            {
                "volume": 66,
                "fee": 2.3,
                "_id": "5ace6540a98fd6254bc8e039"
            }
        ],
        "delivery_charge": "10/RMB/g",
        "phoneNumber": "2137061352",
        "address": {
            "country": "USA",
            "zip": "90007",
            "state": "CA",
            "city": "Los Angeles",
            "line2": "APT 4008",
            "line1": "325 W Adams Blvd"
        },
        "updatedAt": "2018-04-11T19:42:56.388Z"
    }
}

```
