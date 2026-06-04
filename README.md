# system-health-monitoring-tool
Python tool that monitors system metrics using psutil library. 

## What it monitors
It monitors CPU usage, virtual memory usage and disk usage.

## Logging
In the event that one of the above metrics passes a threshold, a log will be written to sys_monitor.log detailing the event
