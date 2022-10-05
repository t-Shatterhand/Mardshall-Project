# Marshall-Project
MuleSoft Demo project 

This project was developed as the first Demo on a System Integration course. 

Functionality, briefly:

HTTP server -> Endpoints

localhost:8081/getHistory - Perform a currency exchange rate history by the start and end dates
localhost:8081/getDoubleConvert - Simple double conversion loss calculator

The base currency for both endpoints is UAH. 
Currencies at /getHistory are fixed, those are EUR, USD, RUB and JPY.
Currency at /getDoubleConvert can be chosen by query parameter currency=..., available ones: EUR, USD, RUB

Telegram Bot -> @MarshallProject_bot

Accepts both endpoints as the message commands. 
All query parameters should be appended to the command.
