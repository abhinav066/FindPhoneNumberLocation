﻿# FindPhoneNumberLocation

 # Phone Number Tracker

Phone Number Tracker is a tool that allows you to track the approximate location of a phone number. It uses the phonenumbers library to parse phone numbers and retrieve information such as the region and service provider.

## Installation


git clone https://github.com/your-username/phone-number-tracker.git

pip install phonenumbers folium colorama opencage

- Run the script:
python phone_tracker.py -p +1234567890


Replace `+1234567890` with the phone number you want to track.


About
The Phone Number Tracker tool is a Python script that allows users to track the approximate location of a phone number. It utilizes the phonenumbers library to parse phone numbers and retrieve information such as the region and service provider associated with the number. The tool also utilizes the OpenCageGeocode API to obtain the latitude and longitude coordinates corresponding to the location of the phone number.

Features
Phone Number Parsing: Parses phone numbers provided in various formats and extracts relevant information such as the country code, region, and service provider.

Location Tracking: Uses the OpenCageGeocode API to obtain the approximate latitude and longitude coordinates of the phone number's location.

Interactive Map Visualization: Generates an interactive map using the folium library, allowing users to visualize the location of the phone number on a map.

How It Works
The tool works by taking a phone number as input and processing it to extract relevant information using the phonenumbers library. It then makes a request to the OpenCageGeocode API to obtain the latitude and longitude coordinates corresponding to the location of the phone number. Finally, it generates an interactive map using the folium library, displaying the location of the phone number.


License
@abhinav066


 
