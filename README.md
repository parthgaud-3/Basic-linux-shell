# Linux Shell in C

Simple Linux shell written in C.

## What Does It Do?

* Executes built-in commands:
  * cd
  * help
  * exit
  * pwd
  * history
  * ! (previous command)
  * !n (nth previous command)
* Executes external commands by forking child process.

## Built With

* C
* Linux Ubuntu

## Usage

Compile shell.c from Linux terminal

```c
$ gcc -o shell shell.c
```

Execute the program

```c
$ ./shell
```

You are now in the shell

```c
>> help
>> pwd
>> [...]
>> exit
```
