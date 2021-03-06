---
title: 'Terminal (Linux/Unix)'
updatedAt: '2021-07-10 12:00:00'
published: true
---

# Terminal (Linux/Unix)

## Files and directories

```bash
pwd # present working directory

cd <path> # change directory
cd ~ # home directory
cd - # previous directory

ls -l # list files
ls -t # sort by modified date
ls -r # reverse

rm <path> # remove file
rm -rf # recursive forced remove
rmdir # remove directory

touch <path> # create empty file

which <program> # where is it running from
find # find files

grep <pattern> # find lines that match pattern
grep -n # get line number
grep -c # get count of matches

wc # word count
cat # concatenate files and print on the standard output
less # page through a file
tail/head # stream the last/first parts of a file
sort # sort lines of text files
uniq # report or omit repeated lines
cat <path> | sort | uniq # get unique values from a list
```

## Permissions

```bash
su # switch user
whoami # print current user

chmod <eg g+rw> <path> # change file permissions
chown <user> <path> # change file owner
```

## Processes

```bash
ps # report running processes
ps auxww # all processes with extra details

pidof <program> # find the process ID of a running program
kill <program> # kill program
kill -9 <program> # force kill

watch <program> # execute a program periodically, showing output fullscreen
watch -d # show only differences
```

## System

```bash
uptime # machine uptime

df -kh # get free disk space in human-readable format
du -s # disk usage of current directory

upower -i /org/freedesktop/UPower/devices/battery_BAT0 # check battery status (capacity, charging rate)

nmcli d wifi # show Wi-Fi networks (channel, rate, signal and more)
```
