# A Blank PhoneGap App

## Usage

### PhoneGap CLI

    $ phonegap create my-app --template blank

### Desktop

In your browser, open the file:

    /www/index.html

	
IMPORTANT:
Only jquery dependencies are present, do not alter the css files in the css folder. 
Only one theme exists ("a" theme), if you need to add to it, contact me since I have the original color palette saved on my computer.
If you try to include another one it will override the old one and break it.
Cordova is not included, so you will have to include those files yourself.
There are examples of hidden menus in the "Entertainment section", I'm not sure if mullins wants them used or not, if
he wants them on separate pages just use the normal buttons.
I separated alot of stuff into small classes.

Class reference:
I've made a bunch of my own classes just to shorten the code a bit, you can find their definitions in the jquery 
initialization script above the css style sheet.

These classes cover transition animations and button style.

Animation classes:
	
	