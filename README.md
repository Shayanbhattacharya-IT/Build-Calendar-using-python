# Build-Calendar-using-python
Build Calendar using python

1. Create a Python file
Name it calendar.py (or any name you like, but avoid naming it exactly calendar.py because it will conflict with Python’s built‑in calendar module).

For example:
my_calendar.py

2. Write the code
# code    
from calendar import *

# Ask user for a year
year = int(input("Enter Year: "))

# Print the calendar for the whole year
print(calendar(year, 2, 1, 8, 3))

# Ask user for a year
year = int(input("Enter year: "))

3. Save the file
Save it as my_calendar.py.

4. Run the file in VS Code terminal
python my_calendar.py

If you named your file differently, replace my_calendar.py with your filename.

🖥️ Example Output
If you enter 2026, you’ll see a full calendar for the year 2026 printed in the terminal.

Note :- 
1 The values 2, 1, 8, 3 in the Python calendar.calendar() function call correspond to optional formatting parameters for the output. 
2 (width): The width of the date columns in characters (default is 2).
1 (lines per week): The number of lines used for each week (default is 1).
8 (column separation): The number of spaces between month columns (default is 6).
3 (months per row): The number of months to display per row in the year calendar layout (default is 3).

<img width="1919" height="1199" alt="Screenshot 2026-01-01 213704" src="https://github.com/user-attachments/assets/5e538ae9-f7e0-4415-be10-dc943550d188" />


https://github.com/user-attachments/assets/ceca8796-3ed7-4e79-b42d-4e749ba3dbdf

