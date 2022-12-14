# C - Stacks, Queues - LIFO, FIFO
This repsitory contains the files to the ALX project: 0x19. C - Stacks, Queues - LIFO, FIFO. The files were compiled on an Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c89. The [betty-style linter](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl "This takes you to the betty-doc") linter was used.
The files will create an interpreter for Monty ByteCodes files.
## The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it.
#### Monty byte code files
* It is considered best practice that files containing Monty byte codes usually have the .m extension.
* There is not more than one instruction per line.
* There can be any number of spaces before or after the opcode and its argument.
* Monty byte code files can contain blank lines (empty or made of spaces only, and any additional text after the opcode or its required argument is not taken into account.
## Usage:
```
./monty file
```
Where file is the path to the file containing Monty byte code.
