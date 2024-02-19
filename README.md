# Garmin Forerunner 965 Configuration Guide

## Table of Contents

1. [Device Information](#device-information)
2. [Configuration Settings](#configuration-settings)
   - [Turn Prompts](#turn-prompts)
   - [Course Recalculation When Off Course](#course-recalculation-when-off-course)
   - [Off Course Alert](#off-course-alert)

## Device Information

- **Model**: Forerunner 965
- **Software Version**: 17.26

## Configuration Settings

### Turn Prompts

To avoid frequent and potentially distracting alerts during navigation, especially in areas with many bends or curves (e.g., forest trails), it is advisable to disable the Turn Prompts feature. This prevents the device from issuing sound alerts ahead of bends or curves.

Note: It's also possible to disable "Turn Notification" when importing a course (GPX-file). Instead of disabling the "Turn Prompts" globally, this allows you to disable turn prompts for a specific course only.

**App Configuration:**

```
Device -> Forerunner 965 -> Navigation -> Alerts -> Turn Prompts: Off
```

**Watch Configuration:**

```
Settings -> Navigation -> Alerts -> Turn Prompts: Off
```

**Reference:** [Garmin Support](https://www8.garmin.com/manuals/webhelp/GUID-0221611A-992D-495E-8DED-1DD448F7A066/EN-US/GUID-A302AFEE-C535-4C80-9DDD-95B717620C5B.html?scroll=GUID-D63C6C77-7AC0-4C5F-AA53-44A8C6B1EB9D)

### Course Recalculation When Off Course

For running activities, to ensure that the device closely adheres to the planned course without recalculating a new route to the final destination upon deviation, adjust the following setting.

**App Configuration:**

```
Device -> Forerunner 965 -> Activities & Apps -> Run -> Routing -> Courses: Follow Course
```

**Watch Configuration:**

```
Settings -> Activities & Apps -> Run -> Run Settings -> Routing -> Courses: Follow Course
```

**Reference:** [Garmin Support](https://www8.garmin.com/manuals/webhelp/GUID-0221611A-992D-495E-8DED-1DD448F7A066/EN-US/GUID-4D9C1A64-B6FE-466C-87D7-5A31C3CFDED5.html)

### Off Course Alert

The Off Course Alert is activated by default; however, it may not function as intended when the Course Recalculation setting is set to 'Use Map' (default). Rather than receiving an off-course notification, the device will reroute you to a new path. Therefore, it's essential to configure the Course Recalculation setting as previously outlined. With this adjustment, the Off Course Alert should operate more reliably, albeit with a slight delay. Typically, the alert is issued approximately 80-90 meters after deviating from the intended course.

**App Configuration:**

```
Device -> Forerunner 965 -> Navigation -> Alerts -> Off Course: On
```

**Watch Configuration:**

```
Settings -> Navigation -> Alerts -> Off Course: On
```

**Reference:** [Garmin Support](https://www8.garmin.com/manuals/webhelp/GUID-0221611A-992D-495E-8DED-1DD448F7A066/EN-US/GUID-A302AFEE-C535-4C80-9DDD-95B717620C5B.html?scroll=GUID-D63C6C77-7AC0-4C5F-AA53-44A8C6B1EB9D)


