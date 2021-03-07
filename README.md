Tasks for Week #1
==================
>[Click this to see the output of the commands](https://raw.githubusercontent.com/rohitjain25/task/main/OUTPUT.txt)\
>Once these tasks are completed, please create a git repo of your own (on github) and push the answers to the following questions to the repo in a README file and then share the repo link with me:

1.)Find the Processes running on a linux machine?
  >```rohit@server:~ps -aux```
  
2.Find the user currently logged in ?
  >```rohit@server:~ w```
  
3.)Find the uptime of the machine ?
  >```rohit@server:~uptime```
  
4.)Find the ram usage ?
  >```rohit@server:~free```
  
5.)Find the disk usage ?
  >```rohit@server:~du -sh```
  
6.)Find the inode usage?
  >```rohit@server:~df -i```
  
7.)Find the ulimit of a user?
  >```rohit@server:~ulimit -Ha```
  
8.)Find the ulimit of the process?
  >```rohit@server:~ulimit -n```
  
9.)Find the file descriptors used by a process?
  >```rohit@server:~lsof -a -p 823```
  
10.)Find the 5 processes by memory usage?
>```rohit@server:~top -b -o +%MEM | head -n 12```

11.)Find the top 5 processes by cpu usage?
>```rohit@server:~ ps -eo pid,ppid,cmd,%mem,%cpu --sort=-%mem | head -6```

12.)Find the top 5 processes by network usage?
>```rohit@server:~netstat | head -9```

14.)Find the network Traffic and bandwidth usage of the machine?
>```rohit@server:~iftop -p```

16.)List files opened by a process?
>```rohit@server:~ sudo lsof | head```

17.)List Processes listening on a specific port?
>```rohit@server:~netstat -ltnp | grep -w ':80'```

18.)Find the status of the service?
>```rohit@server:~service apache2 status```

19.)Find Zombie processes on a machine?
>```rohit@server:~ps aux | grep 'z'```

20.)Find the eniviornment variables set on machine?
>```rohit@server:~printenv```

21.)Display processes started by a user?
>```rohit@server:~htop -u rohit```

22.)kill a process
>```sudo kill -s 15 PID-HERE```

23.)List Open Port
>```rohit@server:~nmap 127.0.0.1```

24.)Find the permission set for a file
>```rohit@server:~ls -l task.txt```

25.)list all the directiories inside a directory
>```rohit@server:~tree```

26.)Display number of files in the directory?
>```rohit@server:~ ls -1 | wc -l```

27.)Display number of lines in a file?
>```rohit@server:~wc -l task.txt```

28.)List the oldest and newest file in a directory ?
>```rohit@server:~ls -lt | tail -1```
>```rohit@server:~ls -ltr | tail -1```

29.)Display the OS and kernel information ?
>```rohit@server:~hostnamectl```

30.)Display the sizing (cpu cores, memory, and disk) of the machine?
>```rohit@server:~lshw```
