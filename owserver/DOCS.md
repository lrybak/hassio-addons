# owserver

The addon provide owserver to read 1-Wire devices over DS2480B-based bus master serial device

## Configuration

**Note**: _Remember to restart the add-on whenever configuration change._

Example add-on configuration:

```yaml
owhttpd: false
device: ''
```

### Option: `owhttpd`

Enable to start the embedded owhttpd server (Default false).

### Option: `device`

Specify DS2480B-based bus master. Keep it empty '' to mock with FAKE device.

## Network

Map TCP port of owhttpd server on your host system (Default 2121)

## Home Assistant integration

1. Configure and start addon. With default configuration addon starts with fake (mocked) devices.
1. Add to Home Assistant through the Integrations. Go to Integrations, Add Integration, Choose 1-Wire, Connection type: OWServer, Host: 9910c4be-owserver, Port 4304 (default).
1. That's it. On the integrations page wou will find 1-Wire integration with discovered devices.