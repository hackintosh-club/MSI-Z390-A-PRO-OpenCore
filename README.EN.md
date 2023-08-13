## MSI Z390-A PRO Hackintosh OpenCore EFI

![image](ScreenShot/Z390APRO.jpg)


### [简体中文](https://github.com/hackintosh-club/MSI-Z390-A-PRO-OpenCore)

### OpenCore

[OpenCore 0.9.3](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 

### Hardware

- Motherboard: Z390
- Bios Version:E7B98IMS.110（2018-08-22）
- CPU: Intel 9th i7-9700K
- RAM: Crucial 8G*2 DDR4 2666MHz
- SSD: aigo S500 S512G MacOS
- iGPU: Intel UHD Graphic 630
- GPU: DELL AMD RX580X 2304SP
- Audio: Realtek ALC892
- Ethernet Card: Intel L219-V


### Notes

 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) or [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) build your SMBIOS

### Bios Setup

```
      
	SETTINGS  
	  |-- Advanced
	     |-- Integrated Graphics Configuration
	        |-- IGD Multi-Monitor：Enabled
			|-- DVMT：64MB
		 |-- USB Configuration
			|-- XHCI Hand-off：Enabled
		 |--  Super I0 Configuration
		       |-- Serial Port：Disabled
		       |-- LPT Port：Disabled
	  OC
	  |-- CPU FeaturesBoot
	     |-- CFG Lock：Disabled
		 |-- SW Guard Extensions(SGX)：Disabled
		Search：secure
		  |-- Secure Boot：Disabled
	   

```

### Contact Us

QQ Group: 23304408

![image](ScreenShot/QRCode.png)


### Tools

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.
