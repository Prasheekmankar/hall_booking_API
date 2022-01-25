1. /////////  To get all available rooms ////////

https://hall-booking-apibyprasheek.herokuapp.com/getAllRooms

method : get

2. /////////  To create room  ////////

http://localhost:3000/createRoom
method : POST
data =  
{
    "noSeats": 5,
    "amenities": ["TV", "Fridge", "microwave"],
    "price": 100
}

3.  ///////  To book a Room  ///////

http://localhost:3000/createBooking
method: POST
data = 
{
    "custName": "vishal",
    "date": "01/15/2020",
    "startTime": "11:00",
    "endTime": "15:00"
}

4. list all rooms with Booked data

http://localhost:3000/getBookedRooms
method: GET

5. list all customers with booked Data

http://localhost:3000/getCustomers
method: GET
