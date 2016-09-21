httpstat:

![image](https://github.com/gaojq/Dan-Dennis-Homework1/raw/master/hw1/READP.png)


Installation:

Download the script directly: https://github.com/djfinn14/Dan-Dennis-Homework1


Usage:

Just pass a url with it:
python httpstat.py httpbin.org/get

By default it will write response body in a tempfile, but you can let it print out by setting HTTPSTAT_SHOW_BODY=true:
HTTPSTAT_SHOW_BODY=true python httpstat.py httpbin.org/get

   You can pass any curl supported arguments after the url (except for -w, -D, -o, -s, -S which are already used by httpstat):
HTTPSTAT_SHOW_BODY=true python httpstat.py httpbin.org/post -X POST --data-urlencode "a=中文" -v



Description:

   We have changed some part of the code in this program.

   First is about the data's color. As we can see in the beginning, the number that showed in the form that present by the program showed no color at all, so it doesn’t look that good, so we changed a little bit about the color.

   Secondly, the form which showed in this program is patternless so we adjust the form a little bit.

   Thirdly, it is a really fabulous work form Danial, he learnt how to use the graphic presentation, and added a cool form which can directly show the time different when
   the program access a http address.


Website test:
   This is a list of website:
       espn.com
       www.sina.com
       www.gentlemonster.com
    
