#How to restore your cntrl + prntscreen in gnome 42

trick 
first type sudo apt install gnome-screenshot
then 
<img src ="./Screenshot from 2022-05-02 00-42-49.png">

click into the shortcut 
<img src ="./Screenshot from 2022-05-02 00-44-50.png">
then click custom shortcut 
give this a name 
like this one 

<img src ="./Screenshot from 2022-05-02 00-49-16.png">

full cmd is here 
sh -c "gnome-screenshot -cf /tmp/test/ && cat /tmp/test | xclip -i -selection clipboard -target image/png"

now do this and tada it works.....
