# crunch
tool for creating wordlist

origin repository [https://salsa.debian.org/debian/crunch](https://salsa.debian.org/debian/crunch)

## crunch Usage Example

Generate a dictionary file containing words with a minimum and maximum length of 6 (`6 6`) using the given characters (`0123456789abcdef`), saving the output to a file (`-0 6chars.txt`):

```shell
root@kali:~# crunch 6 6 0123456789abcdef -o 6chars.txt
Crunch will now generate the following amount of data: 117440512 bytes
112 MB
0 GB
0 TB
0 PB
Crunch will now generate the following number of lines: 16777216
```

# Packages and Binaries:
> crunch

Crunch is a wordlist generator where you can specify a standard character set or any set of characters to be used in generating the wordlists. The wordlists are created through combination and permutation of a set of characters. You can determine the amount of characters and list size.

This program supports numbers and symbols, upper and lower case characters separately and Unicode.

**Installed size:** `83 KB`

**How to install:** `sudo apt install crunch`

<details>
<summary>Dependencies</summary>
<pre>
<code>libc6</code>
</pre>
</details>

## crunch

Generate wordlists from a character set

```shell
root@kali:~# crunch -h
crunch version 3.6

Crunch can create a wordlist based on criteria you specify.  The output from crunch can be sent to the screen, file, or to another program.

Usage: crunch <min> <max> [options]
where min and max are numbers

Please refer to the man page for instructions and examples on how to use crunch.
```

*Updated on: 2021-Nov-26*
