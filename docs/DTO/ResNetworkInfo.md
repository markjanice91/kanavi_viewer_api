# ResNetworkInfo

body

```go
{
	ErrCode: @ErrCode
	Res: {
		Ip: [4]int
		Mac: [6]int
		Subnet: [4]int
		Gateway: [4]int
		Port: int
		EthernetMode: @EthMode
		DstIp: [4]int
	}
}

/* sample 1(support ehternet mode)
{
    "ErrCode": 0,
    "Res": {
        "Ip": [
            192,
            168,
            123,
            201
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
            105
        ]
    }
}
*/

/* sample 2(not support ehternet mode)
{
    "ErrCode": 0,
    "Res": {
        "Ip": [
            192,
            168,
            123,
            200
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
            0,
            0,
            0,
            0
        ]
    }
}
*/
```