# PItracker

PItracker is designed to detect the PendingIntent vulnerability on Android. The technical details of PItracker can be found in the following paper. Please cite this paper if you use our tool.

Chennan Zhang, Shuang Li, Wenrui Diao, and Shanqing Guo. PITracker: Detecting Android PendingIntent Vulnerabilities through Intent Flow Analysis. The 15th ACM Conference on Security and Privacy in Wireless and Mobile Networks (WiSec'22), San Antonio, Texas, USA. May 16-19, 2022.

-------------------

python version: 3.7.4

Add requirement:numpy  pydot
pip3 install numpy
pip3 install pydot

example:

analyze an apk:
```
python main.py -a F:\apks\a.apk -o F:\apks\out
```

analyze a directory:
```
python main.py -d F:\apks\ -o F:\apks\out
```
