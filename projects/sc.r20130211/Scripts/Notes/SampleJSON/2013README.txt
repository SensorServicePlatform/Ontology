
2013CmuGetAllDeviceTypes.txt is the output from GetAllDeviceTypes API call. 
	 = get me all the instances of the device catalog.
	This should end up defining new CMU subclasses of Device

2013CmuQueryAllDevices.txt is the output from the confusingly named GetAllDevices API call.
	= get me all the instances of devices
	This should populate the model with instances of Device, which can become instances of subclasses using SPIN rules.

2013CmuGetAllSensorTypes.txt is the output from GetAllSensorTypes API call. 
	 = get me all the instances of the sensor catalog
	This should end up defining new CMU subclasses of Sensor

2013CmuQueryAllSensors.txt is the output from the confusingly named GetAllSensors API call.
	= get me all the instances of sensors
	This should populate the model with instances of Sensor, which can become instances of subclasses using SPIN rules.

2013CmuGetReadingFromAllSensorsOfType.txt is the output from the confusingly named GetLatestReadingsFromAllDevices API call.
	= get me the latest reading from all sensors of type "x", where "x" is supplied in the call.
	This should populate the model with instances of Measurement