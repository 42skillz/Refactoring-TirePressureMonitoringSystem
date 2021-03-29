TirePressureMonitoringSystem refactoring kata
=============================================

Write the unit tests for the Alarm class
----------------------------------------

The Alarm class is designed to monitor tire pressure and set an alarm if the pressure falls outside of the expected range. The Sensor class provided for the exercise fakes the behavior of a real tire sensor, providing random but realistic values. Note that there is a MockAlarm and a StubAlarm class provided in the "tests" folder. The purpose of these is purely to demonstrate how a mock and a stub look, you won't need them to complete the exercise.

### Alarm class:
Monitors tire pressure and sets an alarm if the pressure falls outside of the expected range.

### Sensor Class:
Simulates the behavior of a real tire sensor, providing random but realistic values.

Write the unit tests for the Alarm class.
Refactor the code as much as you need to make the Alarm class testable.

Minimize changes to the public API as much as you can.

### Actions: 
Parametrize Constructor & Extract Interface
