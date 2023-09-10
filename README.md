# Calander  https://tejaskarde21.github.io/Calander/weeklyTestCalender/index.html

Leap Year Check (isLeapYear function):

This function takes a year as input and returns true if it's a leap year and false otherwise.
It uses the standard logic for determining leap years: divisible by 4 but not divisible by 100 unless also divisible by 400.
Get February Days (getFebDays function):
This function takes a year as input and returns the number of days in February for that year. It uses the isLeapYear function to determine whether it's a leap year.
DOM Elements Selection:
The code selects various HTML elements using document.querySelector.
Month Picker Functionality:
When the element with the ID month-picker is clicked, it triggers a function that shows a list of months and hides some other elements.
Generate Calendar (generateCalendar function):
This function generates a calendar for a given month and year.
It first clears the content of the element with the class calendar-days.
It calculates the number of days in each month and determines the first day of the month.
It then creates HTML elements representing the days of the month and appends them to the calendar.
Month List Click Event:
For each month in month_names, it creates a clickable element and attaches an event listener. When clicked, it updates the displayed month and generates a new calendar.
Previous and Next Year Buttons:
These buttons allow the user to navigate to the previous or next year, updating the displayed calendar accordingly.
Current Date Display:

The current date is obtained and displayed in the calendar. The current date is highlighted.
Time Display:

The current time is obtained and displayed. It updates every second using setInterval.
Date Format Update:

The date and time formats are set using Intl.DateTimeFormat.
