# SETUP
All required dependencies are included in requirements.txt
1. Dependencies <br />
run following command to install them:
```shell
sudo pip install -r requirements.txt
```

If there is error saying package SIX cannot be uninstalled, use following command instead:
```shell
sudo pip install --ignore-installed six -r requirements.txt
```
Since I had problem with package six version, therefore I have included six-1.13.0. cd into this folder and run 
```shell
sudo python setup.py install
``` 
should install the newest version of six, then you can rerun command above, should work.


