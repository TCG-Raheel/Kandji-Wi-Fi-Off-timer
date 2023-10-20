# Kandji-Wi-Fi-Off-timer
Turns of wi-fi on devices after a certain time of day - for Kandji MDM managed devices 

Here's how to implement this script using Kandji:

Log in to your Kandji dashboard.
Create a new policy or edit an existing one, depending on your requirements.
In the policy settings, go to the "Scripts" section.
Click the "+ Add Script" button and name your script (e.g., "Turn off Wi-Fi").
Paste the script content into the script field.
Specify the execution schedule for the script. You can set it to run at the desired time of day.
Save the script and policy.
Assign the policy to the target MacBooks or device groups in your Kandji organization.
This script checks the current time and turns off Wi-Fi if it's equal to or later than the specified time (in this case, 20:00 or 8:00 PM). You can adjust the turn_off_time variable to your desired time.

Make sure to thoroughly test the script in your Kandji environment before deploying it to production devices, and ensure that you have the necessary permissions and authentication to manage Wi-Fi settings on the target MacBooks.
