time-off-tracker

A prototype for requesting and approving vacation days in 2027. It is a single static page (index.html) with no build step.

Manager view: set each person's day allowance, set the daily limit (and raise it for a single day), approve or decline requests, and add employees with auto-generated access codes.
Employee view: enter your access code, then pick weekdays on the 2027 calendar up to your allowance. Weekends and BC stat holidays can't be selected.
A switch at the top of the page moves between the manager and employee views. It is a prototype setting, not part of the app.
Run it

Prototype limits
Data is saved in each visitor's browser (localStorage). A manager and an employee on different devices do not see the same requests.
Access codes are checked in the browser and are visible in the page source. They are not real security.
A real version needs a small backend (a database and sign-in) so everyone shares one set of data.
