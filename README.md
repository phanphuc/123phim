# 123Phim

Header Request:
```
X-123F-Version: 3
X-123F-Token: {TOKEN_KEY} (please contact 123Phim to get your key)
Content-Type: application/json
```

Header Response:
```
Content-Type: application/json
```


Data Service:
* [Location](https://github.com/phanphuc/123phim/blob/master/docs/data/location.md)
* [Cinema](https://github.com/phanphuc/123phim/blob/master/docs/data/cinema.md)
* [Film](https://github.com/phanphuc/123phim/blob/master/docs/data/film.md)
* [Session](https://github.com/phanphuc/123phim/blob/master/docs/data/session.md)
* [Room](https://github.com/phanphuc/123phim/blob/master/docs/data/room.md)
* [News](https://github.com/phanphuc/123phim/blob/master/docs/data/news.md)


Booking Service:
* [Seat](https://github.com/phanphuc/123phim/blob/master/docs/booking/seat.md) (updating)
    * [Seat Status](https://github.com/phanphuc/123phim/blob/master/docs/booking/seat.md#get-seat-status)
    * [Seat Price](https://github.com/phanphuc/123phim/blob/master/docs/booking/seat.md#get-seat-price)

* [Ticket Type](https://github.com/phanphuc/123phim/blob/master/docs/booking/ticket.md)
    * [Get Ticket Type](https://github.com/phanphuc/123phim/blob/master/docs/booking/ticket.md#get-ticket-type-list)
    * [Add Ticket Type](https://github.com/phanphuc/123phim/blob/master/docs/booking/ticket.md#add-ticket-type)

* [Concession Items](https://github.com/phanphuc/123phim/blob/master/docs/data/concession.md)
    * [Get Concession Items](https://github.com/phanphuc/123phim/blob/master/docs/booking/concession.md#get-concession-items)
    * [Add Concession Items](https://github.com/phanphuc/123phim/blob/master/docs/booking/concession.md#add-concession-items)

* [Order](https://github.com/phanphuc/123phim/blob/master/docs/data/order.md)
    * [Get Order](https://github.com/phanphuc/123phim/blob/master/docs/booking/order.md#get-order)
    * [Create Order](https://github.com/phanphuc/123phim/blob/master/docs/booking/order.md#create-order)
    * [Confirm Order](https://github.com/phanphuc/123phim/blob/master/docs/booking/order.md#confirm-order)
    * [Cancel Order](https://github.com/phanphuc/123phim/blob/master/docs/booking/order.md#cancel-order)