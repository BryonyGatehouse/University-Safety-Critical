# Assignment 1 : Steam Boiler

Design and program the controller for a Steam Boiler with multiple pumps, a controller for each pump, sensors, and a valve.

- **MODE WAITING** waiting for a message from the physical units. The system is not in operation.
- **MODE READY** sending messages until a reply is recieved. The program is in operation and the system is waking up.
- **MODE NORMAL** running in standard operating mode.
- **NODE DEGRADED** maintaining the water level. The system is operating with one of the non-vital physical units broken.
- **NODE RESCUE** maintaining the water level. The water level sensor is broken.
- **NODE EMERGENCY STOP** stopping or stopped. The system is stopped.

The program must include safety procedures to prevent the steam boiler from damaging itself or others. All possible scenarios (within our abilities) should be accounted for.
