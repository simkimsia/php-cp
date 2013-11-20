php-cp
======

If you know the cp command in bash, then you would love to use this. This is for use in PHP. Currently only considers the -R or recursive key

Consider that this is the original usage of the cp command in bash

      cp [options]... Source Dest
      cp [options]... Source... Directory
      
You can easily copy one file to a new destination

      cp /path/to/abc.txt /new/dest/to/abc.txt

You can copy one file to a new directory

      cp /path/to/abc.txt /new/dest/folder

You can copy recursively one folder to another

      cp -R /path/to/folder /new/dest/folder
    
You can copy using wildcard

      cp /path/to/files/*.txt /new/dest/folder/for/text/files
    

This library aims to achieve within PHP without you googling and looking at StackOverflow for solutions.

Read this http://ss64.com/bash/cp.html for details about the original cp command in Bash
