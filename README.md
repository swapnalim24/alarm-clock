# alarm-clock
This project involves creating a clock and alarm app using JavaScript. The code retrieves elements from an HTML file, such as the clock, the alarm hour, minute, second, and period input fields, the set alarm button, and the alarm list. The clock is updated every second using setInterval() method, which gets the current time and displays it in a 12-hour format with hours, minutes, seconds, and AM/PM.

The project stores the alarms in an array and allows users to set alarms by validating input values for hour, minute, and second. It creates a new Date object for the alarm time and adds it to the alarms array. The project also adds the alarm to the alarms list with a delete button. When the delete button is clicked, the alarm is removed from the alarms array and list.

The project checks for alarms every second using setInterval() method and compares the current time to the alarm time. If the current time matches an alarm time, an alert is displayed, and the alarm is removed from the alarms array and list. Overall, this project demonstrates how to create a clock and alarm app with JavaScript and manipulate the HTML DOM.
