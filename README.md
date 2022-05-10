# PINSTA
#### Video Demo:  <[URL HERE](https://www.youtube.com/watch?v=3YAFGB_ALzs)>
#### important :
This should be run locally 
### Description:
Hello world, Welcome to Pinsta , Marouane BEN ABBOU CS50 final project.        
In quick terms Pinsta is a website that allows the user to send an Instagram message to anyone at a given time.  
Technical tool used :
* Python
* Flask
* HTML,CSS
* Javascript
* bootstrarp
* SQLite3
* Jinja 

Getting Pinsta to work wasn't an easy task to do I needed some kind of bot or extensions that help me access Intagram without manually doing it which got me to many false leads, but finally I found selenium a bot that is usually for testing websites.
I used selenium to make my own bot I called  it Pinsta too, It can access Instagram using an extention called chromedriver with all that I programmed my website inspired from last week's problem finance and adding some personal tweaks to it.


### How the webpage works:

The idea is simple. The user can register with his Instagram username, and any password that we'll use to login to Pinsta or just login if the user already created a Pinsta account.
Once inside you'll see a description of the only feature available right now, which is as you guessed sending scheduled messages
Once clicked, you will be prompted with these fields:
* Reciever : the Instagram username of the person you want to send your message to.
* Password: your instagram password that is crypted using werkzeug security so no worries.
* message : message you want to send
* Date : enter the day and hour and the exact minute when you want your message to be sent
	 
**Database:**

Database stores all users and their Pinsta passwords but does not store the user's instagram password for safety and privacy.


### How to Install and Run Pinsta:

1. You'll need the following libraries: 
	* selenium
	* time
	* pause
	* datetime
	* flask
	* datetime
	* cs50
	* werkzeug.security

2. Dowloand chromedriver from it's website or from my project folder.

3. Dowloand the project file and open it with your editor.

### How to use Pinsta:

Once you have installed all necessary libraries and chromedriver just enter to app.py and type 'flask run', click on the link that you will get and voila you ready to send scheduled messages.



### License
MIT License

Copyright (c) [2022] [Marouane BEN ABBOU]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

