# Cheatsheet

## Less


```less {filename}```




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




Other          ||
---------------|---------------------------------------------------------------------------
```F```        | simulate tail -f inside less pager
```m``` + ```a```| mark the current position with the letter ‘a’
```‘a```       | go to the marked position ‘a’
```&pattern``` | display only the matching lines, not all
```v```        | using the configured editor edit the current file
```CTRL+G```   | show the current file name along with line, byte and percentage statistics


Search  ||
--------|---------------------
```/``` | Search forward
```?``` | Search backward
```n``` | Go to next match
```N``` | Go to previous match
