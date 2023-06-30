# Shell Processes and signals -  0x05. Processes and signals

## About this project:

In this project i have learnt and practice

* What is a PID
* What is a process
* How to find a process’ PID
* How to kill a process
* What is a signal
* What are the 2 signals that cannot be ignored

### Task file description:

1. [0-what-is-my-pid](0-what-is-my-pid) - A Bash script that displays its own PID.
2. [1-list_your_processes](1-list_your_processes) - A  Bash script that displays a list of currently running processes.
  * Must show all processes, for all users, including those which might not have a TTY
  * Display in a user-oriented format
  * Show process hierarchy
3. [2-show_your_bash_pid](2-show_your_bash_pid) - Bash script that displays lines containing the bash keyword based on the script `1-list_your_processes` that displays the PID along with the process name of processes who name contains the word bash.
4. [3-show_your_bash_pid_made_easy](3-show_your_bash_pid_made_easy) - Bash script that displays the PID
`To infinity and beyond` indefinitely with a `sleep 2` in between each iteration.
5. [5-kill_me_now](5-kill_me_now) Bash script that kills the [4-to_infinity_and_beyond](4-to_infinity_and_beyond) process using kill.
6. [6-kill_me_now_made_easy](6-kill_me_now_made_easy) - Bash script that kills the [4-to_infinity_and_beyond](4-to_infinity_and_beyond) process using `pkill.`
7. [7-highlander](7-highlander) - Bash script that displays `To infinity and beyond` indefinitely with a `sleep 2`  in between each iteration.
  * Displays `I am invincible!!!` upon receiving a `SIGTERM` signal.
8. [8-beheaded_process](8-beheaded_process) - Bash script that kills the process [7-highlander.]

