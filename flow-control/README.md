This script makes it easy to setup your ship for recieving or providing fuel for or from other ships.

## What it does
Sets the **FlowIn** and **FlowOut** values for all **Resource Bridges** on your ship.

### in
All **Resource Bridges** are set to the values **FlowIn=1** and **FlowOut=0**.

This will allow to receive fuel from other ships. The connected **Resource Bridge** on the other ship should be set up to the exact opposite values (**FlowIn=0** and **FlowOut=1**).

### out
All **Resource Bridges** are set to the values **FlowIn=0** and **FlowOut=1**.

This will allow to provide fuel to another ship. The connected **Resource Bridge** on the other ship should be set up to the exact opposite values (**FlowIn=1** and **FlowOut=0**).

### default
For every other activity this should be activated. If you add or remove stuff from the ship inventory and the mode is **in** or **out**, it can create **ghost slots** and will have to restart the game.

## Installation

* Put a Text Panel in your cockpit and rename the property **PanelValue** to **FS**.
* Put a Switch in your cockpit, rename the property **SwitchState** to **FSC** and set **SwitchStyle** to **1**.
* Now add **4** Yolol Chips and paste the scripts in them.