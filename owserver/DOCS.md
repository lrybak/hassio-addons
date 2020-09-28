# onewire2mqtt

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