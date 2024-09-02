# Real Time Collision Handling
## Project Description
![col](https://github.com/user-attachments/assets/54a49b09-41a1-4010-88be-4d6edef1cbc3)

The project was originally built utilising Directx11  utlising the legacy [DirectX SDK](https://www.microsoft.com/en-gb/download/details.aspx?id=6812) it is has now suggested to utilise the modern Windows SDK instead. Instead of implementing the newer SDK for DirectX11 I have decided to learn DirectX12 to update this project. There are more details contained within the respository archiving my learning of this updated SDK [found here](https://github.com/MoAgilah/Introduction-to-Game-Programming-with-DirectX12).
The project itself demonstrates the following Real time collision handling techniques:
- Intersection tests for Moving Sphere To Sphere.
- Intersection tests for Ray Sphere.
- Intersection tests for Ray Cyclinder.
- Intersection tests for Ray Triangle.
- Intersection tests for Sphere Poly Intersection.
- One Dimensional Sweep And Prune
- Collision resolution - impulse, coefficient of restitution, bounce, rest

On the update of the project to a DirectX12 project, I intend to add the following:
- [ ] improve coming to a rest.
- [ ] introduce bounding hierarchy volume.
- [ ] Real time collision checks.

## Project Controls
For all Camera states:
| Key    | Response |
| -------- | ------- |
| space bar  | toggle reduce framerate to 1 frame a second   |
| w  | toggle wireframe    |
| c | change camera state     |
| r | drop a ball on a random triangle |
| t | drop a ball on the flat top triangle |
| u | move marked triangle left to right |
| i | move marked triangle right to left |
| d | drop debug ball on one of three corners or the center of the top triangle |
| n | move debug ball target |
| e | deactivate all active balls |
| f | drop a ball on marked triangle and it's inverse marked triangle |
| g | deactivate the bottom triangles |
| h | reenabled the bottom triangles |
| up key | increment number of balls |
| down key | decrement number of balls |
| b | drop all of the number of balls |
| m | cycle heighmap to drop balls on |

The following camera states are available:
- Side
- Top

Whilst in CameraState::Side:

| Key    | Response |
| -------- | ------- |
| q | zoom camera in     |
| a | zoom camera out    |
| o | rotate camera left    |
| p | rotate camera right     |
