<p align="center">
<img src="./gnl-logo.png" />
</p>
<h1 align="center">ft_printf</h1>
<p align="center">You will recode printf(). You will mainly learn about using a variable number of arguments.</p>

- PROGRAM NAME |
libftprintf.a

- TURN IN FILES |
Makefile, *.h, */*.h, *.c, */*.c

- MAKEFILE |
NAME, all, clean, fclean, re

- EXTERNAL FUNCTS |
malloc, free, write,
va_start, va_arg, va_copy, va_end

- LIBFT AUTHORIZED |
Yes.

- DESCRIPTION |
Write a library that contains ft_printf(), a function that will mimic the original printf().

- PROTOTYPE |
int ft_printf(const char *, ...);
_

<h2>Useful Links</h2>
<ul>
<li><a href="https://github.com/fegastal/42SP_ft_printf_contents/blob/main/variadic_functions.pdf">Variadic Functions</a></li>
</ul>

<h2>Requirements (Mandatory Part)</h2>
<ul>
<li>Don’t implement the buffer management of the original printf().</li>
<li>Your function has to handle the following conversions: cspdiuxX%</li>
<li>Your function will be compared against the original printf().</li>
<li>You must use the command ar to create your library. Using the libtool command is forbidden.</li>
<li>Your libftprintf.a has to be created at the root of your repository</li>
<li>You have to implement the following conversions:</li>
<li>• %c Prints a single character</li>
<li>• %s Prints a string (as defined by the common C convention).</li>
<li>• %p The void * pointer argument has to be printed in hexadecimal format.</li>
<li>• %d Prints a decimal (base 10) number.</li>
<li>• %i Prints an integer in base 10.</li>
<li>• %u Prints an unsigned decimal (base 10) number.</li>
<li>• %x Prints a number in hexadecimal (base 16) lowercase format</li>
<li>• %X Prints a number in hexadecimal (base 16) uppercase format.</li>
<li>• %% Prints a percent sign.</li>
</ul>
