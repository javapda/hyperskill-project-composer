# hyperskill-topics-for-project-compose | [readme](../readme.md)

* [exit codes](https://hyperskill.org/learn/step/30933)

## Notes

### [exit codes](https://hyperskill.org/learn/step/30933)
* [Exit codes](https://hyperskill.org/learn/step/30933) in operatings
systems refer to numerical values that a program or command
returns upon completion. 
* Provides success or failure of the command.
* Enables users and system administrators to determine the 
outcome of the executed task.
* An exit code of `0` indicates command ran successfully (without error).
* A command generating (returning) a non-zero exit code with it
encounters an error or fails to execute properly. They exact non-zero code may vary depending upon what its cause was. For example, a `1` may be a general error and other non-zero numbers
may be more specific.

#### Common Unix-based system exit codes
* `0` - indciates the successful termination of a command or program without errors
* `1` - generic `catch-all` error code. It is often used to indicate that a command or program encountered an unspecified error condition
* `2` - typically indicates incorrect usage or invalid arguments passed to a command or script
* `126` - suggests that the execution of invoked command or script was unsuccessful, usually due to insufficient permissions
* `127` - signifies that the command or script could not be found or executed
* `130` - commonly used to indicate the termination of a program by the user, typically by pressing _**Ctrl+C**_ to send a `SIGINT` signal

#### codes defined:
* List of Linux exit status codes : https://www.ditig.com/publications/linux-exit-status-codes
* What are Exit Codes in Linux? : https://itsfoss.com/linux-exit-codes/
* [How to use exit code to read from terminal, from script and with logical operators](https://www.geeksforgeeks.org/how-to-use-exit-code-to-read-from-terminal-from-script-and-with-logical-operators/)
