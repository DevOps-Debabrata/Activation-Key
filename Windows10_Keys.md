# Windows 10 activation keys
> ***Note: please buy a original Windows key. This is only for educational purposes. Some keys might not work.***

# Tutorial
First type:
```
slmgr /ipk <YOUR KEY>
```
And activate your default KMS server using this following commands below:
```
slmgr /skms kms8.msguides.com
```
and
```
slmgr /ato
```
(optional) You can restart your computer to ensure the activation.
```
shutdown /r /t 0
```

# Example of a script - Windows 10 Home
```
@echo off
title Windows 10 Activation Service
slmgr /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
slmgr /skms kms8.msguides.com
slmgr /ato
cls
echo Restarting now...
shutdown /r /t 0
```
# Keys
```
Home - TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
Home N - 3KHY7-WNT83-DGQKR-F7HPR-844BM
Home Single Language - 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH
Home Country Specific - PVMJN-6DFY6-9CCP6-7BKTT-D3WVR
Professional - W269N-WFGWX-YVC9B-4J6C9-T83GX
Professional N - MH37W-N47XK-V7XM9-C7227-GCQG9
Professional Workstations - NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J
Professional Workstations N - 9FNHH-K3HBT-3W4TD-6383H-6XYWF
Professional Education - 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y
Education - NW6C2-QMPVW-D7KKK-3GKT6-VCFB2
Education N - 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ
Enterprise - NPPR9-FWDCX-D2C8J-H872K-2YT43
Enterprise N - DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4
Enterprise G - YYVX9-NTFWV-6MDM3-9PT4T-4M68B
Enterprise G N - 44RPN-FTY23-9VTTB-MP9BX-T84FV
Windows 10 Pro build 10240 – VK7JG-NPHTM-C97JM-9MPGT-3V66T
```