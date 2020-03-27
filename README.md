# Track-COVID-19-Main
The general idea is to have an Android and an iOS application that can detect the presence of other apps through Bluetooth.

Each app would generate its own id and would keep it private, only boradcasting it to nearby apps.
Apps would detect the other nearby apps ids and store the encounter.
Apps would periodically check a list on a centralized server in order to recognize if any of its encounters corresponds to an infected person.
If an encounter with an infected person is detected, the app alerts the user, who should inform the authorities and proceed to be tested.

Apps would not upload any data at all: the only internet access would be limited to downloading information from the centralized server.
This guarantees that the user is not tracked in anyway other than by the apps that are nearby at a given time.

Anyone may use any idea, code, or any kind of asset present in the Track-COVID-19 repositories.
