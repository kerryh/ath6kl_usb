ath6kl_usb
==========

ath6kl_usb is a branch from ath6kl for USB. The repository include the compat and cfg80211 components from below repositories :
compat : 
  - git clone https://github.com/senthilb/ath6kl-compat-wireless.git
  - cd ath6kl-compat-wireless
  - git checkout -b 7b33cfd
  - clone the "compat", "include", "udev" and "compat/scripts/compat_firmware_install" directories as COMPAT module for ath6kl_usb
  
	
cfg80211 :  
  - git clone http://github.com/kvalo/ath6kl.git
  - cd ath6kl 
  - git checkout 009f2ea7c0a3009b44940d820e407a21f3d53d52
  - clone the "ath6kl/net/wireless" directory as CFG80211 for ath6kl_usb developing 

