# Order

## Get Order

### Request
```
GET [API_PATH]/booking/order?invoice_no=20160608174353126072
```

### Response
```
{
    "status": 1,
    "result": {
        "transaction_id": "843571",
        "p_cinema_id": "4",
        "cinema_id": "28",
        "date_add": "2016-06-08 17:43:53",
        "ticket_code": "WWHZ9F5",
        "price_after": "150000",
        "price_before": "150000",
        "voucher_code": "",
        "voucher_value": "0",
        "voucher_description": "",
        "coupon_code": "",
        "coupon_description": "",
        "vista_booking_id": "WWHZ9F5",
        "film_id": "1094",
        "film_name": "Trước Ngày Em Đến - Me Before You",
        "film_version": "2D/Digital",
        "film_duration": "110",
        "film_status": "2",
        "publish_date": "2016-06-03",
        "session_time": "2016-06-08 20:20:00",
        "customer_email": "hanhlinh0826@yahoo.com",
        "customer_phone": "0904926890",
        "room_code": "131",
        "room_name": "Phòng Chiếu 1",
        "room_title": "Phòng Chiếu 1",
        "cinema_name": "BHD Star Bitexco",
        "cinema_address": "Lầu 3&4, Bitexco Icon 68, 2 Hải Triều, Q.1, Tp.HCM",
        "cinema_logo": "http://s3.img.edn.vn/123phim/2015/02/07d1779f6271267e107d03119dc6f487.png",
        "cinema_latitude": "10.77164",
        "cinema_longitude": "106.704387",
        "booking_service": "2",
        "poster_url": "http://s3.img.edn.vn/123phim/2016/04/truoc-ngay-em-den-me-before-you-14615742547420.jpg",
        "list_seat": [{
            "seat_code": "B6",
            "seat_price": "75000"
        }, {
            "seat_code": "B7",
            "seat_price": "75000"
        }],
        "list_combo": {},
        "list_ticket": [{
            "SeatData": "B6",
            "Description": "Adult Standard 2D",
            "PriceCents": "75000"
        }, {
            "SeatData": "B7",
            "Description": "Adult Standard 2D",
            "PriceCents": "75000"
        }]
    }
}
```


---


## Create Order

### Request
```
POST [API_PATH]/booking/order

{
    "session_id": 5073560,
    "session_time": "2016-06-08 08:35:00",
    "cinema_id": 8,
    "cinema_name": "BHD 3/2",
    "film_id": 838,
    "film_name": "X-Men: Apocalypse",
    "room_id": "1",
    "room_name": "Phòng chiếu 1",
    "list_seat": ["A01", "A02"],
    "payment_type": "ATM",
    "bank_code": "123PCC",
    "booking_data": {
        "user_session_id": "457391c9c82bfdcbb4947278c0401e41",
        "seats": [{
            "seat_code": "A01",
            "area_id": 1,
            "area_index": 1,
            "row_index": 1,
            "col_index": 1
        }],
        "tickets": [],
        "concessions": []
    }
}
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


## Confirm Order

### Request
```
POST [API_PATH]/booking/order/confirm

{
    "invoice_no": "20160608174353126072"
}
```

### Response
```
{
    "status": 1,
    "result": true
}
```


---


## Cancel Order

### Request
```
POST [API_PATH]/booking/order/cancel

{
    "invoice_no": "20160608174353126072"
}
```

### Response
```
{
    "status": 1,
    "result": true
}
```
