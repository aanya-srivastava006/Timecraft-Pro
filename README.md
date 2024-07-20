# Timecraft-Pro

## Problem description

The problem discussed is an NP-hard problem of generating a valid and highly optimal timetable. By valid we mean that there are no conflicts in the timetable, i.e. no two classes are in the same classroom at the same time, nor can a professor hold two classes at the same time, etc. 
Next, we describe the specific timetable format we will be analyzing. Classes are defined in the following fashion:
- Subject that is being taught
- Type of class (lectures or practicals)
- The professor conducting the class
- All of the student groups listening to the class toghether at the same time
- Classroom type allowed (i.e. some classrooms require students to have access to computers, some do not)
- Length (1 to 4 hours)
We assume that all classrooms are of the same size and have the required capacity. Valid hours for holding classes are from 9am to 9pm. The task at hand is to assign a time and classroom for each of the classes given in the mentioned format.
