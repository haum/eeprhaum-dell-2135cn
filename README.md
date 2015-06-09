# eeprhaum-dell-2135cn

## Dump eeprom using R-Pi

```
echo "24c02 0x50" > /sys/class/i2c-adapter/i2c-1/new_device
cat /sys/class/i2c-adapter/i2c-1/1-0050/eeprom > /tmp/eeprom.bin
```
