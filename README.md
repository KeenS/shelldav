# ShellDAV
A WebDAV CLI.

# Usage

1. open `shelldav` and set `BASE_URL` and other variables.
2. See `./shelldav help`

```
$ ./shelldav help
NAME
  ShellDAV -- webdav cli on http://webdav.example/your/dir/

SYNOPSIS
  ./shelldav <command> [options] <args>

DESCRIPTION
get <file>        -- get the file.
put <file> [dest] -- put the file to dest. If dest is omitted, file path is used.
mkdir [-p] <path> -- make directory.
mv <file> <dest>  -- move file to dest.
cp <file> <dest>  -- copy file to dest.
rm <file> ...     -- remove the files.
```

# Requirement

* POSIX Shell (a.k.a /bin/sh)
* curl

# TODO
* Control output
* More options
* `wget` support
