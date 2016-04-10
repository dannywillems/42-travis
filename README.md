# 42 Travis

Travis files for 42 projects

## How to use ?

This repository contains a travis file for 42 projects using different 42 test
libraries such as moulitest or libft-unit-test.
The travis file use the syntax [project]-[42-test-library]. For example, if you
want to test your libft with the moulitest, you use the travis file
libft-moulitest.

The project name use for the travis filename is giving in parenthesis.

A command is given if you want to download the corresponding travis file.

## Libft (libft)

* [moulitest](https://raw.githubusercontent.com/dannywillems/42-travis/master/libft-moulitest.yml):
  run moulitest with libft-bonus to test all files.
```
wget https://raw.githubusercontent.com/dannywillems/42-travis/master/libft-moulitest.yml >> .travis.yml
```

## Get next line (gnl)

* [moulitest](https://raw.githubusercontent.com/dannywillems/42-travis/master/gnl-moulitest.yml):
  run moulitest with get_next_line target.
```
wget https://raw.githubusercontent.com/dannywillems/42-travis/master/gnl-moulitest.yml >> .travis.yml
```
