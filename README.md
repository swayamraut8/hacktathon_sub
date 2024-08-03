
# SnapIt (A cashier-free transaction and checkout system)
The PayApp project is an innovative solution that integrates RFID technology, QR code scanning, and a comprehensive web application to streamline the process of product management, purchase, and theft prevention. This project was developed as part of a hackathon and leverages the power of the ESP32 microcontroller, MongoDB Atlas, and modern web technologies to deliver a seamless user experience.



## Features

- ESP32 Integration: Utilizes an RFID reader to identify products and prevent theft.
- QR Code Scanning: Allows users to scan products using QR codes for quick information retrieval.
- Web Application: User-friendly interface for scanning products, viewing product details, making purchases, returning products, and managing user balance.
- Backend Server: Manages API requests, processes transactions, and handles product data stored in MongoDB.
- Real-time Updates: Ensures that the product information and user balance are always up-to-date.

## Deployment
To use the app visit this url:
https://snap-it-n16t.onrender.com

Note: The app's backend is hosted on the free-tier offered by render. The app's functionality won't be usable instantly. It takes around a minute for the server hosting the API to fire up once the site is opened. After that, it should work smoothly.

![Alt text](https://assets.digitalocean.com/articles/alligator/boo.svg "a title")

## Tech Stack

**Client:** HTML, CSS,

**Server:** Node, Express, MongoDB Atlas

**Hardware:** ESP32, MFRC522 RFID Sensor

