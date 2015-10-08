###Questions

    1. What option to ls tells it to output file size in human readable form?
      man ls
      -h
      Also:   When used with the -l option, use unit suffixes: Byte, Kilobyte, Megabyte,
              Gigabyte, Terabyte and Petabyte in order to reduce the number of digits to
              three or less using base 2 for sizes.

    2. Is there a case insensitive option to grep?
      man grep
        -i 
        Ignore case in searches

    3. What does the -r and -f options to rm do exactly?
      man rm
      -f  Attempt to remove the files without prompting for confirmation, regard-
          less of the file's permissions.  If the file does not exist, do not
          display a diagnostic message or modify the exit status to reflect an
          error.  The -f option overrides any previous -i options.
      
      -r removes all subdirectories within the directory.  In other words, it removes
         the chain of directories and files

    4. What does the ifconfig command do?
      man iconfig
      configures network interface parameters
