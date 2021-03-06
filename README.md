# logair-makezurich

Vision:
Autonomous devices that can be strapped to anything to continuously map air quality, so we can make city centers more livable spaces.

What we want to achieve here:
- Build a data uplink through TTN
- Be able to drop a device somewhere for a few days and have it pinging
- Trying other LoRaWAN providers if possible
- Finding out how to stream all or most of the data our device generates within the LoRa constraints

What we have right now:
- LogAir devices & STM32s
- SX1276
- Tried to have the SX1276 upload data with the Bluepill as a MCU
- Failed
- Tried to have the murata module upload data from the Arduino BLE 33
- Managed to have that working
- Tried Murata x Bluepill
- Failed

What we need:
- People who already did similar things to jumpstart
- A Murata module? We have that now
- Inputs of any kind
