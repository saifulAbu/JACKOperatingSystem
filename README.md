# JACKOperatingSystem
An operating system created from scratch using JACK programming language. The author wrote the programming language JACK and the target architecture HACK from scratch following the nand2tetris project[1].

## Capabilities
* Efficient mathematical operations implementation for division, multiplication and square-root as the target HACK[3] architecture does not handle this complex operations.
* Screen operations such as draw pixel, line, rectangle, and circles.
* BitMap implementation for character output.
* Keyboard operation to read from memory-mapped location.
* Dynamic memory management for memory allocation and de-allocation. Capability to read/write a certain location of RAM.
* String implementation with allowed operations such as length, charAt, setCharAt, appendChar, toInt, setInt etc.
* Array implementation with new and dispose operations.
* System class implementation with operations such as halt, error and wait.


## Instructions to Build and Run
* `git clone https://github.com/saifulAbu/JACKOperatingSystem`. This project comes with a JACK compiler, and a JACK virtual emulator [2].
* Update your ~/.bashrc with the following two lines
```
alias jackc='sh /path/to/JACKOperatingSystem/tools/JackCompiler.sh'
alias jackvm='sh /path/to/Bucket-List/9.os/JACKOperatingSystem/tools/VMEmulator.sh'
```
Then run `source ~/.bashrc`

* Write a application program using the JACK OS API specied in [0]. An example application program is provided in the Pong directory.
* Copy codes of the OS into the Pong directory.
* cd to Pong directory. run the command 
jackc
jackvm
* As the virual machine emulator opens, load the Pong directory. Choose no animation, hit the run button.

Here is an example of some graphics output created using the OS
[A House](https://github.com/saifulAbu/JACKOperatingSystem/blob/master/drawa_screen.png)
[Pong Game](https://github.com/saifulAbu/JACKOperatingSystem/blob/master/first_game_play.png)


References
0. https://docs.wixstatic.com/ugd/44046b_695a82ff2d974bd5b3b2642aa42ac4e8.pdf
1. https://www.nand2tetris.org
2. https://github.com/saifulAbu/JACKOperatingSystem/tree/master/tools
3. https://github.com/saifulAbu/HACK-Architecture
