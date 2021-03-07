Tasks for Week #1
=================
1.)Find the Processes running on a linux machine?\
  ```rohit@server:~ps -aux```\
2.Find the user currently logged in ?\
  ```rohit@server:~ w```\
3.)Find the uptime of the machine ?\
  ```rohit@server:~uptime```\
4.)Find the ram usage ?\
  ```rohit@server:~free```\
5.)Find the disk usage ?\
  ```rohit@server:~du -sh```\
6.)Find the inode usage?\
  ```rohit@server:~df -i```\
7.)Find the ulimit of a user?\
  ```rohit@server:~ulimit -Ha```\
8.)Find the ulimit of the process?\
  ```rohit@server:~ulimit -n```\
9.)Find the file descriptors used by a process?\
  ```rohit@server:~lsof -a -p 823```\
10.)Find the 5 processes by memory usage?\
```rohit@server:~top -b -o +%MEM | head -n 12```\
11.)Find the top 5 processes by cpu usage?\
```rohit@server:~ ps -eo pid,ppid,cmd,%mem,%cpu --sort=-%mem | head -6```\
12.)Find the top 5 processes by network usage?\
```rohit@server:~netstat | head -9```\
14.)Find the network Traffic and bandwidth usage of the machine?\
```rohit@server:~iftop -p```\
16.)List files opened by a process?\
```rohit@server:~ sudo lsof | head```\
17.)List Processes listening on a specific port?\
```rohit@server:~netstat -ltnp | grep -w ':80'```\
18.)Find the status of the service?\
```rohit@server:~service apache2 status```\


