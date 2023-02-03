# Timesheet exercise


#### N.B. The timesheet data is located in solution/timesheet.csv

Staff in the Programming Solutions Ltd office typically work a 40 hour week of five eight-hour shifts.
Usual hours are 9am to 6pm. All shifts include an hour for lunch which is not paid.
The file timesheet.csv contains a list of employees and their start and end times for a given
week. If an entry is blank, then they did not work that day.
Use the data in the file to write functions that can display the following information. Please
sort all lists by employee last name then first name.


1. A list of all employees and the total paid hours they worked for the week.
2. A list of all the employees that did not work 40 hours in the week and how many
they worked.
3. A list of all the employees that worked at the weekend and how many paid weekend
hours they worked.
4. (stretch goal) A list of all employees that have earned overtime in the week and how much regular
time, overtime and double time they should be paid.


Overtime is calculated as follows:
• The first 8 working hours of the day are regular time.
• Work over 8 hours but up to 12 hours is considered overtime
• Work over 12 hours in a single day is considered double time.
If someone works for 7 consecutive days the rules on the 7th day change as follows:
• The first 8 hours of work are always considered overtime.
• The hours after the first 8 are considered double time.


Finally, for the week as a whole, any hours worked over 40 that are not already
overtime/double time should be considered overtime.


### Prerequisites

- python 3

### Getting started

The project has one file `main.py` which calls the `main` function when the file is run. To check you're all set up properly, `cd` into the `solution` directory (instructions [here](https://phoenixnap.com/kb/linux-cd-command#:~:text=The%20Linux%20cd%20command%20offers,a%20built%2Din%20shell%20command)) and run the following command in the terminal.

`python main.py` 


If it's working you should see "Hello Aire Logic" printed out to the terminal.

Feel free to add more files / directories as needed to keep your code well structured and organised