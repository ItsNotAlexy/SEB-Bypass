# SEB-Bypass
A way to bypass SEB (Safe Exam Browser) with VMWare


# Bypass Patch v3.0.5
Creation by [AlexyyDev](https://github.com/ItsNotAlexy) made for Educational Purposes and not for malicious intent.


# Bypassing SEB
- Then install [VMWare](https://www.vmware.com/products/workstation-player.html)
- After installing, Download a Windows ISO:
    - [Windows 11](https://www.microsoft.com/software-download/windows11)
    - [Windows 10](https://www.microsoft.com/en-us/software-download/windows10ISO)
- After that create a new virtual machine using VMware and the ISO file downloaded
- Then in the virtual machine, download [Safe Exam Browser](https://safeexambrowser.org/download_en.html)
- You should be able to have a "SEB Configuration Tool" application upon downloading SEB.
- Open the "SEB Configuration Tool" and press "Security"
- Use this configuration:
    ![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/b7b12295-b4c9-432e-a271-096d4b2675f7)
- After that, Go to the "Config File" tab and click the "Save Settings"
![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/a9cf6c15-67e2-43ea-9a67-4a4b33ddf21e)
- Close the SEB Configuration Tool and launch SEB on your virtual machine!

# Bypass Custom Configuration
In a case where your school makes you download a "SEB Configuration File" you can follow these steps:
- Find the SEB Configuration File (Can be identified with the SEB Logo with a black/grey colour scheme)
- Then right click on the file and click "Open With" and choose notepad.
- Find these values:
  - "allowedDisplaysIgnoreFailure" -> From "false" to "true"
  <br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/6ecd3030-ff8d-472f-9d94-af71db9c2c95)

  - "allowDisplayMirroring" -> From "false" to "true"
  <br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/113bca36-e8b9-4658-bb28-2bab9c832db5)

  - "allowVirtualMachine" -> From "false" to "true"
  <br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/81612324-edb9-46a5-a6e3-cb0d521ce0b0)

- Save the file and launch SEB with double clicking the configuration file

- Another way to bypass an SEB Configuration file is by downloading this premade bypass settings [here](https://github.com/ItsNotAlexy/SEB-Bypass/raw/main/SebBypassSettings.seb)
- Download the file and double click the file to automatically launch SEB with the VMWare bypass configurations
