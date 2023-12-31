This is an iFruit boot theme, imspired by GTA5 and MacOS.

![Alt text](ifruit.png)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="fruit.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="fruit.png">
</picture>

-------------------------------------------------------------------
Installation
-------------------------------------------------------------------

Assuming the unzipped ifruit theme folder is located in your download directory.
Copy the finished theme to /usr/share/plymouth/themes:

`sudo cp -r ~/Downloads/ifruit-main/ifruit /usr/share/plymouth/themes`

After copying, get a list of the installed themes with the following command:

`plymouth-set-default-theme --list`

Set it to iFruit theme:

`sudo plymouth-set-default-theme ifruit -R`
