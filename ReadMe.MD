ANALOG CLOCK using JS, CSS and HTML

A more advanced version of the simple clock this time instead of just using css I have also used CSS and Javascript

HTML NOTES

Line 16
 div.number.number$*12{$} = emmet abbrevaition to generate 12 instead of indvidually typing 


CSS NOTES

Line 2
The box-sizing property allows us to include the padding and border in an element's total width and height.

Line 7 
adding some colour effect rather than monotone

Line 18
rgba so that it is transparent

Line 19
from square to circle

Line 24
position the numbers around the clock

Line 26
made line 21 .clock class position to relative in order to fix numbers around the clock

Line 57
transform: translateX(-50%) moves the clock hand to the left to make it center with the 12

line 60
add a psudeo element to the dom adding the circle in the middle


JAVASCRIPT NOTES

Line 1
Every 1000th millisecond function will be called

Line 7
Set Function

Line 8
set the date i.e the current time it wil run on

Line 9
 const secondsRatio = currentDate.getSeconds() / 60
 get the seconds from current date and divde by no of seconds

Line 10
const minutesRatio = (secondsRatio + currentDate.getMinutes()) / 60
percentage of a minute .05 = 30secs

Line 11
 const hoursRatio = (minutesRatio + currentDate.getHours()) / 12
 12 hours not 60