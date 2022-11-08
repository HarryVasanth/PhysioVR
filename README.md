# PhysioVR

PhysioVR is currently in development phase and is not yet ready for release, if you want more information please check the [wiki](https://github.com/HarryVasanth/PhysioVR/wiki/Home).
  
The first release will be ready soon!
  
**Working features:**  
  
* PhysioAdapt:
  
	* UI implemented  
	* Receives UDP data
	* Identifies Sensor variable
	* Instantiates/Updates Sensor variable
	* Instantiates Environment + Environment variables
	* Identifies and updates Environment variables (from UDP)
	* PhysioAdapter updates environment variables depending on sensor values
	* DataExporter implemented (csv log)
	* Sends UDP data with all existing variables

* PhysioWOz:
  
	* UI Navigation implemented  
	* Receives UDP data but doesn't parse the data
	* Prepared to send data but not yet streaming
