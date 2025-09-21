# Method A

1. Get YuzakiKokuban-Resized.img from [Releases](https://github.com/C-F0x/yet-another-gts10pwifi-tutorial/releases/tag/ImageHub)

2. Rename it to boot.img than flash it via [fastbootd](https://github.com/C-F0x/yet-another-gts10pwifi-tutorial/releases/tag/fastbootD_only). Or you can flash it in Odin, remember to compress it to boot.tar at first.

3. Boot, than use KernelSU or its fork to patch the init_boot.img, you can get it from AP.tar.md5 or the [releases](https://github.com/C-F0x/yet-another-gts10pwifi-tutorial/releases/tag/ImageHub).

4. Flash patched_init_boot.img again via fastbootd or odin.

---

# Method B (Haven't been tried)

1. Get YuzakiKokuban AK3.zip From [Original Release](https://github.com/YuzakiKokuban/android_kernel_samsung_mt6989_TabS10/releases)

2. Boot from Proper [KernelSU General Image](https://github.com/tiann/KernelSU/releases). 

3. Flash your Official Boot.img with [Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher/releases)

4. Flash your perfered AK3.zip in [Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher/releases), than reboot

5. Use KernelSU or its fork.

---

# Q&A
Q: Why not use Magisk or Magisk Alpha?

A: I don't like Patch the Whole AP.tar Once Device Update.


Q: Why not use the original YuzakiKokuban image?

A: YuzakiKokuban/android_kernel_samsung_mt6989_TabS10#1 


Q: Can I use AK3.zip upon KSU General Image.

A: You Tell Me


Q: Can I use APatch on this device?

A: edit the boot config on ur own.


Q: Why not use method B

A: I don't want to lose my bluetooth savedata.


Q: Will it lose userdata

A: You will lose your userdata only if u moddified vbmeta.img, it's not necessary on OneUI 6.1/7. 

But Unforntunately, it seems to be necessary on OneUI 8 cuz u need to use oneui7 bl with oneui8 ap cp csc. Sadly😞

Once system booted with a different vbmeta, userdata got broken so that u need to factoryformat. e.g dont modify vbmeta after sys update


Q: Still Any Questions

A: Submit an issue.
