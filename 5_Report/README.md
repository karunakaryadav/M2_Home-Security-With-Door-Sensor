# DESCRIPTION:-

Here is a Project developed as mini project in embedded c as Home Security With Door Sensor Door sensors are an essential component of your home security system In this mini project you can get status of our Home Door which is closed or open If the Led connected to atmega port is high means if Led is Flashing then you can get the idea about status of Door i.e our door is open similarly, If the Led connected to atmega controller port is low means Led is not Flashing then you can get that the Door is Closed this is all becoz of I have made a system that if Door is closed then there will be no supply to the Led so Led will not glow similarly for open of door there will be supply of 5V that i have made so that Led will glow there so this is how you can get status of your Home Door with this Embedded project.

# ABSTRACT:-

Door sensor for security purposes are widely used now. An door sensor based on electrical and electronics circuit technology is used to develop the security system as well as automatic light switching system. This security system with door sensor which could benefit every safer environment and single individual. Furthermore, the system is developed with safety environment when switching ON or OFF the light during the room door open or door close.Basically, this system is designed for security purpose to secure the home.
The system which is the designed Home Security using door sensor is designed considering some factors such as economy, availability of components and efficiency, compatibility, portability and also durability.The general operation of this system and performance is dependent on the opening and closing of the door.

# REQUIREMENTS:-

**High Level Requirements**:
|  ID   |                     DESCRIPTION                                           |        STATUS    |
|-------|-----------------------------------------------                            |------------------|
|  H_01 |    User gets idea about Door status either open or closed                 | Implemented      |
|  H_02 |   gets Door Status through specific indication                            | Implemented      |
|  H_03 |   Automatic opening and closing of Door when object in front of Door.     |  FUTURE          |

**Low Level Requirements**:

|  ID  |            DESCRIPTION                                                     |    STATUS        |
|------|----------------------------------------------------------------------------|------------------|
| L_01 |      Gets Indication of Open Door ( High LED )                             | Implemented      |
| L_02 |      Gets Indication of Closed Door ( Low LED )                            | Implemented      |
| L_03 |  Getting Indication through Specific sound ( Alarm 🚨 )                    |	Pending          |

# TEST CASES :-

|  ID    |              DESCRIPTION                                           |     INPUT       |      OUTPUT     |   PASS/FAIL    |
|--------|------------------------------------------------------------------- |---------------- |-----------------|----------------|
| K_01   |             At the stage of Opening of Door                        |    	Open door   |    	High LED	  |        PASS    |
| K_02   |             At the stage of Closing of Door	                      |      Close door	|       Low LED   |       	PASS   |

























