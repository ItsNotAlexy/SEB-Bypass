<div align="center">
    <img style="width: 350px;height:350px;" src="https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/5d66e32b-79fa-4890-98b8-c6c4d18bfd52">
</div>

# SEB-Bypass
A way to bypass SEB (Safe Exam Browser) with VMWare.


# Bypass Patch v3.0.5
Creation by [AlexyyDev](https://github.com/ItsNotAlexy) made for Educational Purposes and not for malicious intent.


# Bypassing SEB
- Then install [VMWare](https://www.vmware.com/products/workstation-player.html).
- After installing, Download a Windows ISO:
    - [Windows 11](https://www.microsoft.com/software-download/windows11)
    - [Windows 10](https://www.microsoft.com/en-us/software-download/windows10ISO)
- After that create a new virtual machine using VMware and the ISO file downloaded.
- Then in the virtual machine, download [Safe Exam Browser](https://safeexambrowser.org/download_en.html).
- You should be able to have a "SEB Configuration Tool" application upon downloading SEB.
- Open the "SEB Configuration Tool" and press "Security".
- Use this configuration:
    <br><br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/b7b12295-b4c9-432e-a271-096d4b2675f7)
  <br><br>
- After that, Go to the "Config File" tab and click the "Save Settings".
    <br><br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/a9cf6c15-67e2-43ea-9a67-4a4b33ddf21e)
- Close the SEB Configuration Tool and launch SEB on your virtual machine!


# Bypass Custom Configuration
In a case where your school makes you download a "SEB Configuration File" you can follow these steps:
- Find the SEB Configuration File (Can be identified with the SEB Logo with a black/grey colour scheme).
- Then right click on the file and click "Open With" and choose notepad.
- Find these values:
  - "allowedDisplaysIgnoreFailure" -> From "false" to "true".
  <br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/6ecd3030-ff8d-472f-9d94-af71db9c2c95)

  - "allowDisplayMirroring" -> From "false" to "true".
  <br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/113bca36-e8b9-4658-bb28-2bab9c832db5)

  - "allowVirtualMachine" -> From "false" to "true".
  <br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/81612324-edb9-46a5-a6e3-cb0d521ce0b0)

- Save the file and launch SEB with double clicking the configuration file.

## Custom Configuration Alternative
- Another way to bypass an SEB Configuration file is by downloading this premade bypass settings [here](https://github.com/ItsNotAlexy/SEB-Bypass/raw/main/SebBypassSettings.seb).
- Download the file and then right click the file and then press "Open With" and click Notepad.
- Hit `CTRL + F` and search "StartURL" and change `www.google.com` into the URL set for your exam.
  <br><br>![image](https://github.com/ItsNotAlexy/SEB-Bypass/assets/101402577/de1fb146-038b-4cfe-ba9a-c7c858a00143)
- Then hit `CTRL + S` to save it and launch SEB with double clicking the configuration file.


# LICENSE
This Repository is under the MIT License. &copy;
