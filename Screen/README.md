# Screen Notes
https://www.rackaid.com/blog/linux-screen-tutorial-and-how-to/

### Actions
To trigger screen action first type ctrl then "a" followed by the action
- Actions -  c = create, d = detatch, n = next window, p = previous window
- Example ctrl a c  = create a new screen


### List active screen sessions and thier state
```
screen -ls
```
### Create new Screen session
```
screen -S session name
```

### Kill screen session
```
screen -X -S <session id> quit
```

### Reconnect to a screen session
```
screen -r <sessionName>
```

### Kill Srcreen
```
exit
```



