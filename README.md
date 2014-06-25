timesheet-to-toggl
==================

This is a quick way to export your [Timesheet](https://play.google.com/store/apps/details?id=com.rauscha.apps.timesheet)'s data to [Toggl](https://www.toggl.com/).
I had to write this, so I'd thought to share it and save your time :)

Usage
-----
- On your mobile device, export your Timesheet data as a CSV. The CSV data should look like the `example_csv_exported_from_timesheet.csv` file.

- Open the script file, and input your email and project info where appropriate (it's marked `ADD YOUR EMAIL HERE`, and so forth)

- Then, execute the `convert` script like so
```bash
./convert <INPUT.CSV> <OUTPUT.CSV>
```
which is, with the example data:
```bash
./convert example_csv_exported_from_timesheet.csv example_csv_ready_for_toggl.csv
```
- You are done: Toggl will happily ingest the `example_csv_ready_for_toggl.csv` 

