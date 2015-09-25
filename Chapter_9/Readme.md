    Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error.  Try to understand why you got this error.
      mkdir Ralph
      touch RalphieBoy
      cd ..
      rmdir Ralph
      result: Directory not empty
      You cannot remove a directory that has files in it.
      
    ENGLISH QUESTIONS
    
    1. Can you touch blah.txt?
    cd Ralph
    touch blah.txt
    ls 
    RalphieBoy blah.txt
    
    2. Let's create foo.txt.  
    touch foo.txt
    ls
    RalphieBoy  blah.txt  foo.txt
    
    What happens when a if you touch an existing file.
    touch foo.txt
    the file was updated and time-stamped
