# **CLI Pomodoro Timer ⏰**

A simple command-line Pomodoro timer written in bash.

- Yes, we have a watch, cell phone, all with timer functions, but using the terminal is faster if you are already working and let's face it, it's cooler too! :)


## **Usage**

1. Make the script executable by running **chmod +x pomodoro.sh**
2. Execute the script by running **./pomodoro.sh 'argument'** where argument is an integer representing the duration of the Pomodoro in minutes.
3. The script will start a timer and display a progress bar with percentage and pipes.
4. Once the timer is finished, the script will display a system notification and play an alert sound.

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

## **Authors**

- @felixoakz
- Google
- ChatGPT (OpenAI)

If anyone wants to contribute, feel free to do so!

## **License**

This project is licensed under the MIT License - see the LICENSE file for details.
