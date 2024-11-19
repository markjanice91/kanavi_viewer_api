# ResBasicConfig

body

```go
{
	ErrCode: @ErrCode
	Res: {
	  OutputChannelData: int
	  SelfCheckActiveState: int
	  PulseActiveState: int
	  PulseOutputMode: int
	  PulsePinMode: int
	  PulsePinChannel: int
	  StartAngle: int
	  FinishAngle: int
	  MinDistance: int
	  MaxDistance: int
	  ObjectSize: int
	  UsrAreaCnt: int
	  UsrArea: [
	    {
	      PointCnt: int
	      Point: [
	        {
	          X: float64
	          Y: float64
	        }
	      ]
	    }
	  ]
	}
}

/* sample OK
{
    "ErrCode": 0,
    "Res": {
        "OutputChannelData": 15,
        "SelfCheckActiveState": 0,
        "PulseActiveState": 0,
        "PulseOutputMode": 0,
        "PulsePinMode": 0,
        "PulsePinChannel": 15,
        "StartAngle": 0,
        "FinishAngle": 100,
        "MinDistance": 0,
        "MaxDistance": 100,
        "ObjectSize": 0,
        "UsrAreaCnt": 3,
        "UsrArea": [
            {
                "PointCnt": 4,
                "Point": [
                    {
                        "X": -1.3900000000000001,
                        "Y": 3.1
                    },
                    {
                        "X": -3.54,
                        "Y": 4.33
                    },
                    {
                        "X": -1.17,
                        "Y": 3.62
                    },
                    {
                        "X": 2.94,
                        "Y": 2.81
                    }
                ]
            },
            {
                "PointCnt": 3,
                "Point": [
                    {
                        "X": -0.35000000000000003,
                        "Y": 1.17
                    },
                    {
                        "X": -1.3,
                        "Y": 1.73
                    },
                    {
                        "X": 0.51,
                        "Y": 2.69
                    }
                ]
            },
            {
                "PointCnt": 6,
                "Point": [
                    {
                        "X": -0.44,
                        "Y": 4.51
                    },
                    {
                        "X": 0.13,
                        "Y": 5.52
                    },
                    {
                        "X": 1.3,
                        "Y": 5.52
                    },
                    {
                        "X": 1.8900000000000001,
                        "Y": 4.51
                    },
                    {
                        "X": 1.3,
                        "Y": 3.5
                    },
                    {
                        "X": 0.13,
                        "Y": 3.5
                    }
                ]
            }
        ]
    }
}
*/
```