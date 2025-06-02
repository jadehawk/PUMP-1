# About

The PUMP-1 is a plant watering machine. One end is connected to a water source ( that is measured by the  Water Exists sensor ). The other goes into a plant. This is a ESPHome sensor using a ESP32-C6 chip and works with Home Assistant. It will be used to water plants, fill coffee machines, top off fish tanks and more

## Instructions

Make sure to send the about section as context for all initial requests when starting a task. When you complete a todo item please mark it as complete

## Todo

1.1 ✓ Don't run the pump if no water
1.2 ✓ Allow a switch to override this protection
1.3 ✓ Add a number entity that is the number of seconds to run the pump for
1.4 ✓ Add a button that when triggered turns the pump on for the set number of seconds
1.5 ✓ Add a API service that takes in a number of seconds and then turns the pump on for that amount of time
1.6 ✓ Add safety alerts if the pump has been running too long, needs a switch override though
1.7 ✓ Add functionality to check the water level every hour, if empty then chirp the buzzer. Allow turning this off with a switch.
1.8 ✓ If the reset_button is tapped then turn the pump on for the time set in 1.3
1.9 ✓ Allow user to toggle a switch to invert the water exists logic. Essentially for filling say a fish tank, I want to pump until the water level reaches my sensor then stop
