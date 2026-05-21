# LMU Shift Sound
This application will allow you to set a beep sound to be set to match a specific RPM to support optimimal shifting and draws inspiration from the `Sound Shift` app created for IRacing, but was recreated from the ground up for LMU.

## How does it work
It uses the `LeMansUltimateTelemetryPlugin.dll` telemetry Plugin dll created by [Fedinand Ernst](https://gitlab.com/shin0bi/lmu-socket) which provides the telemetry as a UDP stream on port 5000. The LMU Shift Sound then uses the stream to get the Team Name, Gears, RPM's etc and uses the data to play a beep sound at the time where the set Limit matches the current gear and engine RPM, helping you to easily get a audible notification at the optimal shift point that you can adjust. 

## Installation

1. Download the MSI files (or extract from the ZIP File)
2. Install the application.
3. Once installed, Launch the application.
4. If required, if the Windows Desktop runtime 9.0 is not installed (windowsdesktop-runtime-9.0.16-win-(x64/x86/arm64) it will be requested during the 1st run of the application.

<img width="647" height="466" alt="Screenshot 2026-05-21 114644" src="https://github.com/user-attachments/assets/ad8c2911-a4fe-41c5-a1af-4690c368340c" />
   
6. If you have Windows firewall active, a popup will appear to allow the service through the firewall. This is due to the fact that it connects to the telemetry on 127.0.0.1 over UDP on port 5000. You will have to allow the service to communicate to be able to get the telemetry from LMU

<img width="410" height="413" alt="Screenshot 2026-05-21 114829" src="https://github.com/user-attachments/assets/4802c485-2110-4855-b37a-288f86dc3660" />
   
8. Follow the instructions located under the 'help' menu to enable the 'LeMansUltimateTelemetryPlugin.dll' to receive telemetry from LMU.
9. You will have to allow the service to communicate 

## Setting a Profile for a Car (associated to a Team)
***Note: Due to the way we receive Telemetry from LMU, which only provides the team name, not the car model, we need to associate the car to the team and not vice versa.***

1. Start LMU and go in to practice session with the car you want to setup. 
2. Check that the service is connected, and that the team name is showing.

<img width="608" height="447" alt="Screenshot 2026-05-21 110715" src="https://github.com/user-attachments/assets/1feb720f-cb61-41cf-8454-73ad104a30b6" />

3. Then, select the specific car, set the RPM settings, delay and volume you require and click on save.
4. When Loading a the same car with a different team, you will need to select the car to associate it, once selected, the saved setting will be loaded. 
5. Click Save to add the new association.


You find the application useful, please feel free to buy me a coffee at [BuymeaCoffee](https://buymeacoffee.com/jssting)






