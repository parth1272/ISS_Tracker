# ISS_Tracker


ISS Tracker and Notifier

This Python script utilizes external APIs to track the International Space Station (ISS) and notifies the user via email when the ISS is overhead during nighttime.

Prerequisites
Python 3.x
Requests library (pip install requests)
smtplib library (usually comes with Python, no need for additional installation)
Configuration
Replace MY_EMAIL and MY_PASSWORD with your Gmail credentials.
Set MY_LAT and MY_LONG to your latitude and longitude, respectively.
How It Works
The script periodically checks the ISS's current position using the Open Notify API.
It also checks if it is nighttime at your location using the Sunrise Sunset API.
If the ISS is overhead and it is nighttime, the script sends an email notification.
Usage
Run the script.

bash
Copy code
python iss_tracker.py
Keep the script running to receive notifications when the ISS is overhead during nighttime.

Note: For security reasons, it is recommended to use an "App Password" for Gmail authentication instead of your actual account password.

Disclaimer
This script is meant for educational purposes and might require additional adjustments based on your specific use case or location. Use it responsibly and ensure compliance with API terms of service.

Acknowledgments
Open Notify API
Sunrise Sunset API
Feel free to enhance or modify the script based on your preferences and needs. Contributions are welcome!
