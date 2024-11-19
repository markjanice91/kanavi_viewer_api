# ReqUserArea

param

```go
index: int

/* sample
http://127.0.0.1:18290/v1/lidar/user-area?index=0
*/
```

body

```go
[
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

/* sample
[
    {
        "PointCnt": 4,
        "Point": [
            {
                "X": -1.39,
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
    }
]
*/
```