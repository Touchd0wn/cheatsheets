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

```SCP ```

&nbsp;

Other          ||
---------------|---------------------------------------------------------------------------
scp /path/to/file root@host:/path/to/destination/ | copy a file from this server to a remote server
scp root@host:/path/to/file /path/to/destination/ | copy a file from a remote server to this server
scp /path/to/file1 /path/to/file2 root@host:/path/to/destination/ | copy multiple files from this server to a remote server
scp root@host:/path/to/source/ /path/to/file1 /path/to/file2 | copy multiple files from a remote server to this server
scp /path/to/directory/\*.txt root@host:/path/to/destination/ | copy all files of type .txt from this server to a remote server
scp root@host:/path/to/source/\*.txt /path/to/destination/ | copy all files of type .txt from a remote server to this server
