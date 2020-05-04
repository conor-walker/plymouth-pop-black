# Plymouth - Black Pop!_OS startup.

I prefer my boot background to be fairly minimalistic, but still be slightly snazzy. This is a slight modification of the standard BGRT theme included in Pop's Plymouth install - the computers OEM logo will display in the centre, with a spinning icon below it (fancy!). The standard Ubuntu logo is replaced with a Pop!_OS logo for completeness, as the standard Spinner theme included in Pop still has the Ubuntu logo for some reason. (I actually run without it, so feel free to delete it if you want!)

To install, copy the pop folder to /usr/share/plymouth/themes. Run the following command in the terminal of your choice:

`sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/pop/pop.plymouth 110 && sudo update-alternatives --config default.plymouth`

Then select the Pop option that shows in the terminal. Then all you need to do is run:
`sudo update-alternatives --config default.plymouth`

This will change the theme to your fancy new Pop branded startup!
