# ft_printf Project

## Introduction

The **ft_printf** project is a fascinating challenge to recreate the behavior of the standard C library function `printf()`.
This project was an incredible learning experience, providing hands-on exposure to handling variadic functions and understanding the mechanics behind one of the most commonly used C functions.
Successfully implementing `ft_printf` opens up the opportunity to add this function to your **libft** for use in future projects.

## Project Description

The goal of this project is to write a library `libftprintf.a`
containing the `ft_printf` function. The function mimics the original `printf` and supports the most commonly used conversions, making it highly versatile and reusable.

### Function Prototype

```c
int ft_printf(const char *format, ...);
