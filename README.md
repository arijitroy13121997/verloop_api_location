# Setup Application

To install dependencies : ```pip install -r requirements.txt```

Add key to helpers/config.py

To run : ```python app.py```

#### Sample

POST [/getAddressDetails](http://127.0.0.1:5000/getAddressDetails)

Request Body
```
{
    "address": "# 3582,13 G Main Road, 4th Cross Rd, Indiranagar, Bengaluru, Karnataka 560008",
    "output_format": "json"
}
```

Response Body
```
{
    "address": "3582, 13th G Main Rd, Channakesahava Nagar, HAL 2nd Stage, Doopanahalli, Indiranagar, Bengaluru, Karnataka 560008, India",
    "coordinates": {
        "lat": 12.9658286,
        "lng": 77.63948169999999
    }
}
```
