# 🛍️ CDC Voucher System

This project is a simulation of Singapore's digital CDC voucher distribution and redemption platform.

The system handles the complete lifecycle of a voucher through four core APIs: Register Household, Register Merchant, Enquiry and Redemption. It relies on a centralized Python Flask backend to manage business logic and state, communicating with two distinct Flet desktop interfaces designed for households and merchants.

## How to Run the System ##
The system requires the backend server and frontend apps to run simultaneously. Both frontend apps will automatically connect to the backend via localhost:5000

1. Start the backend by running app.py in the backend folder.
2. Start the frontends by running household_frontend.py in and python merchant_frontend.py in the main project folder.

## Requirements ##
Before running the application, ensure you have Python 3.10+ installed. <br>
Flet 0.8.3 is required. Other versions may cause the UI to fail.
