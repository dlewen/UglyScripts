UglyScrips !
======================

This is a collection of ugly but perhaps usful scripts.

### lossping
A script executing ping, and only outputing when a packet is lost.

example:

```
$ ./lossping 8.8.8.8
PING 8.8.8.8, printing stats only on packet loss
1 packets dropped, 1 packets sent, pattern: FFFF, loss: 100%, old no data
2 packets dropped, 2 packets sent, pattern: AAAA, loss: 100%, old no data
3 packets dropped, 13 packets sent, pattern: C001, loss: 23%, old rtt min/avg/max/mdev = 176.359/176.359/176.359/0.000 ms
4 packets dropped, 26 packets sent, pattern: C0CA, loss: 15%, old rtt min/avg/max/mdev = 756.732/756.732/756.732/0.000 ms
5 packets dropped, 27 packets sent, pattern: C01A, loss: 18%, old rtt min/avg/max/mdev = 756.732/756.732/756.732/0.000 ms
^\Quit
Stats: 10 packets dropped, 75 packets sent, pattern: 0000, loss: 13%, old rtt min/avg/max/mdev = 287.725/287.725/287.725/0.000 ms
```

Press CTRL+\ for statistics
