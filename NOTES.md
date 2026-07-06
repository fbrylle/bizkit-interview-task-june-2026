Notes:

1. The frontend price bug:
   Problem: Changing the end date didn't recalculate the total price because the "to" input was missing an event
   listener.
   Fix: Added an eventListener to the "to" input field to trigger the update on change.

2. Wrongly Allowed == from_date: 2026-01-08, to_date: 2026-01-18

3. I used AI tools as a development assistant to automate repetitive tasks and assist with reporting. To ensure quality, I
   never accept AI output blindly; everything it provided was thoroughly reviewed, manually tested, and validated before reaching production.