# Home Assistant Add-on: owserver

![Current version][version]

Provide owserver to read 1-Wire devices over DS2480B-based bus master serial device

## About

This addon provides you owserver instance to read 1-Wire devices over DS2480B-based bus master serial device and exposing reading to Home Assistant via the native integration. Addon has been tested with **[MERA-PROJEKT MP00206-P](http://www.meraprojekt.com.pl/mp00206-p.html)** but shoud work well with other devices based on DS2480B chip.

## Installation

1. Access your Home Assistant, go to **Supervisor** -> **Add-on Store** and add this URL as an additional repository: `https://github.com/lrybak/hassio-addons`
2. Find the "owserver (1-Wire)" add-on and click the "INSTALL" button.
3. Configure the add-on and click on "START". With default configuration addon starts with fake (mocked) devices.
4. Add to Home Assistant through the Integrations. Go to Integrations, Add Integration, Choose 1-Wire, Connection type: OWServer, Host: 9910c4be-owserver, Port 4304 (default).
5. That's it. On the integrations page wou will find 1-Wire integration with discovered devices.

## Configuration

Please check the **[documentation](https://github.com/lrybak/hassio-addons/blob/master/owserver/DOCS.md)** page.


[version]: https://img.shields.io/badge/version-v0.1.2-blue.svg