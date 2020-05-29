# KafuuService
osu!Kafuu Local Service (You can think of it as a special switcher) made by Python!!

What is special? In addition to providing the function of a general switcher, it can also provide some local API interfaces for players on the osu! Kafuu website ... I mean, anti-cheating, and double verification of login.

## For example, you can get the computer's CPU id through:

```
127.0.0.1:13377/api/get_sys_info/cpu
```
or this for all:

```
127.0.0.1:13377/api/get_sys_info/all 
```

## and more? sure.

![screenshot1](https://github.com/kafuu-osu/KafuuService/blob/master/screenshot1.png)
![screenshot2](https://github.com/kafuu-osu/KafuuService/blob/master/screenshot2.png)


## install
```
pip install -r requirements.txt
```

## build pyd
```
./build_pyd64.bat
```

## build exe
```
./build_exe.bat
```

Then you can choose to digitally sign the program or not



For some reasons, some future changes may not be open source
But now it is completely open source
