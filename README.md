# Flight-Search-App
MATLAB app that allows user to search for possibility of a certain flight

As a truly enthusiast of flying and air travel I created an app that lets users to search for possibility of a certain flight and outputs information about the flight, departure and arrival airports, airline and aircraft. The app requires the user to type in departure and arrival airport and has an option to select an airline – right now, only major US and European airlines are available for selection. Once the user types in the information, the following information is displayed:

Flight information:
• Airline
• Departure Airport
• Arrival Airport
• Codeshare (outputs ‘Y’ if such exists)

Departure and Arrival Airports:
• Name
• City
• Country
• IATA (International Air Transportation Association) code
• ICAO (International Civil Aviation Organization) code
• Latitude
• Longitude
• Altitude in feet
• Timezone (according to GMT)
• DST (Daylight Savings Time)
• Timezone (city and country)

Airline:
• Name
• Alias (commonly known as)
• IATA code
• ICAO code
• Callsign (used for pilot/tower communications)
• Country

Aircraft:
• Name
• IATA code
• ICAO code

Airport names must exactly match to the ones in database, so the user is encouraged to use ‘updated_airports.txt’ file to check the spelling. In the future versions, flight connection possibilities will be added. Enjoy using the following software!
