# ✏️ ft_printf
A custom implementation of the standard C `printf` function.
It replicates the core functionality of `printf`, handling various format specifiers and producing formatted output to the standard output, without using the original `printf`.  
This project deepens understanding of variadic functions, memory handling, and formatted string construction in low-level C.

## ✅ Supported Format Specifiers

- `%c` → character  
- `%s` → string  
- `%p` → pointer address  
- `%d` / `%i` → signed decimal integer  
- `%u` → unsigned decimal integer  
- `%x` / `%X` → hexadecimal (lowercase / uppercase)  
- `%%` → literal `%` character

## 🔧 Usage

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/ft_printf.git
cd ft_printf
````

### 2. Compile
````bash
make
````

### 3. Link with your code
````bash
gcc your_code.c libftprintf.a
````

## Example
````C
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello %s, number: %d, hex: %x\n", "world", 42, 42);
    return (0);
}

````





