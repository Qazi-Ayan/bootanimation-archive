# bootanimation-archive
Collection of various boot animations from different sources

# Android Boot Animation Archive

A curated collection of verified, 0%-compression raw `bootanimation.zip` files for custom ROMs (crDroid, LineageOS) and rooted Android devices using **BootStudio** or **Magisk**.

---

##  Downloads & Previews

All animations are verified and hosted directly in our [Latest Release (v1.0)](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest).

| Animation | Style / Type | Download Link |
| :--- | :--- | :--- |
| **ASUS ROG** | Gaming / Cyber | [Download ROG.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |
| **Sony Xperia** | Stock OEM | [Download Xperia.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |
| **Nokia** | Retro Classic | [Download Nokia.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |
| **Windows** | Retro OS | [Download Windows.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |
| **Dynamic OS** | Minimal / Clean | [Download Dynamic.os.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |
| **Android X Google**| Stock Mashup | [Download Android.X.Google.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |
| **Apple iOS** | Concept | [Download AppleiOS.zip](https://github.com/Qazi-Ayan/bootanimation-archive/releases/latest) |

---

## How to Apply?

BootStudio (Recommended)
1. Install [BootStudio](https://github.com/gauthier1024/BootStudio).
2. Download any `.zip` from the table above or the Releases tab.
3. Open **BootStudio** ➔ tap **`+` (Import)** ➔ select the downloaded `.zip`.
4. Preview the animation and tap **Apply**.

### Method 2: Manual Magisk Module
Place the raw `bootanimation.zip` into your Magisk module structure at:
* `/data/adb/modules/<module_id>/system/product/media/bootanimation.zip`
* Set permissions to `644` (`chmod 644`) and reboot.

---

*Note: All boot animations in this collection are community archives and ports from original OEMs and creators.*