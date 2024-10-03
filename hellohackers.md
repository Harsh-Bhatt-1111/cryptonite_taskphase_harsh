# Hello Hackers
Working on the first module.
## Intro to Commands
First, I started the challenge on pwn.college. Then, I connected my WSL using ```ssh -i key hacker@pwn.college```.<br/>
Then, ```whoami``` was used to get the current logged in user and finally the following chain of commands were used to get the flag.
```
hacker@hello~intro-to-commands:~$ whoami
hacker
hacker@hello~intro-to-commands:~$ hello
Success! Here is your flag:
pwn.college{kODP71gKi6uxQEGsvtHYFoJow7j.ddjNyUDL0cjN0czW}
```
## Intro  to Arguments
In this challenge, ```echo``` command was used which simply 'echoes' its arguments.
```
hacker@hello~intro-to-arguments:~$ echo Hello
Hello
hacker@hello~intro-to-arguments:~$ echo Hello Hackers!
Hello Hackers!
```
Here, the arbitrary ```hello``` command was used along with the argument ```hackers``` to get the flag.
```
hacker@hello~intro-to-arguments:~$ hello hackers
Success! Here is your flag:
pwn.college{UcuRSSLcay3y2phCzszts-B-0--.dhjNyUDL0cjN0czW}
```
