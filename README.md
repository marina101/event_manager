# event_manager
Takes info on fundraiser attendees via CSV format, generates personlized thank you letter to each attendee with the name of their congresspeople (found using Sunlight API)

This program is inspired from the Jumpstart Labs tutorial. It takes a CSV file containing registration information of sample people who attended a non-profit fundraiser event. The program parses the names and zipcodes of the attendees. It then uses the API of the Sunlight Foundation to look up the names and websites of the congress people for each attendee using the attendees zipcodes. Finally, it creates a new directory of personalized thank you letters to each attendee in html format. 
