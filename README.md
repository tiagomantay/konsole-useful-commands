# konsole-useful-commands
Konsole (terminal) useful commands 

## automatic select yes 
```$ yes | command```

## reading a log file in real time
```$ tail -f [LOG_FILE]```
```$ tail -f [LOG_FILE] | grep [word/text]  --> Only word/text matches! ```

## find folders
```$ find . -type | grep [DIR_NAME]```

## find if there are files containing a word/text
```$ grep -Pri [word/text] [DIR_NAME]```

## list all apt repositories
```$ grep ^ /etc/apt/sources.list /etc/apt/sources.list.d/*```

## run commands in sequence
```$ command_1; command_2; command_3```

```$ command_1 && command_2 (run 2 only if 1 was successful)```

## run commands in sequence
```$ tail -f path_to_log | grep search_term```

## reference the last item from the previous command:  !$
```$ cd home```
```$ ls !$    --> equals to: ls home```

## reference the last item from the previous command:  !!
```$ apt-get install xmms2```
```$ sudo !!    --> equals to: sudo apt-get install xmms2```

## create your alias
```$ alias ls=dir```
```$ dir    --> equals to: ls```
