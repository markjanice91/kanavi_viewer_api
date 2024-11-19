# ResDefaultInfo

body

```go
{
	ErrCode: @ErrCode
	Res: {
	  FWVersion: [3]int
	  HWVersion: [3]int
	  EndTarget: int
	}
}

/* sample OK
{
    "ErrCode": 0,
    "Res": {
        "FWVersion": [
            3,
            1,
            3
        ],
        "HWVersion": [
            2,
            0,
            0
        ],
        "EndTarget": 0
    }
}
*/
```