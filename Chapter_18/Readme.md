###Questions

    1. Show me the lines in foo.txt that have "ERROR" in them.
      touch foo.txt
      cat > foo.txt
        this line does not have an error
        this line does
        are you sure?
        I'm sure this line does not have an error
        Look again
      grep -i ERROR foo.txt
        this line does not have an error
        I'm sure this line does not have an error
    
    2. Show me the lines in bar.txt that have "davinci" in them.
      touch bar.txt
      cat > bar.txt
        davinci coders teaches me
        I learn from Davinci
        Leo's last name is Dicaprio
      grep -i davinci bar.txt
        Davinci coders teaches me
        I learn from Davinci
        
    3. Can you print all the lines in text files that have your first and last name in them?
      touch file_1.txt
      touch file_2.txt
      
      cat > newfile_1.txt
        My name is Henry Jones'
        no it isn't, it's Ralph Cramden
        wrong again, it's Ryan Nance
        Are you sure?
        Yep
      cat > newfile_2.txt
        Hello, I'm Ryan Nance
        Nice to meet you.
        
        That name again is Ryan Nance.
       
      grep 'Ryan Nance' *.txt
        newfile_1.txt:wrong again, it's Ryan Nance
        newfile_2.txt:Hello, I'm Ryan Nance
        newfile_2.txt:That name again is Ryan Nance.
        
    4. What does the option -i to grep accomplishes
      This allows you to search files without the need to be case sensitive.
