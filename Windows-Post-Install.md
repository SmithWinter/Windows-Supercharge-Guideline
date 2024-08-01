# 📀 Windows Post-install

## 💻 Turn off automatic Windows Update

One day, Windows pop-up some annoyed notifications like this 🤬

![Windows Update 1](./Images/windows-update-1.jpg)

or this 🤬 when you want to shutdown.

![Windows Update 2](./Images/windows-update-2.jpg)

Annoyed 😡? Well, there are some tools to turn off automatic and monitor Windows Update 😍.

Ah ❗, I would recommend you to update driver for peripheral devices such as WiFi/Bluetooth/LAN adapters 📶 before tweaking Windows Update.

* ### 💾 [Windows Update Blocker by Sordum](https://www.sordum.org/9470/windows-update-blocker-v1-8/)

🔗 *Alternative*: [Internet Archive](https://archive.org/details/windows-update-blocker-1.8-by-sordum)

✅ *VirusTotal*: [Link](https://www.virustotal.com/gui/file/a094805ad7530fba95ca68fe8dd061ff2c36447a4dca660229cd4a3602c3371d)

This is a simple Windows update blocker, in my opinion i would not recommend using it because of no manual update monitoring.

* ### 💾 [Windows Update Mini Tool 22.04.2022](https://www.majorgeeks.com/files/details/windows_update_minitool.html)

🔗 *Alternative*: [Internet Archive](https://archive.org/details/windows-update-mini-tool-22.04.2022)

✅ *VirusTotal*: [Link](https://www.virustotal.com/gui/file/1bd6fbd5e65d9e88f47cb43f60e0e694b702513fde26afb18a0d1396bcb7307d)

Currently I'm using it, it can disable automatic update and monitoring Windows updates manually, reliable than the first option.

## 💽 Intel/AMD/NVDIA Driver

![intel-amd-nvdia](/Images/intel-amd-nvdia.jpg)

Installing Intel, AMD, or NVIDIA drivers through Windows Update can be unreliable and may lead to system instability. For optimal performance and stability, it's recommended to download and install the latest drivers directly from the manufacturer's website.

Below is driver assistant tools for Intel / AMD / NVIDIA.

* 🖥 ***Intel***: [Download Center](https://www.intel.com/content/www/us/en/download-center/home.html)

* 🖥 ***AMD***: [Download Center](https://www.amd.com/en/support/download/drivers.html)

* 🖥 ***NVDIA***: [Download Center](https://www.nvidia.com/download/index.aspx)

The most stable version can vary depending on the specific system. It's recommended to research and find the optimal version for your particular hardware and software configuration.

### 🤔 *What to do if I want to downgrade driver version?*

Simple, use this, mostly recommended by many tech communities

* ### 💾 [Display Driver Uninstaller of WagnardSoft](https://www.wagnardsoft.com/forums/viewtopic.php?t=4992)

📄 Getting Started: [Document](https://www.wagnardsoft.com/content/How-use-Display-Driver-Uninstaller-DDU-Guide-Tutorial)

📺 Prefer a video tutorial? Watch this [video](https://www.youtube.com/watch?v=xn8z39tiEL0)

Once the old driver is removed, install the desired driver version.

Before restarting your computer to normal mode, make sure to `DISABLE AUTOMATIC WINDOWS UPDATE` to prevent the driver from being reinstalled.

## 🖥 Turn off Fast Startup Windows 10/11

![Fast boot meme](./Images/fast-startup-meme.jpg)

### 🤔 *Should I turn off Fast Startup ?*

Before SSDs became widely available, HDDs were the primary storage option for computers, its reading speed were significantly slower compared to today's standards. This slower speed impacted overall system performance, especially when loading applications or large files.

Fast Startup is generally not recommended for SSDs due to several reasons:

* **Diminished performance benefits**: SSDs are significantly faster than HDDs, so the boot time improvements offered by Fast Startup are minimal.

* **Potential for system instability**: Fast Startup doesn't perform a full shutdown, which can lead to incomplete updates, corrupted files, or other system issues.

* **Unnecessary wear on the SSD**: While the impact is debated, some argue that Fast Startup's write operations to the SSD during hibernation can slightly shorten its lifespan.

### 🤔 *What distinguish between Fast Startup and Hibernation?*

📝 Explanation from Microsoft: [Document](https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/distinguishing-fast-startup-from-wake-from-hibernation)

### 🤔 *How do I turn off Fast Startup ?*

📄 Documentation: [Link](https://www.windowscentral.com/how-disable-windows-10-fast-startup)

📺 Prefer a video tutorial? Watch this [video](https://www.youtube.com/watch?v=L049J2yxY_w)
