##### setup kivy linux
```
sudo apt-get install cython
```

python2.x only so far. Download buildozer and install
```
git clone https://github.com/kivy/buildozer
cd buildozer
sudo python setup.py install
```

Go into app directory
```
buildozer init
buildozer android debug deploy run
```
If its the first time...
Last cmd can take a long time to install SDK, NDK, etc. -verbose to buildozer to view output


##### Testing APK file on PC
download 
http://kivy.org/#download
and execute
```
sudo python setup.py install
python main.py
```
