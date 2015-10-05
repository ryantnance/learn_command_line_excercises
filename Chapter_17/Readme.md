    1. Can you show me all the files in slash temp slash foo?
        cd /tmpfind /tmp/foo -name '*' -print
            /tmp/foo
            /tmp/foo/happy.txt
            /tmp/foo/sad.txt
        
            
    
    
    2. What log files are in your log directory?
        $find . -name '*.log' -print
            ./log/one.log
            ./log/three.log
            ./log/two.log
