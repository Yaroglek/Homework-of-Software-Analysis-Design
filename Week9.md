# 1.
![](image/9.1.png)

```
Hotel(hotelID/key, address)
RoomCatalog(catalogID/key, hotelID/Fkey)
RoomDescription(descriptionID/key, catalogID/Fkey, price, type, address)
Room(roomID/key, date, descriptionID/Fkey, availability)
ReservationLineItem(roomID/Fkey, reservationID/Fkey, adultCount, childCount)
Reservation(revervationID/key, customerID/Fkey)
Customer(name, customerID/key)
```

![](image/9.2.png)

```
Customer(name, customerID/key)
Card(cardID/key, customerID/Fkey, bank, number)
Payment(paymentID/key, customerID/Fkey, cardID/Fkey, totalCost)
Item(itemID/key, paymentID/Fkey, details)
```
# 2.
![](image/9.3.png)