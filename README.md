# Gigabyte Z390 UD Ventura install — OpenCore 0.9.3

Tested with Monterey installation, then updated to Ventura (13.4.1 - 22F82) without a problem.

You don't really need to know all the hardware list here, beside the MB model and the GPU maybe (using an AMD RX 5xx series).

I don't use internal MB features that I can replace with "real", dedicated ones when possible (e.g Sound card, WIFI…), so you're on your own here, except for USB.

---

**USB mapping** extracted from: <https://github.com/7gill/Gigabyte-Z390-UD-Catalina-install> (USBMap.kext).

All USB 3 PORTS ARE WORKING AT EXPECTED SPEED.

Links to other successful installation

- <https://www.tonymacx86.com/threads/success-gigabyte-z390-ud-open-core-0-6-3.305982/>
- …

I don't remember where I found this tailored base EFI for this Motherboard, which I customized further.  
I will put this here as soon as I found that info again (thanks buddy, I owe you so much for the SSDT's etc.).

## Notes

Several improvements over an older Catalina + Clover installation on the same hardware.  
UI is much much smoother (AMD 5xx serie), less hiccups with multiple monitors when they get out of sleep, etc. Can't list all the small improvements brought by switching to OpenCore (I post-poned this for so long, but it was worth it).

Geekbench **5** score should be in the 1300-1400 | 8000-8500 ballpark.  
43500-45500 (OpenCL) | 51000-53000 (Metal)

Geekbench **6** score should be in the 1600-1800 | 7900-8200 ballpark.  
50800-51500 (OpenCL) | 61000-63000 (Metal)

This is for an heavily water-cooled 9900K, uncastrated by a shady BIOS ([95W vs 125W TDP](https://www.comptoir-hardware.com/actus/processeurs/37749-tdp-et-magouilles-chez-intel-test-du-9900k-sagement-a-ses-95w.html)).  
NO THROTTLING WHATSOEVER 🔥.  
AFAIK, all cores are kept at full turbo at all time (4.7~5GHz IIRC).

GPU is an AMD RX 590.

## Acknowledgements

THANKS TO ALL PEOPLE INVOLVED IN MAKING X86 MACOS ALIVE AND KICKING (Dortania, previous pionneers like Clover and Chameleon, and all the communities scattered on the interweb…), as well as [allowing macOS in QEMU](https://github.com/kholia/OSX-KVM), or upgrading older macs to "unsupported" newer systems.

---

And please, Apple, just make a computer with PCI Slots supporting nVidia and AMD cards… That's all we're asking. THANKS IN ADVANCE.
