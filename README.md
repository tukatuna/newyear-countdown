In this code, we first set the desired timezone using date_default_timezone_set(). Replace 'Your_Timezone' with your preferred timezone, such as 'America/New_York' or 'Europe/London'.

Next, we calculate the time remaining until New Year's Eve using the strtotime() function to get the timestamp for December 31 of the current year at 23:59:59. We subtract the current timestamp using time() to determine the time difference.

Then, we convert the time remaining into days, hours, minutes, and seconds by dividing and using modulus calculations.

Finally, we format the countdown string using sprintf() to display the countdown in the format of "XX days XX hours XX minutes XX seconds". The countdown is then echoed to display on the webpage.

Please note that this code will display the countdown until the next New Year's Eve based on the current year and the selected timezone. You may need to adjust the code if you want to display the countdown for a specific future New Year's Eve date.

Remember to replace 'Your_Timezone' with your desired timezone for accurate countdown calculations.
