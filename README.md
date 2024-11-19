# VL Series APIs

## Support Models

| Model | H/W Version | F/W Version |
| --- | --- | --- |
| VL-R2 | 2.0.0 or later | 3.2.0 or later |
| VL-R4 | 2.0.0 or later | 3.1.3 or later |
| VL-R270 | 1.0.0 or later | 1.1.1 or later |

## APIs

| Path | Method | Request | Response |
| --- | --- | --- | --- |
| /v1/lidar/lidar-infos | Get | [ReqLiDARList](docs/DTO/ReqLiDARList.md)  | [ResLiDARList](docs/DTO/ResLiDARList.md)  |
| /v1/lidar/basic-config | Get | [Request](docs/DTO/Request.md)  | [ResBasicConfig](docs/DTO/ResBasicConfig.md)  |
| /v1/lidar/default-info | Get | [Request](docs/DTO/Request.md)  | [ResDefaultInfo](docs/DTO/ResDefaultInfo.md)  |
| /v1/lidar/network-info | Get | [Request](docs/DTO/Request.md)  | [ResNetworkInfo](docs/DTO/ResNetworkInfo.md)  |
| /v1/lidar/teaching-area | Get | [Request](docs/DTO/Request.md)  | [ResTeachingArea](docs/DTO/ResTeachingArea.md)  |
| /v1/lidar/teaching-mode | Get | [Request](docs/DTO/Request.md)  | [ResTeachingMode](docs/DTO/ResTeachingMode.md)  |
| /v1/lidar/motor-speed | Get | [Request](docs/DTO/Request.md)  | [ResMotorSpeed](docs/DTO/ResMotorSpeed.md)  |
| /v1/lidar/warning-area | Get | [Request](docs/DTO/Request.md)  | [ResWarningArea](docs/DTO/ResWarningArea.md)  |
| /v1/lidar/fog-filter | Get | [Request](docs/DTO/Request.md)  | [ResFogFilter](docs/DTO/ResFogFilter.md)  |
| /v1/lidar/radius-filter | Get | [Request](docs/DTO/Request.md)  | [ResRadiusFilter](docs/DTO/ResRadiusFilter.md)  |
| /v1/lidar/contam-detection-mode | Get | [Request](docs/DTO/Request.md)  | [ResContamDetectionMode](docs/DTO/ResContamDetectionMode.md)  |
| /v1/lidar/cloud-point | Get | [Request](docs/DTO/Request.md)  | [ResCloudPoint](docs/DTO/ResCloudPoint.md)  |
| /v1/lidar/reset-config | Post | [Request](docs/DTO/Request.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/hfov | Post | [ReqHFov](docs/DTO/ReqHFov.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/output-channel | Post | [ReqOutputChannel](docs/DTO/ReqOutputChannel.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/user-area | Post | [ReqUserArea](docs/DTO/ReqUserArea.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/object-size | Post | [ReqObjectSize](docs/DTO/ReqObjectSize.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/pulse-output-time | Post | [ReqPulseOutputTime](docs/DTO/ReqPulseOutputTime.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/detection-distance | Post | [ReqDetectionDisatance](docs/DTO/ReqDetectionDisatance.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/pulse-active-state | Post | [ReqPulseActiveState](docs/DTO/ReqPulseActiveState.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/pulse-pin-output | Post | [ReqPulsePinOutput](docs/DTO/ReqPulsePinOutput.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/self-check-active-state | Post | [ReqSelfCheckActiveState](docs/DTO/ReqSelfCheckActiveState.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/guide-beam | Post | [ReqGuideBeam](docs/DTO/ReqGuideBeam.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/id | Post | [ReqID](docs/DTO/ReqID.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/network-info | Post | [ReqNetworkInfo](docs/DTO/ReqNetworkInfo.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/teaching-mode | Post | [ReqTeachingMode](docs/DTO/ReqTeachingMode.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/motor-speed | Post | [ReqMotorSpeed](docs/DTO/ReqMotorSpeed.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/warning-area | Post | [ReqWarningArea](docs/DTO/ReqWarningArea.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/fog-filter | Post | [ReqFogFilter](docs/DTO/ReqFogFilter.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/radius-filter | Post | [ReqRadiusFilter](docs/DTO/ReqRadiusFilter.md)  | [Response](docs/DTO/Response.md)  |
| /v1/lidar/contam-detection-mode | Post | [ReqContamDetectionMode](docs/DTO/ReqContamDetectionMode.md)  | [Response](docs/DTO/Response.md)  |

## Data Transfer Object

### Post

[Request](docs/DTO/Request.md)

[ReqLiDARList](docs/DTO/ReqLiDARList.md)

[ReqHFov](docs/DTO/ReqHFov.md)

[ReqOutputChannel](docs/DTO/ReqOutputChannel.md)

[ReqUserArea](docs/DTO/ReqUserArea.md)

[ReqObjectSize](docs/DTO/ReqObjectSize.md)

[ReqPulseOutputTime](docs/DTO/ReqPulseOutputTime.md)

[ReqDetectionDisatance](docs/DTO/ReqDetectionDisatance.md)

[ReqPulseActiveState](docs/DTO/ReqPulseActiveState.md)

[ReqPulsePinOutput](docs/DTO/ReqPulsePinOutput.md)

[ReqSelfCheckActiveState](docs/DTO/ReqSelfCheckActiveState.md)

[ReqTeachingMode](docs/DTO/ReqTeachingMode.md)

[ReqGuideBeam](docs/DTO/ReqGuideBeam.md)

[ReqID](docs/DTO/ReqID.md)

[ReqMotorSpeed](docs/DTO/ReqMotorSpeed.md)

[ReqWarningArea](docs/DTO/ReqWarningArea.md)

[ReqFogFilter](docs/DTO/ReqFogFilter.md)

[ReqRadiusFilter](docs/DTO/ReqRadiusFilter.md)

[ReqContamDetectionMode](docs/DTO/ReqContamDetectionMode.md)

[ReqNetworkInfo](docs/DTO/ReqNetworkInfo.md)

### Get

[ResLiDARList](docs/DTO/ResLiDARList.md)

[ResBasicConfig](docs/DTO/ResBasicConfig.md)

[ResDefaultInfo](docs/DTO/ResDefaultInfo.md)

[ResNetworkInfo](docs/DTO/ResNetworkInfo.md)

[ResTeachingArea](docs/DTO/ResTeachingArea.md)

[ResTeachingMode](docs/DTO/ResTeachingMode.md)

[ResMotorSpeed](docs/DTO/ResMotorSpeed.md)

[ResWarningArea](docs/DTO/ResWarningArea.md)

[ResFogFilter](docs/DTO/ResFogFilter.md)

[ResRadiusFilter](docs/DTO/ResRadiusFilter.md)

[ResContamDetectionMode](docs/DTO/ResContamDetectionMode.md)

[ResCloudPoint](docs/DTO/ResCloudPoint.md)

[Response](docs/DTO/Response.md)

### Type

[ErrCode](docs/DTO/ErrCode%20143f454b48f5804f9621fdba345aadda.md)

[EthMode](docs/DTO/EthMode%20143f454b48f58033bb76e44ec26b8618.md)