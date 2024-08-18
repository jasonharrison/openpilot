## Private Fork of SunnyPilot (OpenPilot) - Not for Public Use

This repository contains my personal and **private** fork of SunnyPilot (OpenPilot), an open-source advanced driver assistance system (ADAS).

🚨 **Warning:** This fork is private, intended solely for my personal use, and is not suitable for use by others. If you are interested in using SunnyPilot, please use the original, unmodified version available at [https://github.com/sunnypilot/sunnypilot](https://github.com/sunnypilot/sunnypilot).

## Important Safety Notice

This private fork has been modified to disable the driver monitoring system, which reduces the safety features provided by OpenPilot. This means that the system will no longer alert you or disengage if it detects potential driver distraction.

## Modifications

The following changes have been made to the original SunnyPilot code:

1. **Driver Monitoring System Disabled:** The driver monitoring code in `selfdrive/controls/lib/events.py` has been disabled. This was done because the system was incorrectly detecting me as distracted, which caused unnecessary alerts and disengagements.

2. **Audible alerts disabled:** Some audible alerts in `selfdrive/controls/lib/events.py` have been disabled.

## Additional Information

For the original, unmodified version of OpenPilot, please visit the [comma.ai OpenPilot GitHub repository](https://github.com/commaai/openpilot).
