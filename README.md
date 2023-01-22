# ntpmon
This NTP server monitoring continously monitors reachability of the NTP server(s) in the background, and writes the result into log file(s).
The log files are nicely displayed on a terminal with standard coloumn number 132.
If the NTP server is part of the pool, its actual score is also displayed at the beginning of each line of the log file.   
You may use the `tail -f <logfile>` to keep watching the reachability status of an NTP server on the fly.
