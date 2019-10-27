# CanaryServer
Fake SMB and SAMR data


Backup and replace “impacket/impacket/smbserver.py” with our modified version.

Run “pip install .” in impacket/ directory.

Run smbserver.py -smb2support "" . in your CanaryServer path.
