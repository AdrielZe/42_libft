# Libft - 42 Project
<h3>📝 Table of Contents</h3>
- Introduction<br>
- Project Structure<br>
- Functions Implemented<br>
- How to Compile<br>
- Usage<br>
- Testing<br>
- License<br>

<h3>📌 Introduction </h3>
Libft is a foundational project at 42, where the goal is to recreate standard C library functions ("stdlib.h", "string.h", "ctype.h", etc.) 
to gain a deeper understanding of how they work behind the scenes. This project is aimed at developing essential skills such as pointer manipulation, 
dynamic memory allocation, and implementing basic algorithms. <br><br>

📁 Project Structure
The project is structured as follows:

libft/<br>
├── libft.h      # Header<br>
├── .c files      # Function implementations (.c)<br>
├── Makefile       # Library compilation<br>
└── README.md       # Project description<br>

<h3>🛠️ Functions Implemented</h3>
  
Part 1 - Libc Functions<br><br>
These are standard functions commonly found in <string.h>, <stdlib.h>, <ctype.h>, etc. Some of the functions implemented include:<br>

ft_memset,
ft_bzero,
ft_memcpy,
ft_strlen,
ft_strdup,
ft_strncmp,
ft_atoi,
ft_isalpha,
ft_isdigit,
ft_isalnum,
ft_isascii,
ft_isprint,
ft_toupper,
ft_tolower<br><br>
Part 2 - Additional Functions<br><br>
These functions extend the functionality of the standard library:<br>

ft_substr,
ft_strjoin,
ft_strtrim,
ft_split,
ft_itoa,
ft_strmapi,
ft_striteri,
ft_putchar_fd,
ft_putstr_fd,
ft_putendl_fd,
ft_putnbr_fd,<br>

<h3>🛠️ How to Compile</h3>
To compile the library, run:<br>

make<br>
This command will generate the libft.a file.<br>

To remove compiled files:<br>
make clean<br>

To remove everything, including the .a file:<br>
make fclean<br>

To recompile everything:<br>
make re<br>

<h3>🚀 Usage</h3>
To use libft in other projects, include the libft.h header and link the libft.a library in your project:
<br>
#include "libft.h" <br>


