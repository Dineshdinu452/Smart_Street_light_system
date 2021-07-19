# Smart_Street_light_system
The principle behind the working of the project lies in the functioning of IR Sensor. We used a Transmissive type IR Sensor in this project and (toggle switch in stimulation).
In Transmissive IR Sensor, the IR transmitter and receiver are placed facing each other so that IR receiver always detects IR Rays emitted by the IR Transmitter.
If there is an obstacle between the IR Transmitter and Receiver, the IR Rays are blocked by the obstacle and the IR Receiver stops detecting the IR Rays.
This can be configured to turn ON or OFF the LEDs (or street lights) with the help of microcontroller 8051.
Here 8051 is programmed in such a way that when when car or moving object is detected by sensor 1 then consecutive street light(led) is turned on leaving all other street light 2 and 3 turned off . when sensor 2 detect object then corresponging street light 2 will be on leaving light and 3 will be off .when sensor 3 detect object the corresponding light 3 will be on leaving light 1 and 2 wiil be off . in last case wthen all theee sensor detect object at a same time the corresponding all therr lights will on .


![street light proteus](https://user-images.githubusercontent.com/73679496/126064530-798fbabf-b424-49a6-ac1d-a91df43efdfc.png)
