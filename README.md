# About This Repository


This Repository contains examples of using the EL3773 terminal along with the TF3650 Power Monitoring library. The examples included can be used for either 1 Phase AC monitoring and 3 Phase AC monitoring. 

For implementing the TF3650 Power Monitoring functions, there is a strict Analysis Toolchain and ID workflow that must be maintained. Notice that the Source FB takes toolchain "Destination IDs" as an array for initialization, these IDs are defined in the sample as an Enum for easier use.

The advantage of using the EL3773 and TF3650 together is that your application can have a very high-end method of power/grid monitoring. In the image below, we are using the EL3773 in a home office that is supplying a video projector single phase power. Meanwhile, on a separate outlet we turn on a laser projector for a heavy power draw simulation.

![PowerMonitoring_LaserPrinter](/Images/PowerMonitoring_LaserPrinter.PNG)



This sample is created by [Beckhoff Automation LLC.](https://www.beckhoff.com/en-us/), and is provided as-is under the Zero-Clause BSD license.

# How to get support

Should you have any questions regarding the provided sample code, please contact your local Beckhoff support team. Contact information can be found on the official Beckhoff website at https://www.beckhoff.com/en-us/support/.

# Further Information

Further Information on TF3650 can be found at the [Beckhoff Infosys](https://infosys.beckhof.com) under the [PLC API](https://infosys.beckhoff.com/content/1033/tf3650_tc3_power_monitoring/6096457867.html)

## Requirements

The following components must be installed to run sample code:

- [TE1000 TwinCAT 3 Engineering](https://www.beckhoff.com/en-en/products/automation/twincat/te1xxx-twincat-3-engineering/te1000.html) version 3.1.4024.0 or higher
- TF3650 Power Monitoring
- EL3773
- Beckhoff SCT (SCT3111-0050 was used in examples)
