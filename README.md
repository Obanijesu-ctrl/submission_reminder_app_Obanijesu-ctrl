# submission_reminder_app_Obanijesu-ctrl
# Submission Reminder App

## Overview
The **Submission Reminder App** helps track student assignment submissions and sends reminders for pending assignments. This project sets up the environment with the necessary directory structure and scripts.

The first four lines of the script require the user to input their name, followed by a greeting.

All the directories were created, and the necessary files were included in the directories using the "mkdir" command to create the directories and the "touch" command to include the files in the respective directories.

All of the files were then given executable permissions using the "chmod +x" command

The contents of the files were then put into their respective destinations, like the "reminder.sh" file into the "app" directory, using the "cat  <<  'EOF' > path/to/directory" command and EOF at the end of the line to indicate the close of the list.
'EOF' in single quotations was used to include all downloadable contents in the file and contain them there.

This was done for every other folder.

Then, to make the "reminder.sh" executable, "cat << 'EOF' > submission_reminder_$name/startup.sh" was used to input "source ./app/reminder.sh" as its content, followed by EOF.


How to run the application
The script "create_environment.sh" should be executed with the "./create_environment.sh" command.
You will be prompted to input your name, after which you should input your name. (...your personal info wouldn't be stolen or anything... :)

Automatically, a directory with your name in it will be created. Navigate to that directory by using the "cd" command. It should look like "submission_reminder_(Your name)"
Now, you'd execute the "startup.sh" script by running "./startup.sh"
Then, the necessary information will be displayed, and you will be able to see how many days are left to submit the assignment and the people who haven't submitted it.

The End.

