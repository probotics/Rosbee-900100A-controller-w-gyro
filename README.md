# Rosbee-900100A-controller-w-gyro
New driver board and firmware for Rosbee

This new RosBee controller has a 4 channel ADC measuring battery voltage and current and internal supply voltages

If the input volatge drops below 10.00 V the alarm bit is set and the motion stopped.

Chec the platform status by regularly checking status.

The platform has as well a three axis gyro.

Each wheel has its own PID speed control making sure that any commande velocity is followed as good as possible independent of 
any loading or friction on the wheel.



