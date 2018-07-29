# Cheatsheet

## Less


```less {filename}```

&nbsp;

Navigation    |                                 | Search | &nbsp;
--------------|---------------------------------|--------|----------------------
```G```       | Go to the end of file           |```/``` | Search forward
```g```       | Go to the start of file         |```?``` | Search backward
```SPACE```   | Forward one window              |```n``` | Go to next match
```b```       | backward one window             |```N``` | Go to previous match
```d```       | Backward half window            ||
```u```       | Backward half window            ||
```j```       | Forward by one line             ||
```k```       | Backward by one line            ||
```10j```     | 10 lines forward.               ||
```10k```     | 10 lines backward               ||
```q or ZZ``` | Exit the less pager             ||

&nbsp;
&nbsp;

Other          ||
---------------|---------------------------------------------------------------------------
```F```        | simulate tail -f inside less pager
```m``` + ```a```| mark the current position with the letter ‘a’
```‘a```       | go to the marked position ‘a’
```&pattern``` | display only the matching lines, not all
```v```        | using the configured editor edit the current file
```CTRL+G```   | show the current file name along with line, byte and percentage statistics

&nbsp;
&nbsp;

## SCP

&nbsp;

Command         ||
---------------|---------------------------------------------------------------------------------------------------------------
```scp /path/to/X root@host:/path/to/dst/``` | copy X from this server to a remote server
```scp root@host:/path/to/X /path/to/dst/``` | copy X from a remote server to this server
```scp /path/to/X /path/to/Y root@host:/path/to/dst/``` | copy X & Y from this server to a remote server
```scp /path/to/directory/\*.txt root@host:/path/to/dst/``` | copy all .txt from this server to a remote server
```scp root@host:/path/to/source/\*.txt /path/to/dst/``` | copy all .txt from a remote server to this server
```scp -r /path/to/directory root@host:/path/to/dst/``` | copy a directory from this server to a remote server
```scp -r root@host:/path/to/directory /path/to/dst/``` | copy a directory from a remote server to this server
