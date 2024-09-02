# Hiearchal Animation
## Project Description
## Project Controls

For all Camera states:
| Key    | Response |
| -------- | ------- |
| w  | toggle wireframe    |
| c | change camera state     |

The following camera states are available:
- Map
- Plane
- Gun
- Robot

Whilst in CameraState::Map:
| Key    | Response |
| -------- | ------- |
| q  | zoom camera in    |
| a | zoom camera out     |

Whilst in CameraState::Plane || CameraState::Gun:
| Key    | Response |
| -------- | ------- |
| q  | pitch upwards    |
| a | pitch downwards     |
| p  | yaw and roll left    |
| o | yaw and roll right     |
| l  | loop de loop    |
| r | barrell roll right     |
| space bar | fire gun     |

Whilst in CameraState::Robot:
| Key    | Response |
| -------- | ------- |
| 1  | change to the idle animation    |
| 2 | change to the attack animation     |
| 3  | change to the dieing animation    |
| f | held down to iterate animation frame by frame     |


