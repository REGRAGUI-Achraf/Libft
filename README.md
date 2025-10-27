# 🧠 Libft — 42/1337 Project

Libft is the very first project of the 42/1337 curriculum.
The goal is to recreate a custom C standard library — a collection of functions that replicate and extend the behavior of the original C library (libc).
This project lays the foundation for all upcoming projects by strengthening your understanding of C programming, memory management, and data structures.

## 📁 Project Structure

**Part 1**: Reimplementation of standard C library functions
(ft_strlen, ft_memcpy, ft_strncmp, ft_atoi, etc.)

**Part 2**: Additional utility functions
(ft_substr, ft_strjoin, ft_split, ft_itoa, etc.)

**Bonus**: Linked list utilities
(ft_lstnew, ft_lstadd_back, ft_lstmap, etc.)

## ⚙️ Compilation
```bash
make          # compile the library
make clean    # remove object files
make fclean   # remove object files and libft.a
make re       # recompile everything
```

The compilation creates a static library called:
```
libft.a
```

You can include it in your future projects with:
```bash
gcc main.c libft.a -o program
```

## 🧩 Skills developed

- Mastery of pointers and memory allocation
- Implementation of data structures (linked lists)
- Code rigor and understanding of the 42 norm
- Building reusable and modular C code

## 🏫 Project Information

**School**: 1337 (42 Network)

**Language**: C

**Status**: ✅ Completed

**Evaluation**: 125/100