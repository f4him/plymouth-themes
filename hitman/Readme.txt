Hitman Plymouth Boot Splash theme for Linux by f4him.
==============================================
Installation Instructions:
1.Extract the downloaded file.
2.Open terminal type "sudo nautilus" (without the quotes) & enter your password. If you use Nemo or Caja or Linux Mint then use the "Open as Root"/"Open as Administrator" option.
3.Navigate to the extracted folder & copy the "Hitman" folder to /lib/plymouth/themes/ & paste the "Hitman" folder there.
4.Type the following commands in the terminal to install the theme

 sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/Hitman/hitman.plymouth 100

This will install the theme, to select it as the default theme type

 sudo update-alternatives --config default.plymouth

This gives you a list of installed themes, select the number corresponding to the Hitman theme & press enter.

Now to save your changes type,

 sudo update-initramfs -u

That's it! Reboot your system & it should boot with the new Hitman Boot Splash Screen!


f4him
shahriarfahim23@gmail.com
