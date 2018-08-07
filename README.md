# JACKOperatingSystem
An operating system created from scratch using JACK programming language. The author wrote the programming language JACK and the target architecture HACK from scratch.

Instructions to Build and Run
git clone this project. This project comes with a JACK compiler, and a JACK virtual emulator.
update your ~/.bashrc with the following two lines
alias jackc='sh /path/to/JACKOperatingSystem/tools/JackCompiler.sh'
alias jackvm='sh /path/to/Bucket-List/9.os/JACKOperatingSystem/tools/VMEmulator.sh'
source ~/.bashrc

0. Write a application program using the JACK OS API specied in [0]. An example application program is provided in the Pong directory.
1. Copy codes of the OS into the Pong directory.
2. cd to Pong directory. run the command 
jackc
jackvm
3. As the virual machine emulator opens, load the Pong directory. Choose no animation, hit the run button.





References
0. https://docs.wixstatic.com/ugd/44046b_695a82ff2d974bd5b3b2642aa42ac4e8.pdf

