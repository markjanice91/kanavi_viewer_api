# ReqNetworkInfo

param

```go
index: int

/* sample
http://127.0.0.1:18290/v1/lidar/network-info?index=0
*/
```

body

```go
{
	Ip: [4]int
	Mac: [6]int
	Subnet: [4]int
	Gateway: [4]int
	Port: int
	EthernetMode: @EthMode
	DstIp: [4]int
}
	
/* sample
{
    "Ip": [
        192,
        168,
        123,
        222
    ],
    "Mac": [
        0,
        8,
        220,
        171,
        205,
        239
    ],
    "Subnet": [
        255,
        255,
        255,
        0
    ],
    "Gateway": [
        192,
        168,
        123,
        1
    ],
    "Port": 5000,
    "EthernetMode": 0,
    "DstIp": [
        192,
        168,
        123,
        100
    ]
}
*/
```