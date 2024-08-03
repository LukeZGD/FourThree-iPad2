# FourThree-iPad2
FourThree Utility - Dualboot iPad 2 devices to iOS 4.3.x

FourThree is based on [4tify-iPad2](https://github.com/Zurac-Apps/4tify-iPad2), the first project that achieved iPad 2 dualboots with a utility.

FourThree supports dualbooting to any iOS 4.3.x version on any iPad 2, as long as that iPad 2 supported 4.3.x. iPad2,4 devices are not supported.

FourThree is a utility within [Legacy iOS Kit](https://github.com/LukeZGD/Legacy-iOS-Kit) - This is a 3 step process for the device. Follow through the steps to successfully set up a dualboot.

To get started, download Legacy iOS Kit, set it up, and select "FourThree Utility" in the main menu.

## Step 1: Restore

- If you have used Legacy iOS Kit to downgrade before, you should be familiar with this process. Just jailbreak your device, install OpenSSH in Cydia, and select the "Step 1: Restore" option in FourThree Utility. Select iOS 6.1.3 IPSW for the Target IPSW, and the iOS 4.3.x IPSW for the Base IPSW. After the 6.1.3 restore, go through the setup process. By the end of this step, your device should be restored and jailbroken in iOS 6.1.3.
- Note: After the restore, Do not open Cydia until after all steps have been completed.

## Step 2: Partition

- In this step, the device partitions will be modified to make room for the second OS. Select the "Step 2: Partition" option in FourThree Utility and it will guide you through running the SSH ramdisk required for this step.

## Step 3: OS Install

- In this step, everything will be set up and iOS 4.3.x will be installed on the device. Select the "Step 3: OS Install" option in FourThree Utility and it will go through the process of finalizing the setup. By the end of this step, the dualboot setup should be complete and the "FourThree" app is visible on the home screen.

## Activation

- No need to worry about activation issues on iOS 4.3.x, the install will be activated.
