 Python 3.6 is the default version that comes with Ubuntu But the latest version is Python 3.7.3.
 
```
 python3 -V
```

Step 1: Install latest python3.7 version
```
sudo apt-get install python3.7
```
Step 2: Add Python 3.6 & Python 3.7 to update-alternatives
```
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.7 2
```

Step 3: Update Python 3 to point to Python 3.7
```
sudo update-alternatives --config python3
```


