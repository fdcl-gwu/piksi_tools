# Settings
Saving configuration to a file:
```
python2 -m piksi_tools.settings -p /dev/ttyS0 read_to_file config.ini
```

Uploading settings on a file to the receiver
```
python2 -m piksi_tools.settings -p /dev/ttyS0 write_from_file config.ini
```

# Dependencies
```
pip install sbp
sudo pip install construct==2.9.33
sudo pip install requests-futures==0.9.5
```
