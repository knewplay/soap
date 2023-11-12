# Features

- Based PROS V5 (3.8.0)
- C language only in use, no others
- Self-described style code, easy to learn and change
- Ready to use in VEX competition, various useful and powerful library

# How to use

Firstly, you have to create a PROS project in your local computer. Visual Studio Code and PROS Plugin are really 

Download last release in here and unzip it.

Copy the header files and c files to the same folder in your project. 

```
# Linux commands that demonstreate what files you should copy
cp include/config.h $YOUR_PROS_PROJ/include/config.h
cp include/starter-kit $YOUR_PROS_PROJ/include/start-kit
cp src/start-kit $YOUR_PROS_PROJ/src/start-kit
```

Write `include` code the `include/main.h` in your project.

```
#include "config.h"
#include "start-kit/automation_selection.h"
#include "start-kit/chassis_track.h"
// include what you need from start-kit here
```

Now, you can just use, learn, and change these various code in your project.
