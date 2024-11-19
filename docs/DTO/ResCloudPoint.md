# ResCloudPoint

body

```go
{
	ErrCode: @ErrCode
  Res: {
		// len(Data) => @ResBasicConfig.OutputChannelData
	  Data: [
		  Channel: int
			// len(CoordData) => (HFov / HFovResol)
		  CoordData: [
			  {
				  X: float64
					Y: float64
					Z: float64
					Distance: float64
			  }
		  ]
	  ]
	}
}
	
/* sample
{
    "ErrCode": 0,
    "Res": {
        "Data": [
            {
                "Channel": 0,
                "CoordData": [
                    {
                        "X": 2.5487519375975345,
                        "Y": 2.157677785265696,
                        "Z": -0.06237095128131305,
                        "Distance": 3.34
                    },
                    {
                        "X": 0,
                        "Y": 0,
                        "Z": -0,
                        "Distance": 0
                    },
                    {
                        "X": 2.6585894276598285,
                        "Y": 2.290787209641496,
                        "Z": -0.06554552065790682,
                        "Distance": 3.51
                    },
                    {
                        "X": 2.6636602662857625,
                        "Y": 2.315484543530252,
                        "Z": -0.06591899940809433,
                        "Distance": 3.5300000000000002
                    },
                    ...
                ],
                "DetectionAreaSet": true,
                "DetectionOutputPin1": true,
                "DetectionOutputPin2": false,
                "DetectionAreaDetect1": true,
                "DetectionAreaDetect2": false,
                "DetectionAreaDetect3": false,
                "DetectionAreaDetect4": false,
                "DetectionAreaDetect5": false
            },
            {
                "Channel": 1,
                "CoordData": [
                    {
                        "X": 2.6255196960518994,
                        "Y": 2.222666489971796,
                        "Z": 0,
                        "Distance": 3.44
                    },
                    {
                        "X": 2.676628998912109,
                        "Y": 2.2860571301222463,
                        "Z": 0,
                        "Distance": 3.52
                    },
                    {
                        "X": 2.689355694563376,
                        "Y": 2.3172971212426643,
                        "Z": 0,
                        "Distance": 3.55
                    },
                    {
                        "X": 2.694313201395296,
                        "Y": 2.342130733496111,
                        "Z": 0,
                        "Distance": 3.5700000000000003
                    },
                    ...
                ],
                "DetectionAreaSet": true,
                "DetectionOutputPin1": true,
                "DetectionOutputPin2": false,
                "DetectionAreaDetect1": true,
                "DetectionAreaDetect2": false,
                "DetectionAreaDetect3": false,
                "DetectionAreaDetect4": false,
                "DetectionAreaDetect5": false
            },
            {
                "Channel": 2,
                "CoordData": [
                    {
                        "X": 2.5792759128981038,
                        "Y": 2.183518237783848,
                        "Z": 0.06311790878168805,
                        "Distance": 3.38
                    },
                    {
                        "X": 0,
                        "Y": 0,
                        "Z": 0,
                        "Distance": 0
                    },
                    {
                        "X": 2.7343327161971454,
                        "Y": 2.356051802508775,
                        "Z": 0.06741291440884434,
                        "Distance": 3.61
                    },
                    {
                        "X": 2.7240265046151846,
                        "Y": 2.367960113921872,
                        "Z": 0.06741291440884434,
                        "Distance": 3.61
                    },
                    ...
                ],
                "DetectionAreaSet": true,
                "DetectionOutputPin1": true,
                "DetectionOutputPin2": false,
                "DetectionAreaDetect1": true,
                "DetectionAreaDetect2": false,
                "DetectionAreaDetect3": false,
                "DetectionAreaDetect4": false,
                "DetectionAreaDetect5": false
            },
            {
                "Channel": 3,
                "CoordData": [
                    {
                        "X": 2.69995859161556,
                        "Y": 2.285683666711569,
                        "Z": 0.1321884234313865,
                        "Distance": 3.54
                    },
                    {
                        "X": 2.7127560142178058,
                        "Y": 2.3169125161182853,
                        "Z": 0.1333086643079237,
                        "Distance": 3.5700000000000003
                    },
                    {
                        "X": 2.7329022502185856,
                        "Y": 2.3548192341650434,
                        "Z": 0.13480231880997326,
                        "Distance": 3.61
                    },
                    {
                        "X": 2.722601430330528,
                        "Y": 2.366721315745817,
                        "Z": 0.13480231880997326,
                        "Distance": 3.61
                    },
                    ...
                ],
                "DetectionAreaSet": true,
                "DetectionOutputPin1": true,
                "DetectionOutputPin2": false,
                "DetectionAreaDetect1": true,
                "DetectionAreaDetect2": false,
                "DetectionAreaDetect3": false,
                "DetectionAreaDetect4": false,
                "DetectionAreaDetect5": false
            }
        ]
    }
}
*/
```