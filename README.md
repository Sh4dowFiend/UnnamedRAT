UnnamedRAT is a remote administration tool that works inside local networks.

1. Compile UnnamedRAT.py with PyInstaller(or something else)
2. Download and run it on PC you want to have remote access to. The program will add itself into autolaunch and open 16865 port, waiting for command client to connect.
3. After that, you will be able to connect to and administrate this PC in any time from any device within a local network, using UnnamedRAT-client.py
4. To do this, just run the python script and enter the password, pre-configured in UnnamedRAT.py(you can change password and LAN port in the source code)
5. Congratulations! Now first device will run any CMD commands you type in RAT console.

Please use this for lawful purposes only.
Let me remind you that in some cases the use of such software may be considered malicious.
The developer does not bear any responsibility for your actions.

Also, I've uploaded a version of server script(UnnamedRAT_default_precompiled.exe) compiled using PyInstaller.
