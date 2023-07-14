# Gigabyte Z390 UD Ventura install — OpenCore

Tested with Monterey installation, then updated to Ventura without a problem.

You don't really need to know all the hardware list here, beside the MB model and the GPU maybe (using a 5XX serie).

I don't use internal MB features that I can replace with "real", dedicated ones when possible (e.g Sound card, WIFI…), so you're on your own here, except for USB.

---

**USB mapping** extracted from: <https://github.com/7gill/Gigabyte-Z390-UD-Catalina-install> (USBMap.kext).

All USB 3 PORTS ARE WORKING AT EXPECTED SPEED.

Links to other successful installation
- <https://www.tonymacx86.com/threads/success-gigabyte-z390-ud-open-core-0-6-3.305982/>
- …

I don't remember where I found this tailored base EFI for this Motherboard, which I customized further.  
I will put this here as soon as I found that info again (thanks buddy, I owe you so much).

## Notes

Several improvements over an older Catalina + Clover installation on the same hardware.  
UI is much much smoother (AMD 5xx serie), less hiccups with multiple monitors when they get out of sleep, etc. Can't list all the small improvements brought by switching to OpenCore (I post-poned this for so long, but it was worth it).


THANKS TO ALL PEOPLE INVOLVED IN MAKING X86 MACOS ALIVE AND KICKING (Dortania, previous pionneers like Clover and Chameleon, and all the communities scattered on the interweb…), as well as [allowing macOS in QEMU](https://github.com/kholia/OSX-KVM), or upgrading older macs to "unsupported" newer systems.

---

And please, Apple, just make a computer with PCI Slots supporting nVidia and AMD cards… That's all we're asking. THANKS IN ADVANCE.
