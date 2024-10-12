# createwindowsmedia
### A Swift-based command-line tool to allow you to create Windows installation media (Using UEFI_NTFS) on macOS. 

This isn't releasing for a long time, and this is just going to be one single component of a significantly larger project which will be a bit torturous to build.

The goal of this at least is to allow you to make a Windows 8+ USB drive on macOS without needing a PC for Microsoft's Media Creation Tool. And usage will be similar to Apple's createinstallmedia for macOS.

Arguments:

--volume, A path to a volume that you don't mind erasing to create your installation media. (Required)

--imagepath, A path to a copy of Windows 8+ in ISO format to create the bootable media from. (Required)

--nointeraction, Writes Windows media without confirming any actions.

--config, Modifies Windows configuration, you'll learn what this'll do later

--help, Displays the help page.
