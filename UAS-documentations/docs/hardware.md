# Drone Hardwares

This section will discuss some main hardware required for drone building and RC UAS operational components. 

## Flight Controller (FC)
Flight controller (often called FC) is an essential component for any UAS aircraft, consisting of internal sensors required for UAS's detection of its orientation and movements in space. The FC is the center of all UAS computations and communications between its components and any ground control station connecting to the UAS, allowing processing of critical mission parameters and connected sensors.

Some of the common sensors onboard the FC includes:

<!-- * The inertial measurement unit (IMU)..... -->
* Accelerometers
    * Provide an instantaneous acceleration data for the drone's motion
* Gyroscopic sensor
    * A gyro sensor works to provide rotational motion awareness for the UAS
* Barometer
    * Utilizes atmospheric pressure to determine altitude
* Magnetometer
    * Obtain magnetic heading and compass data

Note that most FC may contain multiple of the same sensors for redundency.


## Power Module
Power Modules are what connects a battery to the Flight Controllers, Motors, or some other components. It has an internal voltage regularator, ensuring that a constant 5V power can be used to power an applicable FC.

Prior to selecting power module, we suggest checking the specification of your UAS components to ensure compatibility and sufficient power outputs.

## RC Receivers (RX)
Receivers are crucial for any RC operations and safety measures. Receivers are what will communicate with an RC transmitter to allow manual command inputs from Pilot to the UAS. We recommend all UAS operations to have a manual RC overrides and kill switch set up for safety.

The receivers are directly connected to the FC, communicating with the UAS through different transmission protocals

## Transmitter (TX)
Transmitters are remote controllers that remotely communicate with the receivers to provide inputs for the UAS. 

## Telemetry Radios
Telemetry radios transmit messages among the UAS to its respective Ground Control Station (GCS) the GCS can receive messages such as attitude, altitude, GPS data, and speed. This is useful when performing outdoor UAS operations where flight data can be read by ground pilots.

