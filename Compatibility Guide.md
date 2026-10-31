# 🧩 Ultra-HD Patch Compatibility Guide

This guide is for players using **Conquest Reborn, ArdenWoW, Grimfall, or other custom WoW 3.3.5a servers that detect modified clients**.

You will encounter more bugs. Limitations of a 32bit client. 

## 📁 Step 1 – Rename HD Patches

Navigate to your client's `Data` folder and rename the following patches:

- `patch-ZZB.MPQ` → `patch-AAB.MPQ`
- `patch-ZZE.MPQ` → `patch-AAE.MPQ`
- `Delete patch-ZZD`

All other patches can remain unchanged.

Launch using your default x32 client

---

## 🌄 Step 2 – Install 32-Bit LuxVelum

Since you'll be using your server's original 32-bit client, you'll need the **32-bit Version DLL of LuxVelum**.

**🔗 [Download LuxVelum 32-Bit](https://github.com/Raz0r1337/LuxVelum/releases/tag/build-1)**

Download the 32-bit Version DLL release and install it into your WoW client folder.

**AMD GPU Users:** Open `Luxvelum.ini` and set `multisampling=0`

---

## 🎨 Step 3 – Additional Enhancements

You can continue using the included ReShade preset, Config.wtf, and additional add-ons. Simply move d3d9.dll from the included x64 folder to your game's root folder.

**⚙️ Config.wtf:** Remember to adjust your resolution and refresh rate to match your monitor.

---

## ⚠️ Compatibility Disclaimer

Different servers may use different patch load orders, potentially causing graphical bugs or other issues.

**These modifications are provided as-is. I will not provide support for compatibility issues on other servers.**
