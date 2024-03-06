to set up once a day Open Task Scheduler:

Press Win + R to open the Run dialog.
Type taskschd.msc and press Enter.
Create a New Task:

In the Actions pane on the right, click on "Create Basic Task".
Set Task Name and Description:

Set Trigger:

Choose "Daily".
Set the start time to 10:00 PM.
Choose whether to run the task every day or select specific days of the week. Click "Next".
Set Action:

Choose "Start a program".
Click "Browse" and select the executable file (.exe) of your Python script created with PyInstaller.
Click "Next".
Review:

Review your task settings and click "Finish" to create the task.
That's it! Your Python script will now run automatically every night at 10:00 PM according to the schedule you've set.
