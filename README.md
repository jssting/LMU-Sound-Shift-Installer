# LMU Shift Sound
This application will allow you to set a beep sound to be set to match a specific RPM to support optimimal shifting and draws inspiration from the `Sound Shift` app created for IRacing, but was recreated from the ground up for LMU.

## How does it work
It uses the `rFactor2SharedMemoryMapPlugin64.dll` telemetry Plugin dll which provides the telemetry, and uses the LMU API's for static data. The LMU Shift Sound uses the telemetry stream to update Gears and RPM's, and uses the data to play a beep sound at the time where the set Limit matches the current gear and engine RPM, helping you to easily get a audible notification at the optimal shift point that you can adjust. 
The service will automatically connect to the LMU API and Telemetry services when you enter the car in the pits and will also automatically disconnect when you exit the car.

## Installation

1. Download the MSI files (or extract from the ZIP File)
2. Install the application.
3. Once installed, Launch the application.
4. If required, if the Windows Desktop runtime 9.0 is not installed (windowsdesktop-runtime-9.0.16-win-(x64/x86/arm64) it will be requested during the 1st run of the application.

<img width="447" alt="Screenshot 2026-05-21 114644" src="https://github.com/user-attachments/assets/ad8c2911-a4fe-41c5-a1af-4690c368340c" />
   
5. Follow the instructions located under the 'help' menu to enable the 'rFactor2SharedMemoryMapPlugin64.dll' to receive telemetry from LMU.
6. You will have to allow the service to communicate 

## Setting a Profile for a Car 

1. Start LMU and go into a practice session with the car you want to setup. 
2. Check that the service is connected, and that the team name is showing.

<img width="612" height="459" alt="Screenshot 2026-05-31 194020" src="https://github.com/user-attachments/assets/571e3e61-27d2-4c86-a298-a24acdcbf756" />

3. Then, set the RPM settings, delay and volume you require and click on save.

You find the application useful, please feel free to buy me a coffee at [BuymeaCoffee](https://buymeacoffee.com/jssting)






