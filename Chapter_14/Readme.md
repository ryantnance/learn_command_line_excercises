    Why is it dangerous to run "rm -rf/"?
      This command will delete all files inside the system, even system files.
      
    1. Can you remove blah.txt?
        mkdir tmp
        cd tmp
        touch blah.txt
        ls (blah.txt)
        rm blah.txt
        ls (no files)
          
    2. Let's get rid of our development log file.
        cd tmp
        touch development.log
        ls
        rm development.log
        ls
    
    3. Can you remove everything in the slash temp slash foo directory?    
        rmdir /tmp/foo
        Directory not empty
        rm -rf /tmp/foo/
        
