# Uwsgi performance

```
Server Software:
Server Hostname:        127.0.0.1
Server Port:            5000

Document Path:          /
Document Length:        40 bytes

Concurrency Level:      500
Time taken for tests:   11.581 seconds
Complete requests:      10000
Failed requests:        1084
   (Connect: 0, Receive: 541, Length: 543, Exceptions: 0)
Total transferred:      1125502 bytes
HTML transferred:       378320 bytes
Requests per second:    863.46 [#/sec] (mean)
Time per request:       579.064 [ms] (mean)
Time per request:       1.158 [ms] (mean, across all concurrent requests)
Transfer rate:          94.91 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0  229 887.6      0    4699
Processing:     0  183 910.6      9    6873
Waiting:        0   10   7.8      9      56
Total:          0  411 1704.1     10   10953

Percentage of the requests served within a certain time (ms)
  50%     10
  66%     11
  75%     12
  80%     13
  90%    112
  95%   3426
  98%   7880
  99%  10625
 100%  10953 (longest request)
```

# Nginx Unit performance

```

Server Software:        Unit/1.19.0
Server Hostname:        127.0.0.1
Server Port:            8080

Document Path:          /
Document Length:        29 bytes

Concurrency Level:      500
Time taken for tests:   5.590 seconds
Complete requests:      10000
Failed requests:        0
Total transferred:      1660000 bytes
HTML transferred:       290000 bytes
Requests per second:    1788.87 [#/sec] (mean)
Time per request:       279.506 [ms] (mean)
Time per request:       0.559 [ms] (mean, across all concurrent requests)
Transfer rate:          289.99 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   3.7      0      25
Processing:    12  274  60.9    269     461
Waiting:        3  273  61.0    268     460
Total:         28  275  59.5    269     461

Percentage of the requests served within a certain time (ms)
  50%    269
  66%    280
  75%    289
  80%    306
  90%    358
  95%    409
  98%    431
  99%    446
 100%    461 (longest request)



```
