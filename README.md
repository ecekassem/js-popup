# js-popup
A pure JavaScript function for making pop-ups with customization of sub-screen size/location, box size, styles and of course various contents. 
This function considers the whole window as the main screen, and it is left to the designer to cutomize the sub-screen that will hold the popup box.
The sub-screen concept was not generated to complicate the popup matter but rather for giving the facility to locate the popup box in anywhere within the window boundries (i.e. instead of being poped up only in the center of the screen!).
Above all else, js-popup supports right-to-left "rtl" languages.

<b>Created by: Engineer/Mohamed Ahmed Kassem El Sayed &#169;2015</b><br>
For further queries and support developer@wencoproman.net<br>
Also, for direct connection call us over <b>+20100 477 86 20</b><br>
js-popup is a very light weight function for making a pure
JavaScript popups, with some customizations, including:<br>
<b>dirc:</b> stands for the popup direction that can be 'ltr' or 'rtl'<br>
<b>wsub:</b> stands for the sub-screen (width) with a range from 0 to 100<br>
<b>hsub:</b> stands for the sub-screen (height) with a range from 0 to 100<br>
<b>tsub:</b> stands for the sub-screen (top) with a range from 0 to 100<br>
<b>xsub:</b> stands for the sub-screen (left or right according to the dirc value ltr or rtl) with a range from 0 to 100<br>
<b>wbox:</b> stands for the box (width) with a range from 0 to 100 (must be less than wsub)<br>
<b>hbox:</b> stands for the box (height) with a range from 0 to 100 (must be less than hsub)<br>
<b>ovrl:</b> stands for the overlay choice with boolean true or false<br>
<b>opct:</b> stands for the overlay opacity with a range from 0 to 1<br>
<b>htit:</b> stands for the box title (height) with a range from 0 to 100 (100 means no message)<br>
<b>tpad:</b> stands for the box title padding that can take any positive value in pixels (ex.: '10px')<br>
<b>tbco:</b> stands for the box title background color (ex.: '#3399ff','yellow', etc.)<br>
<b>tclr:</b> stands for the box title foreground color (ex.: '#ffffff','black', etc.)<br>
<b>mpad:</b> stands for the box title padding that can take any positive value in pixels (ex.: '15px')<br>
<b>mbco:</b> stands for the box message background color (ex.: '#eeeeee','grey', etc.)<br>
<b>mclr:</b> stands for the box message foreground color (ex.: '#000000','blue', etc.)<br>
<b>titl:</b> stands for the box title contents that can be any valid string or even an html code (ex.: 'My title','&#60;h1&#62;My title&#60;/h1&#62;', etc.)<br>
<b>mesg:</b> stands for the box message contents that can be any valid string or even an html code (ex.: 'My message','&#60;p&#62;My message&#60;/p&#62;', etc.)<br>
<b>time:</b> stands for the time of animation in milli-seconds 0 means no animation<br>
<b>anim:</b> stands for animation with restricted values like 'tl' which means TOP-LEFT i.e. start animating from the top-left corner
<b>refr:</b> stands for refresh if true the parent window will be refreshed after closing the popup box
