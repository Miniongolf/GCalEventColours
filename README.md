# GCalEventColours
Automatically colour codes Google Calendar events based on title triggers.

# How to modify
To modify the triggers and colours, edit the values in `mapList`, where `mapList[k][0]` is the trigger in the title (make sure this is lower case) and `mapList[k][1]` is the target colour. 

Colours can be found here:
https://developers.google.com/apps-script/reference/calendar/event-color

Credits to Marguerite Thibodeaux for the base program
https://www.linkedin.com/pulse/automate-color-coding-your-google-calendar-marguerite-thibodeaux-acc/
