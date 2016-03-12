# Homework-2---CS-407

Author: Nicholas H. Swanson

In this implementation of the Calendar, the event is stored in a TextEdit box and may be edited.  By default the box is set to the empty string, indicating no event is occuring on that day.  The delete button sets the TextEdit's text field back to the empty string.  Submit saves the TextEdit's current text and cancel exits the window without saving.

Data is saved through stored preferences.

Bugs:
-Editing an event for one day edits the events for all days.
