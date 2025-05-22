# ESPHome-Garden-Watering-System
ESPHome and Home Assistant Garden Watering System with 2 controllers and 7 valves

This project was created to provide a Garden Watering System using Home Assistant and ESPHome.
There are 2 physical controllers controlling up to 7 solenoid valves.
An extra requirement was the need to monitor the water tank level and cut power when too low.

The ESPHome Sprinkler component is used to manage the watering sequence within each controller.
Home assistant is used for management and also coordination between the controllers.
