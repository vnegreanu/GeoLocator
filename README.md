GeoLocatorCAPL script used to decode some messages from CAN and send them via sockets to a Java app 

  - Imports custom .cfg configuration file in CAnoe format
  - Supports multichannel ISOTP for CAN messages
  - Decodes information received from NMEA frames via CAN
  - Decodes Longitude, latitude, altitude, date/time, heading and speed. 
  - Supports WakeUp/Sleep and Network Management functionalities
  - Packs everything in alligned structures and sends them via UDP socket to a Java app for map display.
