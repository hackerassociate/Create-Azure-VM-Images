# Create-Azure-VM-Images

### Create Azure VM Images 

```
First we need to run Sysprep command  in Windows 10

Press Windows logo key + X at the same time. Select Command Prompt (Admin) from the menu.

Type cd \Windows\System32\Sysprep and then press Enter.

Type sysprep and then press Enter to open Sysprep GUI mode.

Choose Enter System Out-of-Box Experience (OOBE) and tick the Generalize checkbox and then shutdown.


```


# Troubleshooting 

### if issue persist then do following


```

To turn BitLocker off, launch Command Prompt as an administrator from the Start Menu, type the following commands, and hit Enter.

manage-bde -status
Disable-Bitlocker –MountPoint ‘C:’

This will turn Bitlocker off.

Now, try running Sysprep again and see if it fixes the issue.


```


