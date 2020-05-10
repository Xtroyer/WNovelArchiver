# WNovelArchiver
A simple python script to easily download and keep up to date raw web-novels on syosetu and kakuyomu  
If you have another WN site (JP/CN/KR/...) which you would like to be usable, feel free to put an issue.  
If your connection isn't stable, the script may (will) crash while downloading.
### Features:
* batch download (1 to max) from the input.txt
* update chapters of all the novels in the /novel_list/ directory
* generate a status file recording for every novel the last chapter ddl-ed
* compressing each novel in a zip of its own (not accessible by commands atm)

### Sites featured:
* Syosetu ncode and novel18
* Kakuyomu


## Build
Clone or download the repo  <br>
<code>cd WNovelArchiver</code><br>
<code>python archive_updater.py</code><br>
You may use arguments (<b>u</b> / <b>d</b> / <b>s</b>)


## Instructions
The script can be launched by either arguments or inputs :
* <b>u</b> to update the current novels
* <b>d</b> to download all novels in the <i>input.txt</i>
* <b>s</b> to detect all novel folders in ./novel_list/ and generate a csv file listing code/last chapter/name

The input.txt file should be written in csv style (code;novelname):<br>
![r](https://image.prntscr.com/image/8AY0wQWOQfqTNRfqg9Lejg.png)<br>The novel name can be let empty, in this case the script will fetch the novel name from the site<br>    
**the novel18.syosetu code should be written as n18'code' (n18n5560ce)**
