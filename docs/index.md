## Summary

Caduceus is meant to assist with accountability at the staff level in a hospital, as well as facilitate communication amongst staff.

## Intended users

* Nurses dealing with difficult or rushed doctors.

  > As a nurse, I find that communication is often lacking between nurses and doctors, so I need an app that lets me see exactly what the doctor requires for a given patient without having to track them down or decipher horrible handwriting on a patient's chart.

* Doctors who worry about their orders being missed or forgotten.

    > As a doctor, we sometimes deal with nurses who are exhausted and occasionally forget things.  I need an app that lets me set my treatments or checks with a schedule attached that lets me be certain they won't forget anything thanks to an alarm tagged to that task.

## Client component

TBD

### Functionality

Patients will be able to log in and see their records as well as any other information in their file the doctor flags as visible.

Nurses will have access to the records of patients assigned to them as well as append notes and use the application to keep track of routine and singular care checks/tasks/etc. required by the doctor.  Clocking in will be done via the application, and they will be able to check their work schedule and send messages to other staff.

Doctors will have access to all patient records and be able to edit them (versions prior to editing will be saved server side).  They will also be able to flag a patient so a warning banner pops up for high priority issues (allergies, etc.).  Doctors will also be able to set specific checks/tasks for nursing staff per patient.

Admin staff will have no access to patient records, but will be able to set work schedules, evaluations, training classes, other HR needs.

### Persistent data

Hours worked, logged on calendar. Messages sent to/from user.
    
### Device/external services

Application will require speakers, clock, calendar, wi-fi or internet, and whatever 2FA service is used.
    
## Server component

Search functions for patient records, work schedules.  Enforcement of task completion. Filtering for high priority flagging.  Time tracking for clocking in/out.

### Functionality

TBD

### Persistent data

Patient records, staff records, task templates, messages sent from one user to another.
    
### External services

TBD
    
## Stretch goals/possible enhancements 

Possible QR code scanning capability for medical supply stocking purposes.
