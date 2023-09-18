# Libft: Mt First 42 School Vurriculum Project 🚀

Welcome to **Libft** - Your Ultimate Companion for 42 School's Curriculum!

## Evaluation

### Francinette

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/42_Logo.svg/2048px-42_Logo.svg.png" alt="drawing" width="170"/>

### Moulinette

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/42_Logo.svg/2048px-42_Logo.svg.png" alt="drawing" width="170"/>

## Getting Started

Getting started with Libft is a piece of cake:

1. **Clone the Repository:** \
Simply launch `git clone https://github.com/LuckyIntegral/Libft_42.git libft` in your local repository.

2. **Include the Header:** \
Add `#include "libft/libft.h"` to all your files. This gives you access to the incredible power of Libft functions.

3. **Compile Libft:** \
Run `make -C $(LIBDIR) all bonus` to create the `libft.a` static library. This library is your treasure chest of functions that will simplify your coding challenges.

4. **Link Libft:** \
To include the static library while compiling your project, use `-L libft libft.a`. This step ensures that your code leverages the magic of Libft.

## Makefile

Makefile has only 5 rules:

1. **all** \
Launch `make all` to create a static library called `libft.a` that contains mandatory functions and a bunch of my suctom functions.

2. **bonus** \
Launch `make bonus` to create a static library called `libft.a` that contains all of the mandatory functions from subject and a bunch of functions that allow you easily manipulate with linked list structure!

3. **clean** \
Launch `make clean` to remove all .o object files

4. **flcean** \
Launch `make flcean` to remove all .o object files, and libft.a file as well!

5. **re** \
Launch `make re` to recompile the whole libft project, it forces to execute `make fclean` and `make all`

## Functions
### Mandatory part, standart C libraries

- [`ft_isalpha()`](ft_isalpha.c)	- checks  for  an  alphabetic  character.
- [`ft_isdigit()`](ft_isdigit.c)	- checks for a digit (0 through 9).
- [`ft_isalnum()`](ft_isalnum.c)	- checks for an alphanumeric character.
- [`ft_isascii()`](ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [`ft_isprint()`](ft_isprint.c)	- checks for any printable character.
- [`ft_toupper()`](ft_toupper.c)	- convert char to uppercase.
- [`ft_tolower()`](ft_tolower.c)	- convert char to lowercase.
- [`ft_memset()`](ft_memset.c)	- fill memory with a constant byte.
- [`ft_strlen()`](ft_strlen.c)	- calculate the length of a string.
- [`ft_bzero()`](ft_bzero.c)	- zero a byte string.
- [`ft_memcpy()`](ft_memcpy.c)	- copy memory area.
- [`ft_memmove()`](ft_memmove.c)	- copy memory area.
- [`ft_strlcpy()`](ft_strlcpy.c)	- copy string to an specific size.
- [`ft_strlcat()`](ft_strlcat.c)	- concatenate string to an specific size.
- [`ft_strchr()`](ft_strchr.c)	- locate character in string.
- [`ft_strrchr()`](ft_strrchr.c)	- locate character in string.
- [`ft_strncmp()`](ft_strncmp.c)	- compare two strings.
- [`ft_memchr()`](ft_memchr.c)	- scan memory for a character.
- [`ft_memcmp()`](ft_memcmp.c)	- compare memory areas.
- [`ft_strnstr()`](ft_strnstr.c)	- locate a substring in a string.
- [`ft_strdup()`](ft_strdup.c)	- creates a dupplicate for the string passed as parameter.
- [`ft_atoi()`](ft_atoi.c)	- convert a string to an integer.
- [`ft_calloc()`](ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

### Mandatory part, non-standard functions
- [`ft_substr()`](ft_substr.c)	- returns a substring from a string.
- [`ft_strjoin()`](ft_strjoin.c)	- concatenates two strings.
- [`ft_strtrim()`](ft_strtrim.c)	- trims the beginning and end of string with specific set of chars.
- [`ft_split()`](ft_split.c)	- splits a string using a char as parameter.
- [`ft_itoa()`](ft_itoa.c)	- converts a number into a string.
- [`ft_strmapi()`](ft_strmapi.c)	- applies a function to each character of a string.
- [`ft_striteri()`](ft_striteri.c)	- applies a function to each character of a string.
- [`ft_putchar_fd()`](ft_putchar_fd.c)	- output a char to a file descriptor.
- [`ft_putstr_fd()`](ft_putstr_fd.c)	- output a string to a file descriptor.
- [`ft_putendl_fd()`](ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd()`](ft_putnbr_fd.c)	- output a number to a file descriptor.

### Bonus part, linked list functions

- [`ft_lstnew()`](ft_lstnew.c)	- creates a new list element.
- [`ft_lstadd_front()`](ft_lstadd_front.c)	- adds an element at the beginning of a list.
- [`ft_lstsize()`](ft_lstsize.c)	- counts the number of elements in a list.
- [`ft_lstlast()`](ft_lstlast.c)	- returns the last element of the list.
- [`ft_lstadd_back()`](ft_lstadd_back.c)	- adds an element at the end of a list.
- [`ft_lstclear()`](ft_lstclear.c)	- deletes and free list.
- [`ft_lstiter()`](ft_lstiter.c)	- applies a function to each element of a list.
- [`ft_lstmap()`](ft_lstmap.c)	- applies a function to each element of a list.
