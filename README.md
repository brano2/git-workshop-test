# Git Exercise

1. Each person in the pair, `git clone` this repo
2. Decide, who is Person A and who is Person B
3. Tasks will be appearing below. After you complete one, another one appears. There is 10 in total.
4. First 6 tasks are always only for one person (it alternates between A and B)
5. In the remaining tasks, you will work in parallel and might even need to resolve some conflicts.

## Tasks
1. Person A - `pod.cpp` - Name your pod
    * Open `pod.cpp` file and locate TASK 1
    * Type the name for your pod inside the double-quotes (you should discuss the choice of the name with your teammate)
2. Person B - `pod.cpp` - Choose max speed
    * Open `pod.cpp` file and locate TASK 2
    * Tell us what the max speed of your pod is by replacing the 0 in the code with a real number

|Task # | Person A                                                | Person B                                                |
|:------|---------------------------------------------------------|---------------------------------------------------------|
|1      | Name your pod - edit `pod.cpp`                          |     |
|2      |                                                         |  Max speed - edit `pod.cpp`  |
| 3     | Pressure vessel temperature - edit `pod.h` and `pod.cpp` | |
| 4     |                                                         | Pressure vessel pressure - edit `pod.h` and `pod.cpp` |
| 5 | Create `main.cpp` and update `Makefile`                     | |
| 6 |                                                             | BMS - create `bms.cpp` and `bms.h` and update `Makefile` |
| 7 | Accelerometer error - edit `accelerometer.cpp`<br>`git pull -- rebase`| Edit `navigation.cpp` - adding accelerometers |
| 8 | Edit  `navigation.cpp` - get velocity                 | Edit `navigation.cpp` - get position<br>`git pull -- rebase` |
| 9 | Edit `bms.h` and `bms.cpp` - get voltage<br>`git pull -- rebase` & resolve conflicts | Edit `bms.h` and `bms.cpp` - get current |
| 10 | Integrate navigation to pod - edit `pod.h` and `Makefile` | Integrate BMS to pod - edit `pod.h`, `pod.cpp` and `Makefile`<br>`git pull -- rebase` & resolve conflicts |
