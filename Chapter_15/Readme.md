      1. Can you put "This class is fun" into bar.txt?
          We can creat the file and add content with one cammand.
          echo "This class is fun." > bar.txt
          You can then run cat bar.txt or less bar.txt
          to see its contents
          
      2. Can you put "Oh so much fun" into foo.txt?
          We can creat the file and add content with one cammand.
          echo "Oh so much fun" > foo.txt
          You can then run cat foo.txt or less foo.txt to see the contents
          
          Explain what the |, <, > and >> do.
          
          | (pipe) takes the output of a command on the left and pipes it to the command on the right
          
          > takes takes the output of a command on the left and puts it into a specified file on the right.
            This is how we add text to a file while at the same time creating it.
            
          < takes the contents of the file on the right and input it into the program on the left  

          >> takes the output of the command on the left and appends (many times adding) it to the file on the right
