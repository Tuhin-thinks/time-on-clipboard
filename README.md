# time-on-clipboard

## Description:

Scrap date and time from <a href="https://www.timeanddate.com/">https://www.timeanddate.com/</a>

use <em>BeautifulSoup</em> to extract the time and date portion from the page's HTML content.

Nect, using <em>pyperclip</em> to copy the content to your clip board.


## Purpose:

1. I was facing a problem, that, my Desktop's time was getting changed after I turn-off and reopen the Desktop.
  So, this is just form of an utility to copy the time to my clipboard, so I can directly paste the content to
   the <em>cmd</em>(administrator) and change the time.
2. I tried using pyautogui and win32api (separately) to resolve the isse, (to change the time), but it can't be fixed
  like that. But now my code works just fine.
  Whenever, I feel like, then, I run the program and open cmd as administrator(type, 'time') and paste the content and hit enter,
  to literally change the time.

## Requirements:
The <a href="https://github.com/Tuhin-thinks/time-on-clipboard/blob/master/requirements.txt">requirements.txt</a> file is been provided. you can open your cmd or terminal, and type, <strong>pip3 install -r requirements.txt</strong>
to install the requirements.
