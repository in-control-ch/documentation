# Hub

The Hub is an interface device for 3rd party inputs.
You can build your own input devices or connect compatible off the shelf products, like the [Logitech Adaptive Gaming Kit](https://www.logitechg.com/de-ch/products/gamepads/adaptive-gaming-kit-accessories).

## Inputs

The Hub has **4 analog** inputs (A1 to A4) and **6 digital** inputs (D1 to D6).


| Abbreviation | Image                               | Hub inputs                 | Use cases                                             |
| ------------ | ----------------------------------- | -------------------------- | ----------------------------------------------------- |
| TRRS         | ![TRRS](images/TRRS_connector_abbreviated.svg) | A1/A2, A3/A4, D1/D5, D2/D6 | dual channel active devices, i.e joystick with 2 axes |
| TRS          | ![TRS](images/TRS_connector_abbreviated.svg)  | All                        | dual channel passive inputs, i.e. 2 buttons           |
| TS           | ![TS](images/TS_connector_abbreviated.svg)   | D1 to D4                   | single channel inputs, i.e. 1 button                  |

The 3.5 mm jack sockets have the following input assignments, see also [Phone connector (audio)](https://en.wikipedia.org/wiki/Phone_connector_(audio)).


| Input    | T   | R    | R    | S   |
| -------- | --- | ---- | ---- | --- |
| A1 \| A2 | A1  | A2   | 3.3V | GND |
| A3 \| A4 | A3  | A4   | 3.3V | GND |
| D1 \| D5 | D1  | D5   | n.c. | GND |
| D2 \| D6 | D2  | D6   | n.c. | GND |
| D3       | D3  | n.c. | n.c. | GND |
| D4       | D4  | n.c. | n.c. | GND |


## Settings

On Input 1 and 2, the Hub accepts stereo jack plugs with two analog signals. This is convenient for building Joysticks or other two-axis devices with just one cable.
The second analog channel for Input 1 and 2 can be activated in the device settings.

![Configurator Hub Settings](images/device_view_hub.png)