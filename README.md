# date2ids
## Introduction
This script converts a date to the Imperial Dating System used in the Warhammer 40k universe
## Usage
### Synopsis
```
date2ids [flags] [date]
```
### Description
This script displays the date in the Imperial Dating System (IDS) format. If run without any arguments, it returns today's date converted to IDS. You can also specify a date or use flags for customization.

- If you provide a specific date or use flags, the script will convert that date to IDS.
- If you don't provide all the date information, the script will assume missing components are 0.
- When both a date and flags are given, the script prioritizes the information passed through the flags.

### Passing arguments is currently not implemented
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
