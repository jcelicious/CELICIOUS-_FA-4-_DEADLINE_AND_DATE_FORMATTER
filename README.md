# CELICIOUS-_FA-4-_DEADLINE_AND_DATE_FORMATTER

import datetime

#User's input's
event_title = input("Enter the event title: ")
year = int(input("Enter the year: "))
month = int(input("Enter the month: "))
day = int(input("Enter the day: "))

deadline = datetime.date(year,month,day)

formatted_title = event_title.upper()
month_name = deadline.strftime("%B")
weekday = deadline.strftime("%A")

#Output
print()
print("Formatted Output")
print(f"Event: {formatted_title}")
print(f"Date: {month_name} {day}, {year}")
print(f"Year: {year}")
print(f"Month: {month_name}")
print(f"Day: {day}")
print(f"Weekday: {weekday}")
