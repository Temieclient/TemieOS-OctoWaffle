
*To Apply the Patch please read and follow this Step List:*

**WARNING: Before proceeding, please ensure that you are applying this patch to TemieOS versions 1-4 and on a version below 11.15.5.97. Applying the patch to incompatible versions may result in system instability or void warranty. Please note that this patch cannot be reverted due to the nature of the verifier process, which writes the patch to the system.**

1. Download Patch.pkc and Verifier.pkc on a secondary machine:

  *Obtain the Patch.pkc and Verifier.pkc files from a reliable source and save them on a secondary machine.
    Disable the TemieOS Machine:*

2. Safely shut down the TemieOS machine that requires the patch.
Unplug the Storage Device Containing the Main Partition:

*Disconnect the storage device (e.g., hard drive, SSD) that contains the main partition from the TemieOS machine.
Plug the Main Partition into the Secondary Computer:*

3. Connect the storage device with the main partition to the secondary computer.
Access the Main Directory on the Storage Device:

*Navigate to the main directory on the connected storage device, typically located at "(partition letter):main/."
Locate the System Directory:*

4. Find and access the System directory within the main directory structure. It is typically located at "(partition letter):main/System/."
***Delete Existing Patch Files (specific to TemieOS 3 or above):
If you are running TemieOS version 3 or below, delete the "patch505.pkc" file located in the "(partition letter):main/System/patches" directory.
If you are running a TemieOS version 4, remove all content present in the "(partition letter):main/System/patches" directory.
Copy Patch.pkc to the System Directory:***

5. Copy the downloaded Patch.pkc file to the "(partition letter):main/System/patches" directory on the storage device.
Save Verifier.pkc on a Secondary Mass Storage Device:

*Save the downloaded Verifier.pkc file on a separate mass storage device to use it later in the process.
Reconnect the Storage Device to the TemieOS Machine:*

6. Carefully reconnect the storage device, containing the main partition with the applied patch, back into the machine running TemieOS.
Run Verifier.pkc:

*Locate the Verifier.pkc file saved on the secondary mass storage device and execute it on the **TemieOS** machine.
Restart Your PC*

7. After running the Verifier.pkc, restart the **TemieOS** machine to ensure the patch is applied successfully.
Enjoy the Patch:

*Once the machine restarts, you can now enjoy the applied patch on your **TemieOS** system.
Please note that these steps should be followed with caution, adhering to the warning provided at the beginning.*
