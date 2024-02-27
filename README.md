# Motel_Maids_Rooms
**Aim:** The project aims to create a script that runs automatically every day at 6:30 AM and creates maid rooms in Excel sheets based on the motel requirements.

**Motel Requirements:** Monday - 3 maids and both the daily and weekly rooms need to be cleaned
                    Tuesday - 2 maids and only daily rooms need to be cleaned
                    Wednesday - 2 maids and only daily rooms need to be cleaned
                    Thursday - 3 maids and both the daily and weekly rooms need to be cleaned
                    Friday - 2 maids and only daily rooms need to be cleaned
                    Saturday - 3 maids and only daily rooms are cleaned
                    Sunday - 3 maids and only daily rooms are cleaned

**Introduction:**

This is a Python script to automatically create and prepares a list of rooms that need to be cleaned depending on the day of the week.
Description:
Types of rooms: 1) Daily
                 2) Weekly 
                 3) jacuzzi 
                 4) double bed etc.
        
Daily rooms need to be cleaned every day and are present in the first 2 columns of the Excel sheet and then followed by the jacuzzi, and double bed, and in each room, there are smoking rooms and non-smoking rooms.

**The rooms that are marked with green or blue need to be cleaned the next day and the rooms that are in yellow need to be cleaned twice a week(Monday and Thursday).**

Tools and Technologies used: Bash, python, and Jupiter Notebook.

**Bash for scheduling the job to run the Python script at 6:30 am everyday**

                 
