Particle-Manchester-ExpandedPayload Library
===========================================

(Expanded-payload w/checksum) Particle Manchester library for 315/433Mhz transmitter/receivers.

* ID is now 8-bit, allowing up to 256 different devices on the same 315/433MHz network.
* Checksum changed to 8-bit
* Payload is now 16-bit, allowing more data to be sent with checksumming.
* Total length of checksummed communications is 4 bytes


Instructions
============

Refer to ManchesterTX/RX_Check folder. All other examples are essentially unchanged, as they rely on a single uint16_t or uint8_t array for sending non-checksummed data.

Please read Manchester.h for details on the implementation of the protocol.

This library requires SparkIntervalTimer library to function.


Credits
=======

Expanded-payload Particle Manchester library for 315/433Mhz transmitter/receivers by Chuan Khoo, August 12/2015

Manchester library for 315/433Mhz transmitter/receivers adapted for Spark by Paul Kourany, May 21/2014

Adapted from mchr3k's Arduino library using SparkIntervalTimer timer library by Paul Kourany
