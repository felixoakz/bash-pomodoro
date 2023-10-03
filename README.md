# **CLI Pomo Timer ⏰**

A simple command-line Pomodoro timer written in bash.

- Yes, we have smartwatches, cell phones, all of them with full fledged timer functions, but using the terminal is faster if you are already working and let's face it, it's a lot cooler too! :)

[![asciicast](https://asciinema.org/a/gDvmCzLlyblUua17gOyxn3Jvt.svg)](https://asciinema.org/a/gDvmCzLlyblUua17gOyxn3Jvt)

## **Usage**

1. Make the script executable by running **chmod +x pomodoro.sh**
2. Execute the script by running **./pomodoro.sh 'argument'** where argument is an integer representing the duration of the Pomodoro in minutes.
3. The script will start a timer and display a progress bar with percentage and pipes.
4. Once the timer is finished, the script will display a system notification and play the mp3 music.

## **Example**

```
$ ./pomodoro.sh 25
```
This will start a 25-minute Pomodoro timer.


## **Limitations**

- This script has only been tested on Linux systems.
- Notifications and sound alerts may not work on other operating systems.
- This script uses the command notify-send to display notifications, which may not be present on all systems.
- This script uses the command paplay to play sound alerts, which may not be present on all systems.

## TODO
- [x] Support for BSD
- [] Support for Mac
- [] Add Unicode Emoji if terminal supports
- [] Add the option to choose between different sounds to be reproduced at the timer completion
- [] Create an alias that takes a number argument to run the pomo timer from any directory

## **Authors**

- @felixoakz
- @PseudoClone

## **Contributions**
Feel free to contribute to this project by submitting a pull request or opening an issue. All contributions, no matter how small, are welcome!

## **License**

This project is licensed under the MIT License - see the LICENSE file for details.
