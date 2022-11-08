# Home Assistant bencorrado Add-on: GPSD

![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg


gpsd is a service daemon that monitors one or more GPSes or AIS receivers attached to a host computer through serial or USB ports, making all data on the location/course/velocity of the sensors available to be queried on TCP port 2947 of the host computer.

## About

With gpsd, multiple location-aware client applications can share access to supported sensors without contention or loss of data. Also, gpsd responds to queries with a format that is substantially easier to parse than the NMEA 0183 emitted by most GPSes. The gpsd distribution includes a linkable C service library, a C++ wrapper class, and a Python module that developers of gpsd-aware applications can use to encapsulate all communication with gpsd. Third-party client bindings for Java and Perl also exist.

Be sure to add the [GPSD  integration](https://www.home-assistant.io/integrations/gpsd/) after starting the add-on.

The gpsd project is the combined effort of
many [individuals][gpsd-acknowledgements].

## Support

You can [open an issue here][issue] GitHub.


## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it, pull requests are welcome.

Thank you for being involved! :heart_eyes:

[issue]: https://github.com/bencorrado/addons-bencorrado/issues
[gpsd-acknowledgements]: https://www.openhub.net/p/gpsd/contributors

