      Make 20 more directories and remove them all.
        I did a mkdir 1, mkdir 2 ... mkdir 20
        then rmdir 20, rmdir 19 ... rmdir 1
        
      Make a single path of directories that is 10 deep and remove them one at a time just like I did above.
        I did mkdir a/b/c/d/e/f/g/h/i/j
        cd a/b/c/d/e/f/g/h/i/j
        cd ..
        rmdir j
        cd ..
        rmdir i
        cd ..
        rmdir h
        cd ..
        rmdir g
        cd ..
        rmdir f
        cd ..
        rmdir e
        cd ..
        rmdir d
        cd ..
        rmdir c
        cd .. 
        rmdir b
        cd ..
        rmdir a
        
      1. Can you remove the tmp directory?
        You cannot remove tmp because it is not empty.
        You could remove each of the directories under tmp individually first 

      2. Let's remove the tmp directory.
        cd tmp/stuff/things/frank/joe/alex
        rmdir john
        cd ..
        rmdir alex
        cd ..
        rmdir joe
        cd ..
        rmdir frank
        cd ..
        rmdir things
        cd ..
        rmdir stuff
        cd ..
        rmdir tmp
        
