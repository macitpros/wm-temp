# wm-temp
Watchman Monitoring plugin that uses SMCkit to monitor temperature sensors

Binary built from SMCkit: https://github.com/beltex/SMCKit

Custom plugin for Watchman Monitoring to alert when Mac is temperature is running above 100ºC (212ºF) or any fans have a minimum speed of 500 RPM. Over 100ºC indicates a physical inspection of the computer is necessary as it may be overheating. Fan speed of less then 500 RPM indicates a fan that may be failing (especially if it is at 0 RPM).
