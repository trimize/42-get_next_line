# get_next_line


Creation of one or multiple file(s) reader in c.


## Installation


```bash
git clone https://github.com/trimize/42-get_next_line.git && cd 42-get_next_line
```

## Usage

To read only one file :

```bash
make
```


For multiple files : 


```bash
make bonus
```

This will compile everything for get_next_line then include get_next_line's header in your file.

```c
import "path/to/get_next_line(_bonus if multiple files).h"
// default path : get_next_line.h

char  *str;

str = get_next_line(your_fd);

```


Compiling your file :


For one file :

```bash
cc -Wall -Wextra -Werror your_file.c get_next_line.c get_next_line.h get_next_line_utils.c
```
For multiple files :

```bash
cc -Wall -Wextra -Werror your_file.c get_next_line_bonus.c get_next_line_bonus.h get_next_line_utils_bonus.c
```

## Grade

125
