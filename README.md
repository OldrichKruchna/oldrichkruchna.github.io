# Hacking Game

### This simple application was part of our one-time workshop for small kids (10 years old) to give them rough idea about what the password is, how to create it, how to create a strong password, what can happen if someone crack your password and so.The basic idea was to let them know, that to create your password from public accessible information is wrong and that password can be easily guess by anyone.

### To simulate this process we gave them roles of hackers and gave them printed facebook profiles of fake users to hack. These printed profiles contained public information like favorite hobby, date of birth, name of pet, favorite person and so.

### This application allows to create profiles in configuration file (config.js) with name, password and secret information. Then kids simply try different passwords from information they gather from printed profiles. The application provides text feedback based on inserted password, it simply counts similarity of real password and password which was inserted. the similarity is counted by Levenshtein Distance algorithm and the application provides a text advice based on this similarity.

### Feel free to use it, update it or improve it. Don't hesitate to ask me for anything kruchna.o@gmail.com

## License (haha)
----------------------------------------------------------------------------
"THE BEER-WARE LICENSE" (Revision 42):
<kruchna.o@gmail.com> wrote this application.  As long as you retain this notice you
can do whatever you want with this stuff. If we meet some day, and you think
this stuff is worth it, you can buy me a beer in return.   Poul-Henning Kamp