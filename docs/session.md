# Session

### Request
```
GET [API_PATH]/data/session?location_id=1&cinema_id=28&film_id=838

location_id: 0
p_cinema_id: 0
cinema_id: 0
film_id: 0
start: yyyy-mm-dd
end: yyyy-mm-dd
```

### Response
```json
{
    "status": 1,
    "result": [{
        "session_id": 5073560,
        "film_id": 838,
        "p_cinema_id": 4,
        "cinema_id": 21,
        "room_id": 140,
        "version_id": 2,
        "session_time": "2016-06-08 08:35:00",
        "status_id": 1,
        "is_voice": false,
        "location_id": 1
    }, {
        "session_id": 5073721,
        "film_id": 1101,
        "p_cinema_id": 4,
        "cinema_id": 130,
        "room_id": 248,
        "version_id": 2,
        "session_time": "2016-06-08 08:40:00",
        "status_id": 1,
        "is_voice": false,
        "location_id": 1
    }, {
        "session_id": 5073554,
        "film_id": 1046,
        "p_cinema_id": 4,
        "cinema_id": 21,
        "room_id": 142,
        "version_id": 2,
        "session_time": "2016-06-08 08:40:00",
        "status_id": 1,
        "is_voice": false,
        "location_id": 1
    }, {
        "session_id": 5073859,
        "film_id": 1110,
        "p_cinema_id": 16,
        "cinema_id": 97,
        "room_id": 235,
        "version_id": 2,
        "session_time": "2016-06-08 08:45:00",
        "status_id": 1,
        "is_voice": true,
        "location_id": 0
    }]
}
```