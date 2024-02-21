# Woox_R7049-V2
Custom Z2M converter for smoke alarm Woox R7049 V2


# Woox_R7049-V2 _TZE200_ft523twt

This is a custom converter that works in Zigbee2MQTT (until the device is officially added) for Woox Smart Smoke Alarm Model TS0601, manufacturerName     fingerprint: [{modelID: 'TS0601', manufacturerName: '_TZE200_ft523twt'}].

Here is how you add the custom converter in Home Assistant using the Zigbee2MQTT addon:
1) Remove the device if it is already added in Zigbee2MQTT;
2) With a file editor (Studio Code Server etc.) add the js file in the folder config/zigbee2mqtt (the folder should already be there);
3) Open the addon Zigbee2MQTT and define the custom converter. See the picture:
   ![r7049_v2](https://github.com/Jtef/Woox_R7049-V2/assets/6143681/18308227-4831-4fbe-b909-15386c3fd2fb)
  
4) Restart Zigbee2MQTT addon;
5) Start pairing the device.

Enjoy!
