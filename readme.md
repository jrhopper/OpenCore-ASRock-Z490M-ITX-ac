# OpenCore-ASRock-Z490M-ITX-ac

## Working:
- Sleep/awake
- Bluetooth
- Wifi

## Not Working
- HDMI audio from the iGPU -  no clue how to make it work, if you figure out please let me know :) 


## Not Tested 
- ~~DisplayPort - I have no monitor yet to test it.~~ it works :)
- ~~On-Board Audio. It is detected but never connected anything there to make sure. (only use Bluetooth headphones)~~ It works :)
- Well I have no ideia if iMessage and those sort of things are working because I dont use them.
- dGPU as I dont use any. 
- USB Type-C port speed, works fine with an Type-A to Type-C adapter though. 


## Software 
 - OpenCore 0.6.3
 - MacOS Big Sur 11.0.1 (20B29)
 - SMBios: IMac20,1 (opencore recomendation for comet lake)
 
## Kexts
- Beaware the USBMap.kext that I mapped using the USBMapTool disables all from usb headers. If you need them. Replace this with InjectUSBAll and do the proper mapping using the USBMapTool. I will probably change this as soon as I get a new case.   

## Hardware List 

- ASRock-Z490M-ITX-ac
- CPU 10600 (non k)
- Kingston HyperX 2x8GB 2400
- Sabrent Rocket NVME 4.0 
- Wifi /BT BCM9460CS2 + M.2 key E adapter 
- GPU: iGPU Intel 630

## Update to Big Sur.
I downloaded the full installation with the gibmacos to prepare an usb  drive just in case. In the end just opened with installer from within Catalina and followed the steps, 35min later averything was working perfectly. No need to do any change.
