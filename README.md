# git-merge-example

Miembr@ 1

$dev1 --> gco master

$master --> git merge dev1

$master --> git push origin master



..............

<-- ESPERAMOS AL PUSH -->

..............



$master --> git pull origin master

$master --> gco dev1

$dev1 --> git merge master

Miembr@ 2

$dev2 --> gco master

$master --> git merge dev2

$master --> git pull origin master

<--    CONFLICTOS ????  -->

$master --> git add / git commit -m'...'

$master --> git push origin master

$master --> gco dev2

$dev2 --> git merge master

