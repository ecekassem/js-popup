# js-popup
A pure JavaScript function for making pop-ups with customization of sub-screen size/location, box size, styles and of course various contents. 
This function considers the whole window as the main screen, and it is left to the designer to cutomize the sub-screen that will hold the popup box.
The sub-screen concept was not generated to complicate the popup matter but rather for giving the facility to locate the popup box in anywhere within the window boundries (i.e. instead of being poped up only in the center of the screen!).
Above all else, js-popup supports right-to-left "rtl" languages.

<b>Created by: Engineer/Mohamed Ahmed Kassem El Sayed [2015]</b>
For further queries and support developer@wencoproman.net
Also, for direct connection call us over <b>+20100 477 86 20</b><br>
js-popup is a very light weight function for making a pure
JavaScript popups, with some customizations, including:<br>
dirc: stands for the popup direction that can be 'ltr' or 'rtl'<br>
wsub: stands for the sub-screen (width) with a range from 0 to 100<br>
hsub: stands for the sub-screen (height) with a range from 0 to 100<br>
tsub: stands for the sub-screen (top) with a range from 0 to 100<br>
xsub: stands for the sub-screen (left or right according to the dirc value ltr or rtl) with a range from 0 to 100<br>
wbox: stands for the box (width) with a range from 0 to 100 (must be less than wsub)<br>
hbox: stands for the box (height) with a range from 0 to 100 (must be less than hsub)<br>
ovrl: stands for the overlay choice with boolean true or false<br>
opct: stands for the overlay opacity with a range from 0 to 1<br>
htit: stands for the box title (height) with a range from 0 to 100 (100 means no message)<br>
tpad: stands for the box title padding that can take any positive value in pixels (ex.: '10px')<br>
tbco: stands for the box title background color (ex.: '#3399ff','yellow', etc.)<br>
tclr: stands for the box title foreground color (ex.: '#ffffff','black', etc.)<br>
mpad: stands for the box title padding that can take any positive value in pixels (ex.: '15px')<br>
mbco: stands for the box message background color (ex.: '#eeeeee','grey', etc.)<br>
mclr: stands for the box message foreground color (ex.: '#000000','blue', etc.)<br>
titl: stands for the box title contents that can be any valid string or even an html code (ex.: 'My title','<tag>My title</tag>', etc.)<br>
mesg: stands for the box message contents that can be any valid string or even an html code (ex.: 'My message','<tag>My message</tag>', etc.)<br>

