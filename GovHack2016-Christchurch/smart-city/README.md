**File formats:** csv, json

**File Descriptions:**

The datasets within this folder contain readings from four sets of sensors located around Christchurch. They collect temperature, humidity, pressure, luminosity, co2, sound readings from their respective environments.

`kite-locations.csv` - Provides the sensor ids and locations.
`metadata/`          - Example individual readings taken directly from the sensors containing sensor metadata, such as unit.
`chch-sensors.csv`   - Log of the various sensor readings.
  Format:
`localtime, kiteid, temperature, humidity, pressure, luminosity, co2, sound`

**Disclaimer:**
The sensors collecting this data are still being tested and may have issues with callibration. As such the accuracy of the data is not guaranteed. The data is provided as is, without warranty. It is intended to be an example of formats and datatypes, and will be more suitable for showing trends rather than absolute values.


