# Ticket Type

## Get Ticket Type List
### Request
```
GET [API_PATH]/booking/ticket?session_id=5073560

session_id: required
```

### Response
```json
{
    "status": 1,
    "result": [{
        "area_id": 2,
        "area_name": "thường",
        "type_description": "Người Lớn",
        "type_code": "0003",
        "type_price": 75000,
        "type_max": 10,
        "type_long_desc": "Vé Người Lớn"
    }, {
        "area_id": 4,
        "area_name": "COUPLE",
        "type_description": "Couple Adult Package",
        "type_code": "0341",
        "type_price": 160000,
        "type_max": 10,
        "type_long_desc": "Ve Ghe Couple (2 ve nguoi lon, vi tri ghe doi)"
    }]
}
```

---

## Add Ticket Type
### Request
```
POST [API_PATH]/booking/ticket

{
    "session_id": 5094639,
    "tickets": [{
        "amount": 2,
        "area_id": 2,
        "area_name": "thường",
        "type_code": "0003",
        "type_price": 75000
    }, {
        "amount": 1,
        "area_id": 4,
        "area_name": "COUPLE",
        "type_code": "0341",
        "type_price": 160000
    }]
}
```

### Response
```json
{
    "status": 1,
    "result": {
        "user_session_id": "457391c9c82bfdcbb4947278c0401e41"
    }
}
```