# ISS Overhead Notifier

This project is a Python script that notifies you via email when the International Space Station (ISS) is passing overhead during nighttime at your location.

---

## Features
- **Real-time ISS Location Check**:  
   Utilizes the [Open Notify API](http://api.open-notify.org/iss-now.json) to track the ISS's current location.  
- **Nighttime Detection**:  
   Uses the [Sunrise-Sunset API](https://sunrise-sunset.org/api) to determine if it is nighttime at your location.  
- **Email Notifications**:  
   Sends you an email alert if the ISS is visible overhead and it is dark outside.

---

## Requirements

1. **Python 3.x**  
2. Install the required libraries:
   ```bash
   pip install requests
