# Concession Items

## Get Concession Items

### Request
```
GET [API_PATH]/booking/concession?cinema_id=8&session_id=5094639

cinema_id: required
session_id: required
```

### Response
```json
{
    "status": 1,
    "result": [{
        "group_code": "1001-3",
        "group_name": "DRINKS",
        "items": [{
            "item_id": "67",
            "item_code": "906",
            "item_name": "iAquafina",
            "item_desc": "1 CHAI NƯỚC TINH KHIẾT AQUAFINA",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/d4715b31afbacc5a88a668702f2beed7.jpg",
            "item_price": "20000"
        }, {
            "item_id": "9",
            "item_code": "615",
            "item_name": "iDrink",
            "item_desc": "1 LY PEPSI/7UP/MIRINDA CAM/MIRINDA SARSI",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/11e22440b6e609756391134fa07a15f2.jpg",
            "item_price": "25000"
        }]
    }, {
        "group_code": "1001-2",
        "group_name": "POPCORN",
        "items": [{
            "item_id": "8",
            "item_code": "618",
            "item_name": "iPopcorn",
            "item_desc": "1 BẮP (NGỌT/MẶN)",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/ed32144e1f5595135d79fa14f6ec9fa6.jpg",
            "item_price": "44000"
        }]
    }, {
        "group_code": "1001-4",
        "group_name": "HOT FOOD",
        "items": [{
            "item_id": "10",
            "item_code": "617",
            "item_name": "iHotDog",
            "item_desc": "1 HOT DOG",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/c65b1023ea9cf687e2b9fc4b33e092b4.jpg",
            "item_price": "44000"
        }]
    }, {
        "group_code": "1001-1",
        "group_name": "COMBO",
        "items": [{
            "item_id": "2",
            "item_code": "622",
            "item_name": "iCombo 1",
            "item_desc": "1 BẮP (NGỌT/MẶN) + 1 NƯỚC (PEPSI/7UP/MIRINDA CAM/MIRINDA SARSI))",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/7edb97951380b473a4e443c07f6a2674.jpg",
            "item_price": "59000"
        }, {
            "item_id": "6",
            "item_code": "614",
            "item_name": "iHotDog Combo",
            "item_desc": "1 HOT DOG + 1 NƯỚC (COCA/FANTA/SPRITE)",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/4f6a958f82bb43bd79a54a2afc4d7b23.jpg",
            "item_price": "59000"
        }, {
            "item_id": "3",
            "item_code": "619",
            "item_name": "iCombo 1 Extra",
            "item_desc": "1 BẮP (NGỌT/MẶN) + 1 NƯỚC (PEPSI/7UP/MIRINDA CAM/MIRINDA SARSI)) + 1 TRONG CÁC LOẠI BÁNH: TWISTER, KITKAT, COSY, POCKY, ĐẬU WASABI, SNACK POCA, SNACK OISHI",
            "item_img": "http://s3.img.edn.vn/123phim/2015/10/aa8a2d4c72fc33355189f43029f58861.jpg",
            "item_price": "74000"
        }]
    }]
}
```

---

## Add Concession Items
### Request
```
POST [API_PATH]/booking/concession

{
    "user_session_id": "457391c9c82bfdcbb4947278c0401e41",
    "session_id": 5094639,
    "items": [{
        "amount": 1,
        "item_id": 3,
        "item_code": "619",
        "item_name": "iCombo 1 Extra",
        "item_price": 74000
    }, {
        "amount": 1,
        "item_id": 67,
        "item_code": "906",
        "item_name": "iAquafina",
        "item_price": 20000
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