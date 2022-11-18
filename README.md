# Troubleshooting tools

troubleshooting tools for Unix-like systems mainly written in shell

## `rotated_logs_save`

Automatically saves a log file after it was closed and rotated. This is useful
when it is not possible to configure log rotation to keep sufficient number
of files.

## `timestamp_logfile`

Reads newly created lines in a log file and prepends them with a timestamp.

## `tmpdir_sizes`

Counts number of files in selected directories. Can be scheduled
to run periodically. This utility is useful to observe situations in which
large number of files can cause software failures.

## `http_monitor`

Continuously probe given address:port destinations using given HTTP request.
Checks the response using a given regex like in F5 LTM HTTP monitor.
