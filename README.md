# load-balancer-exercise

```bash
loadtest -t 5 -c 100 --rps 100 http://localhost:80
```

```bash
[Sun Aug 12 2018 15:12:47 GMT-0600 (MDT)] INFO Requests: 0, requests per second: 0, mean latency: 0 ms
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Target URL:          http://localhost:80
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Max time (s):        5
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Concurrency level:   100
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Agent:               none
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Requests per second: 100
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Completed requests:  500
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Total errors:        0
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Total time:          5.003157674 s
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Requests per second: 100
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Mean latency:        10.1 ms
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO Percentage of the requests served within a certain time
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO   50%      8 ms
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO   90%      15 ms
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO   95%      19 ms
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO   99%      36 ms
[Sun Aug 12 2018 15:12:52 GMT-0600 (MDT)] INFO  100%      39 ms (longest request)
```