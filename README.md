# Arduino driver for PMW3901 optical flow sensor

This library is based on on the [Bitcraze_PMW3901](Bitcraze_PMW3901) library, q.v. for details.  I made
the following modifications:

* Support different SPI buses (SPI1, SPI2, ...; defaults to SPI)

* Support software SPI via the [DigitalIO](https://github.com/greiman/DigitalIO) library
