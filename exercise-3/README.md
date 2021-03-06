# Exercise-3

As described in [module-4](https://github.com/INFO-201/m4-git-intro), you should begin by forking this repository, then cloning it to your local machine (if you haven't already).

In the space below, you'll provide some information about a terminal command you've learned thus far in the class. In particular, you should include the following:

A `heading` with the name of the command
An example of how it can be used (with appropriate code highlighting)
A _nested list_ of information about the command (i.e., things that it does, or how it can be used)

See `complete` branch for answers.

# The `cut` command

`cut` can be used to extract columns from a file.

For example
`cut -f3 infile > outfile` 
extracts the third column of the infile and saves it to the outfile.

####Different options and how to use them with `cut`

- -f
  - points to the column to extract
  - multiple columns can be extracted by seperating them with a comma `cut -f 1,4 filename`
- -d
  - defines the delimiter to seperate columns
  - default: \t

Combined example `cut -d : -f 1,3,56 filename`