# date2ids
## Introduction
This script converts a date to the Imperial Dating System used in the Warhammer 40k universe
## Usage
### Synopsis
```
date2ids [flags] [date]
```
### Description
Displays date in the Imperial Dating System format.
Returns todays date converted to IDS if ran without any arguments. If you specify a date or you use the flags it will convert that instead.
If you don't give it all the date information it will assume they are 0.
Given both date and flags it will always prioritise information passed through with the flags.

### Passing arguments is currently **not implemented**
### Date
    The date you want to pass needs to be formatted as: DD-MM-YY or DD/MM/YY
    If you pass the date it will assume the time of day is 00:00, unless you specify it with flags.
### Flags
    * `-h`, `--help`: Displays help.
    * `-y YEAR`, `--year YEAR`: Specify the year (e.g., 2023).
    * `-m MONTH`, `--month MONTH`: Specify the month (1-12).
    * `-d DAY`, `--day DAY`: Specify the day of month (1-7).
    * `-H HOUR`, `--hour HOUR`: Specify the hour of the day (0-23).
    * `-M MINUTE`, `--minute MINUTE`: Specify the miunte of the hour (0-59).
### Example usage
* Display todays date in IDS.
```
>date
Thu Jan  4 17:29:38 CET 2024
>date2ids
0.012.024.M3
```
<!-- TODO: Finish this once you finish the program>
