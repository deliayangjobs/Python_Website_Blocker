# Website_Blocker_Python
Block entertainment websites during working hours.

On Mac, to schedule this job, need to do: 
$sudo crontab -e
Add one line at the end of the table: 
@reboot python3 /path/website_blocker.py
