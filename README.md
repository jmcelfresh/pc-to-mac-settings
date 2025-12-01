# Make a Mac feel more like a Windows PC
List of setting changes, using Mac OS Tahoe. 

## Display (external monitors)
(If you're using a MacBook or an iMac you don't need to worry about this)

Go to System Settings > Displays

### Refresh Rate
macOS may default refresh rate to the lowest setting, which will make the computer feel slow and choppy. Set the refresh rate to the highest setting supported by your monitor. 

### Resolution
macOS doesn't have UI scaling like Windows. If you're using an external monitor that isn't high resolution (less than 4k) you have to choose between slightly-too-small or an oversized UI.

Default resolution is the small version. There's also a HiDPI setting that will greatly increase the UI size. Depending on which you pick, you will be increasing or descreasing the UI scale of all other UI elements.

### App Scaling
You have to adjust the UI size for every app and some system functions individually.

**macOS**

Go to Accessibility > Display
- Text > Text size: Increase or decrease depending on your resolution. Setting each individual app in this menu seems to work better than the default. 
- Menu bar size: Increase on low res
- Pointer size: Increase on low res

Go to Desktop & Dock
- Size slider


**Terminal**

Settings... 
- Text > Font > Change...
- Window > Window Size > Columns / Rows (PowerShell has more default columns than the Mac terminal)


**Chrome**

- Three dots > Settings > Appearance > Page Zoom

I can't find a way to increase the Chrome UI size, only the web pages it displays. 


**VS Code**

- [Cmd] + [+] or [-] to scale the entire interface


## Mouse
System Settings > Mouse

- Turn off "Natural scrolling" to change the direction the page moves to match Windows. 
- Go to Advanced... > Pointer Acceleration and try it with the setting off. Windows has a similar setting that you may or may not have set up on your PC. Go with whatever feels best. 


## Keyboard

Remap the ctrl/cmd keys so you can copy/paste like on Windows. 

System Settings > Keyboard > Keyboard Shortcuts...

**Modifier Keys**

    Control Key    Command
    Option key     Option
    Command key    fn Function
    Function key   Control

If you want to get nuts, there are many other shortcuts to re-map, but the above were enough for me to do most things I'm used to. 


