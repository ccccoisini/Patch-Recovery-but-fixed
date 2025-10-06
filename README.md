# Patch-Recovery

Based on https://github.com/Johx22/Patch-Recovery (I actually Fixed Error 2)

This CI service patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://github.com/phhusson/samsung-galaxy-a51-gsi-boot)

# How to use:
- clone this repo.
- Copy your recovery.img/recovery.img.lz4 on the folder where you cloned the tool.
- Run "chmod 777 magiskboot" and "chmod 777 avbtool" without quotes.
- Run "./script1.sh" and "./script2.sh" without quotes.
- The Patching process will start
- A Patched-Recovery.img will be generated at the end of the process.
