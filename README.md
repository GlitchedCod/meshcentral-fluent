# This is a WiP.
# MeshCentral ~~Material~~ Fluent UI:
his repository contains a custom UI for MeshCentral based on Material UI, originally created by [ijustw0rkhere](https://github.com/ijustw0rkhere) and also forked from [DaanSelen](https://github.com/DaanSelen).

If you encounter issues or unsual choice, please feel free to submit an issue, I will look at it as soon as possible!

# Installation guide (of this version):

Clone this repository (if you have git installed, if not: download it here: [Git Download](https://git-scm.com/downloads))<br>

```shell
git clone https://github.com/DaanSelen/meshcentral-material
```
<br>

after that move or copy the folder src/meshcentral-web (or parts of it IF YOU KNOW WHAT YOU ARE DOING) into your installed MeshCentral root folder, where `meshcentral-files` and `meshcentral-data` is located.

```shell
(sudo) mv ./meshcentral-material/src/meshcentral-web /opt/meshcentral
```

Once that's done, restart the MeshCentral server using the guide instructed service file. Using Systemd this is done like this:<br>

```shell
sudo systemctl restart meshcentral.service
```
<br>

After that browse to your MeshCentral server IP or domain.<br>

# Image showcase: (WARNING: Not contractual !)

![image](https://github.com/user-attachments/assets/85a6d5dd-41da-4e3a-9357-cf76a3e62526)

# Known issues:

None right now.

# Thank you for using!
