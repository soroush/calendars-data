# Calendar Arithmetic Data Repository
This repository contains valid conversion between various calendar
systems and the Gregorian calendar at known times. The conversions 
is based on actual historical data. This repository is intended to 

## Data Format
Current version of repository format is 0.1.0.
The data is provided in CSV format in 6 columns. End of line is Unix-style (`\n`).
In the upcoming versions, more details like Julian Day Number and leap year
status will be added.

```<gregorian_year>;<gregorian_month>;<gregorian_day>;<calendar_year>;<calendar_month>;<calendar_day>```

## Supported Calendars
Currently conversions between the Solar Hijri and the Gregorian 
calendar between 1799-03-21 and 2100-03-21 is supported. 