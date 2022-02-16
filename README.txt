################### Media_Player ###################

-Must: installing VLC MediaPlayer x64 for 64bit system

-Python 3.7.4

-install python VLC package

conda install -c postelrich python-vlc

or

pip install python-vlc

-Making standalone file command (in conda):
pyinstaller --onefile -w MediaPlayer_OrDaniel.py
the stand alone file still need the VLC 64 bit to be installed
