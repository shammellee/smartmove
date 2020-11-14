# Smart Move (smv)

Smart move is a Unix utility that copies one or more source files to a
destination directory and, if the copy was successful without error, deletes
(unlinks) the source file(s).

## Installation

Copy the `smv` file to a location in your `$PATH` environment variable (eg,
`/usr/local/bin`) or run the script directly.

## Usage

```sh
$ smv <source> [...] <destination-directory>

# Example
$ smv source_dir/* dest_dir
$ smv file_1 file_2 file_3 dest_dir

# Running smv directly
$ ./smv source_dir/* dest_dir
$ ./smv file_1 file_2 file_3 dest_dir
```

