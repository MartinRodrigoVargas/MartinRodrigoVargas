# Hello, I'm Martin Vargas 👋
#
## I'm a student of the **UNDEFINED ACADEMY** free Bootcamp to become a **Full-stack JavaScript Developer**.
#
### I share some Ubuntu terminal commands that I have learned:
|sudo| It is used before a command is executed as **root** or **administrator**.| Syntax [sudo apt-get update]|
|ls|Show the current directory.|Syntax [ls-ll]|
|mkdir|Create a directory.|Syntax [mkdir /dirname]|
|rm|Remove file.| Syntax [rm /dir/filename]|
|mv|Move file.| Syntax [mv /dir/filename /dir/filename]|
#
### Now I share some useful alias commands:
alias findd="ls ~/ | grep $1"; 
**We can use this alias to filter folders in our directory.**
#
alias updateos="sudo apt update && sudo apt dist-upgrade -y"
**Executing this command we can update the OS.**
#
alias mkdircd='function _mkdircd(){ mkdir -p "$1"; cd "$1"; };_mkdircd'	
**Create a directory and access it directly.**
#
alias tv="curl -s https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py | python3 -"
**Perform a speed test of the Internet connection.**
