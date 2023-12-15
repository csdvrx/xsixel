# Xsixel in pictures

This is Xsixel running xeyes inside wezterm

![Xsixel running xeyes inside wezterm](screenshots/xsixel-in-wezterm.png)

# Using the release

Extract xorg_x86-64_release1.tgz to /xorg

Start with: `/xorg/startx.sh` which will tell you how to run apps like `DISPLAY=:1 xeyes`

# Compiling

Use src/xserver-SIXEL/build-xsixel.sh to build from sources into /xorg

# What's coming next

Make cosmopolitan binaries for a multiplatform Xsixel running inside multiplatforms terminals like Alacritty

# Credits

[Hayaki Saito](https://github.com/saitoha) did most of the work [on xserver-SIXEL in 2014](https://github.com/saitoha/xserver-SIXEL) which was based on [@pelya's Xsdl kdrive server](https://github.com/pelya/xserver-xsdl)
