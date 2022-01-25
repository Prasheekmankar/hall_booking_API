1. /////////  To create room  ////////

http://localhost:3000/createRoom
method : POST
data =  
{
    "noSeats": 5,
    "amenities": ["TV", "Fridge", "microwave"],
    "price": 100
}

2.  ///////  To book a Room  ///////

http://localhost:3000/createBooking
method: POST
data = 
{
    "custName": "vrushabh",
    "date": "01/15/2020",
    "startTime": "11:00",
    "endTime": "15:00"
}

3. list all rooms with Booked data

http://localhost:3000/getBookedRooms
method: GET

4. list all customers with booked Data

http://localhost:3000/getCustomers
method: GET
