# Asus Vivobook S15 S530UA

# Detail

	Version:	1
	Date:		04/27/2019
	Support:	All BIOS
	macOS:		Mojave 10.14.4
	Status:		Stable

# System specification

	1. Name:		Asus Vivobook S530UA BQ100T
	2. CPU:			Intel Core i5-8250U
	3. Graphic:		Intel UHD620
	4. Wifi:		Intel Dual Band Wireless-AC 8265, replaced with DW1560
	5. Card Reader:		n/a (Not tested)
	6. Camera:		ASUS UVC HD
	7. Audio:		Realtek ALC256
	8. Touchpad:		ELAN1300
	9. Bios Version:	303
	
# Not working

	1. Card Reader
	2. Instant Hotspot (Continuity)

# Thing will never able to use

	1. Fingerprint.
	2. FN + media controller's key.

# Know problems

	Screen flickering when charging after wake from sleep.
	
# Installation

	1. Build a USB installer and copy CLOVER folder to USB's EFI folder.
	2. After install, install Clover to your macOS drive and copy CLOVER folder to your laptop main EFI folder.
	3. Use any kext installer app to install kext from Kexts/LE or SLE. (If you are not sure, see the Note section)
	4. Copy hda-verb from misc folder to /usr/bin.
	5. Reboot and enjoy
	
# DW1560 kext install

	1. Copy kext from DW1560/CLOVER to CLOVER/kexts/Other.
	2. Use any kext installer app to install kext from DW1560/LE or SLE. (If you are not sure, see the Note section)
	3. Reboot and enjoy.

# Note

	1. SMBIOS in clover.plist is fake, you need to rebuild yourself.
	2. "LE or SLE" titled folder means you can install kext to either LE or SLE. If you are manually copying the kext, make sure you repair premissions and rebuild kext cache after the copy. The difference between LE and SLE you can found on Google.
	
# Special thanks

	1. **tctien342** for providing base Clover folder (https://github.com/tctien342/Asus-Vivobook-S510UA-High-Sierra-10.13-Hackintosh)
	2. **Hackintosh - The OS X on PC World** (Facebook group: https://www.facebook.com/groups/hackintoshPC)

# Contact 
	
	Email:			superzeldalink@gmail.com
	Facebook Messenger:	m.me/zeldalink.168
	
