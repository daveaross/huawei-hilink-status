huawei-hilink-status
===================

Unsophisticated Python command-line utility to show device information and the connection status from Huawei HiLink modems. Tested with 2 samples of Huawei's E3331 modem.

## Installation

```
apt-get install python-pip
pip install xmltodict
git clone git://github.com/daveaross/huawei-hilink-status
cd huawei-hilink-status
python ./hstatus.py
```

## Usage example

```
$ sudo python hstatus.py 
  Huawei X9EBY15408001520 GW Modem (IMEI: 864568012669595)
    Hardware version: CH1E3331SM
    Software version: 22.146.33.01.74
    Web UI version: 17.100.14.02.74
    Serial: X9EBY15408001520
    MAC address (modem): BA:AB:BE:34:00:00
    Connection status: Connected
      Network type: HSPA+ (4G)
      Signal level: ▁▃▄▆ (70%)
      Roaming: Disabled
      Modem WAN IP address: 100.86.42.34
      Public IP address: 120.21.39.112
      DNS IP addresses: 10.143.147.147, 10.143.147.148
      Network operator: Vodafone AU
      Connected for: 02:42:18 (hh:mm:ss)
      Downloaded: 900.27 KB
      Uploaded: 225.39 KB
    Total downloaded: 834.64 MB
    Total uploaded: 532.64 MB


$ python ./hstatus.py
Huawei E3276 LTE Modem (IMEI: 861711012616361)
  Hardware version: CH2F4276GM
  Software version: 22.250.04.00.186
  Web UI version: 22.100.05.00.03
  Serial: B3A3TC2313833197
  MAC address (modem): 00:0D:87:22:34:AC
  Connection status: Connected
    Network type: UMTS (3G)
    Signal level: ▁▃▄▆█ (92%)
    Roaming: Enabled
    Modem WAN IP address: 10.197.32.60
    Public IP address: 32.131.81.221
    DNS IP addresses: 212.113.0.4, 66.28.0.61
    Network operator: Swisscom
    Connected for: 00:49:33 (hh:mm:ss)
    Downloaded: 737.0 KB
    Uploaded: 178.0 KB
  Total downloaded: 47.69 MB
  Total uploaded: 19.86 MB
  Unread SMS: 1
```

