# worker_allocation_challenge

Given a list of buildings and a list of employees, write a script that generates the schedule a work week by
implementing the method schedule(buildings, employees). Stipulations are below:
● The output schedule is for the next 5 days: assume Monday through Friday.
● All employees work full days, but can be unavailable on certain days (sick/vacation etc.)
● Assume buildings are given in the order of their importance -- no need for anything but a simple
in-order scheduling
● There are 3 types of employees:
○ Certified installers
○ Installers pending certification
○ Handypeople
● There are 3 types of buildings, each requiring a different set of employees. All installs are done in 1 day.
○ Single story homes require:
- 1 certified installer
○ Two story homes require:
- 1 certified installer AND
- 1 installer pending certification OR a handyperson
○ Commercial buildings require:
- 2 certified installer AND
- 2 installers pending certification AND
- 4 workers of any type (cert, pending or handypeople)
