# ARES v1.0
## Hexicdecimal Binary Encryption for Python 3.9 and Windows 10
[Tramell Software Development (AGY)](https://alectramell.github.io){:target="_blank"}

[https://alectramell.github.io](https://alectramell.github.io){:target="_blank"}


## Usage..

	>>> import ares

## Encrypt String (ASCII) to Hexicdecimal Binary..

	>>> ares.encrypt('hello world')

## Decrypt Hexidecimal Binary String to Text String (ASCII)..

	>>> ares.decrypt('68656c6c6f20776f726c64')

## Convert Text File (.txt) to Hexicdecimal Binary File (.bin)..

	>>> ares.encrypt('filename.txt')

## Convert Hexidecimal Binary File (.bin) to Text File (.txt)..

	>>> ares.decrypt('filename.bin')

## Read Hexidecimal Binary File (.bin) into Program String, then print..

	>>> print(ares.bindata('file.bin'))

