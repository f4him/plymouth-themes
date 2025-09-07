# Hitman Plymouth Boot Splash Theme for Linux  
by **f4him**

---

## Installation Instructions  

1. Extract the downloaded file.  
2. Open a terminal and type:  

   ```bash
   sudo nautilus
   ```

	If you use Nemo, Caja, or Linux Mint, use Open as Root / Open as Administrator instead.



3. Navigate to the extracted folder and copy the Hitman folder to:
`/lib/plymouth/themes/`

4. Install the theme with:

```bash
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/Hitman/hitman.plymouth 100
```

5. To select it as the default theme, run:

`sudo update-alternatives --config default.plymouth`

Select the number corresponding to Hitman and press Enter.


6. Save your changes by typing:

`sudo update-initramfs -u`


7. Reboot your system, and you should see the Hitman Boot Splash Screen in action!
---

	🎩 "Walk in silence. Boot in style."
