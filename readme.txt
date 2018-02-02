Last login: Tue Jan 30 15:59:35 on ttys000
Bradleys-MacBook-Pro:~ bradleythiessen$ pwd
/Users/bradleythiessen
Bradleys-MacBook-Pro:~ bradleythiessen$ cd lighthouse
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Clearing any previously set forwarded ports...
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 3000 (guest) => 3000 (host) (adapter 1)
    default: 3001 (guest) => 3001 (host) (adapter 1)
    default: 8080 (guest) => 8080 (host) (adapter 1)
    default: 5000 (guest) => 5000 (host) (adapter 1)
    default: 5432 (guest) => 5432 (host) (adapter 1)
    default: 22 (guest) => 2222 (host) (adapter 1)
==> default: Running 'pre-boot' VM customizations...
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
==> default: Mounting shared folders...
    default: /vagrant => /Users/bradleythiessen/lighthouse
==> default: Machine already provisioned. Run `vagrant provision` or use the `--provision`
==> default: flag to force provisioning. Provisioners marked to run always will still run.
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ vagrant ssh
Welcome to Ubuntu 16.04.3 LTS (GNU/Linux 4.4.0-87-generic x86_64)
           .-='-. _db_      .--==-,
          (_  (  _IIII_   _(    )  `.
            (    |" " |-.(  ` ,_  `  )
             '-._HHHHHH  `)---' `'--'
                 |.   |--`
                 |    |      Lighthouse Labs
       _H___,=====;___|      Built # 20171219-141500-8dc7a2e
    n_/____/____/``\__\
   /__|:: :|. .|:::|::|      Direct complaints to /dev/null
_%&|__&%_"_|_"_|_ H|__|__

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage
Last login: Wed Jan 31 00:51:49 2018 from 10.0.2.2
vagrant [vagrant]> npm install -g javascripting
/home/vagrant/.nvm/versions/node/v8.9.4/bin/javascripting -> /home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/javascripting/bin/javascripting
+ javascripting@2.6.1
added 111 packages in 10.718s
vagrant [vagrant]> javascripting
























                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                             
   » VARIABLES                                                                
   » STRINGS                                                                  
   » STRING LENGTH                                                            
   » REVISING STRINGS                                                         
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              












































   
 # JAVASCRIPTING  
   
 ## INTRODUCTION (Exercise 1 of 19)  
   
  To keep things organized, let's create a folder for this workshop.  
   
  Run this command to make a directory called javascripting (or something  
  else if you like):  
   
     mkdir javascripting  
   
  Change directory into the javascripting folder:  
   
     cd javascripting  
   
  Create a file named introduction.js:  
   
     touch introduction.js  
   
  Or if you're on Windows:  
   
     type NUL > introduction.js  
   
  (type is part of the command!)  
   
  Open the file in your favorite editor, and add this text:  
   
     console.log('hello');  
   
  Save the file, then check to see if your program is correct by running  
  this command:  
   
     javascripting verify introduction.js  
   
  By the way, throughout this tutorial, you can give the file you work with  
  any name you like, so if you want to use something like catsAreAwesome.js  
  file for every exercise, you can do that. Just make sure to run:  
   
     javascripting verify catsAreAwesome.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [vagrant]> mkdir javascripting
vagrant [vagrant]> cd javascripting
vagrant [javascripting]> touch introduction.js
vagrant [javascripting]> type NUL > introduction.js
-bash: type: NUL: not found
vagrant [javascripting]> 
Display all 1958 possibilities? (y or n)
vagrant [javascripting]> javascripting verify introduction.js

# JAVASCRIPTING

## INTRODUCTION (Exercise 1 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 hello

 Your Attempt ===================

 Hello

 Difference ===================

 hHello

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls introduction.js'. If you see 'ls: cannot access introduction.js: No                                                                          
    such file or directory,' then perhaps the file doesn't exist, or has a                                                                          
    different name, or is in a different directory.                           
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting verify introduction.js

# JAVASCRIPTING

## INTRODUCTION (Exercise 1 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# YOU DID IT!

 Anything between the parentheses of console.log() are printed to the
 terminal.

 So this:

    console.log('hello');

 prints hello to the terminal.

 Currently we are printing a string of characters to the terminal: hello.

 In the next challenge we focus on learning about variables.

 Run javascripting in the console to choose the next challenge.

 You have 18 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> exit
logout
Connection to 127.0.0.1 closed.
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ vagrant ssh
Welcome to Ubuntu 16.04.3 LTS (GNU/Linux 4.4.0-87-generic x86_64)
           .-='-. _db_      .--==-,
          (_  (  _IIII_   _(    )  `.
            (    |" " |-.(  ` ,_  `  )
             '-._HHHHHH  `)---' `'--'
                 |.   |--`
                 |    |      Lighthouse Labs
       _H___,=====;___|      Built # 20171219-141500-8dc7a2e
    n_/____/____/``\__\
   /__|:: :|. .|:::|::|      Direct complaints to /dev/null
_%&|__&%_"_|_"_|_ H|__|__

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage
Last login: Wed Jan 31 01:44:22 2018 from 10.0.2.2
vagrant [vagrant]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                                
   » STRINGS                                                                  
   » STRING LENGTH                                                            
   » REVISING STRINGS                                                         
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## VARIABLES (Exercise 2 of 19)  
   
  A variable is a name that can reference a specific value. Variables are  
  declared using var followed by the variable's name.  
   
  Here's an example:  
   
     var example;  
   
  The above variable is declared, but it isn't defined (it does not yet  
  reference a specific value).  
   
  Here's an example of defining a variable, making it reference a specific  
  value:  
   
     var example = 'some string';  
   
 # NOTE  
   
  A variable is declared using var and uses the equals sign to define the  
  value that it references. This is colloquially known as "Making a variable  
  equal a value".  
   
 ## The challenge:  
   
  Create a file named variables.js.  
   
  In that file declare a variable named example.  
   
  Make the variable example equal to the value 'some string'.  
   
  Then use console.log() to print the example variable to the console.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify variables.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [vagrant]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

Error: ERROR: /vagrant/variables.js does not exist!
    at /home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/javascripting/lib/run-solution.js:51:13
    at tryCallOne (/home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/javascripting/node_modules/promise/lib/core.js:37:12)
    at /home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/javascripting/node_modules/promise/lib/core.js:123:15
    at flush (/home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/javascripting/node_modules/asap/raw.js:50:29)
    at _combinedTickCallback (internal/process/next_tick.js:131:7)
    at process._tickCallback (internal/process/next_tick.js:180:9)
vagrant [vagrant]> cd javascript
-bash: cd: javascript: No such file or directory
vagrant [vagrant]> ls
javascripting  temp_test_file.txt  Vagrantfile
vagrant [vagrant]> cd javascripting
vagrant [javascripting]> javascript verify variables.js
-bash: javascript: command not found
vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 some string

 Your Attempt ===================

 Difference ===================

 some string 

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls variables.js'. If you see 'ls: cannot access variables.js: No such                                                                          
    file or directory,' then perhaps the file doesn't exist, or has a                                                                          
    different name, or is in a different directory.                           
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

{ Error: Command failed: node "/vagrant/javascripting/variables.js"
/vagrant/javascripting/variables.js:3
output example;
       ^^^^^^^

SyntaxError: Unexpected identifier
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:607:28)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/variables.js"' }
vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

{ Error: Command failed: node "/vagrant/javascripting/variables.js"
/vagrant/javascripting/variables.js:2
set example = 'some string';
    ^^^^^^^

SyntaxError: Unexpected identifier
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:607:28)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/variables.js"' }
vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

{ Error: Command failed: node "/vagrant/javascripting/variables.js"
/vagrant/javascripting/variables.js:2
output example;
       ^^^^^^^

SyntaxError: Unexpected identifier
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:607:28)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/variables.js"' }
vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 some string

 Your Attempt ===================

 Difference ===================

 some string 

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls variables.js'. If you see 'ls: cannot access variables.js: No such                                                                          
    file or directory,' then perhaps the file doesn't exist, or has a                                                                          
    different name, or is in a different directory.                           
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting print
   
 # JAVASCRIPTING  
   
 ## VARIABLES (Exercise 2 of 19)  
   
  A variable is a name that can reference a specific value. Variables are  
  declared using var followed by the variable's name.  
   
  Here's an example:  
   
     var example;  
   
  The above variable is declared, but it isn't defined (it does not yet  
  reference a specific value).  
   
  Here's an example of defining a variable, making it reference a specific  
  value:  
   
     var example = 'some string';  
   
 # NOTE  
   
  A variable is declared using var and uses the equals sign to define the  
  value that it references. This is colloquially known as "Making a variable  
  equal a value".  
   
 ## The challenge:  
   
  Create a file named variables.js.  
   
  In that file declare a variable named example.  
   
  Make the variable example equal to the value 'some string'.  
   
  Then use console.log() to print the example variable to the console.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify variables.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

{ Error: Command failed: node "/vagrant/javascripting/variables.js"
/vagrant/javascripting/variables.js:2
console log();
        ^^^

SyntaxError: Unexpected identifier
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:607:28)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/variables.js"' }
vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 some string

 Your Attempt ===================

 Difference ===================

 some string

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls variables.js'. If you see 'ls: cannot access variables.js: No such                                                                          
    file or directory,' then perhaps the file doesn't exist, or has a                                                                          
    different name, or is in a different directory.                           
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting verify variables.js

# JAVASCRIPTING

## VARIABLES (Exercise 2 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# YOU CREATED A VARIABLE!

 Nice work.

 In the next challenge we will look at strings more closely.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 17 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                                  
   » STRING LENGTH                                                            
   » REVISING STRINGS                                                         
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## STRING LENGTH (Exercise 4 of 19)  
   
  You will often need to know how many characters are in a string.  
   
  For this you will use the .length property. Here's an example:  
   
     var example = 'example string';  
     example.length  
   
 ## NOTE  
   
  Make sure there is a period between example and length.  
   
  The above code will return a number for the total number of characters in  
  the string.  
   
 ## The challenge:  
   
  Create a file named string-length.js.  
   
  In that file, create a variable named example.  
   
  Assign the string 'example string' to the variable example.  
   
  Use console.log to print the length of the string to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify string-length.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting

























                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                                  
   » STRING LENGTH                                                            
   » REVISING STRINGS                                                         
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## STRINGS (Exercise 3 of 19)  
   
  A string is a sequence of characters. A character is, roughly speaking, a  
  written symbol. Examples of characters are letters, numbers, punctuation  
  marks, and spaces.  
   
  String values are surrounded by either single or double quotation marks.  
   
     'this is a string'  
       
     "this is also a string"  
   
 ## NOTE  
   
  Try to stay consistent. In this workshop we'll only use single quotation  
  marks.  
   
 ## The challenge:  
   
  For this challenge, create a file named strings.js.  
   
  In that file create a variable named someString like this:  
   
     var someString = 'this is a string';  
   
  Use console.log to print the variable someString to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify strings.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify strings.js

# JAVASCRIPTING

## STRINGS (Exercise 3 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# SUCCESS.

 You are getting used to this string stuff!

 In the next challenges we will cover how to manipulate strings.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 16 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                                            
   » REVISING STRINGS                                                         
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## STRING LENGTH (Exercise 4 of 19)  
   
  You will often need to know how many characters are in a string.  
   
  For this you will use the .length property. Here's an example:  
   
     var example = 'example string';  
     example.length  
   
 ## NOTE  
   
  Make sure there is a period between example and length.  
   
  The above code will return a number for the total number of characters in  
  the string.  
   
 ## The challenge:  
   
  Create a file named string-length.js.  
   
  In that file, create a variable named example.  
   
  Assign the string 'example string' to the variable example.  
   
  Use console.log to print the length of the string to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify string-length.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify string-length.js

# JAVASCRIPTING

## STRING LENGTH (Exercise 4 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# WIN: 14 CHARACTERS

 You got it! The string example string has 14 characters.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 15 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                                         
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## REVISING STRINGS (Exercise 5 of 19)  
   
  You will often need to change the contents of a string.  
   
  Strings have built-in functionality that allow you to inspect and  
  manipulate their contents.  
   
  Here is an example using the .replace() method:  
   
     var example = 'this example exists';  
     example = example.replace('exists', 'is awesome');  
     console.log(example);  
   
  Note that to change the value that the example variable references, we  
  need to use the equals sign again, this time with the example.replace()  
  method to the right of the equals sign.  
   
 ## The challenge:  
   
  Create a file named revising-strings.js.  
   
  Define a variable named pizza that references this string: 'pizza is  
  alright'  
   
  Use the .replace() method to change alright to wonderful.  
   
  Use console.log() to print the results of the .replace() method to the  
  terminal.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify revising-strings.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify revising-strings.js

# JAVASCRIPTING

## REVISING STRINGS (Exercise 5 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# YES, PIZZA IS WONDERFUL.

 Well done, with that .replace() method!

 Next we will explore numbers.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 14 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                                  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## NUMBERS (Exercise 6 of 19)  
   
  Numbers can be integers, like 2, 14, or 4353, or they can be decimals,  
  also known as floats, like 3.14, 1.5, or 100.7893423. Unlike Strings,  
  Numbers do not need to have quotes.  
   
 ## The challenge:  
   
  Create a file named numbers.js.  
   
  In that file define a variable named example that references the integer  
  123456789.  
   
  Use console.log() to print that number to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
  javascripting verify numbers.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify numbers.js

# JAVASCRIPTING

## NUMBERS (Exercise 6 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# YEAH! NUMBERS!

 Cool, you successfully defined a variable as the number 123456789.

 In the next challenge we will look at manipulating numbers.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 13 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                                         
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## ROUNDING NUMBERS (Exercise 7 of 19)  
   
  We can do basic math using familiar operators like +, -, *, /, and %.  
   
  For more complex math, we can use the Math object.  
   
  In this challenge we'll use the Math object to round numbers.  
   
 ## The challenge:  
   
  Create a file named rounding-numbers.js.  
   
  In that file define a variable named roundUp that references the float  
  1.5.  
   
  We will use the Math.round() method to round the number up. This method  
  rounds either up or down to the nearest integer.  
   
  An example of using Math.round():  
   
     Math.round(0.5);  
   
  Define a second variable named rounded that references the output of the  
  Math.round() method, passing in the roundUp variable as the argument.  
   
  Use console.log() to print that number to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify rounding-numbers.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify rounding-numbers.js

# JAVASCRIPTING

## ROUNDING NUMBERS (Exercise 7 of 19)

{ Error: Command failed: node "/vagrant/javascripting/rounding-numbers.js"
/vagrant/javascripting/rounding-numbers.js:2
var rounded = math.round(example);   
              ^

ReferenceError: math is not defined
    at Object.<anonymous> (/vagrant/javascripting/rounding-numbers.js:2:15)
    at Module._compile (module.js:643:30)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/rounding-numbers.js"' }
vagrant [javascripting]> javascripting verify rounding-numbers.js

# JAVASCRIPTING

## ROUNDING NUMBERS (Exercise 7 of 19)

{ Error: Command failed: node "/vagrant/javascripting/rounding-numbers.js"
/vagrant/javascripting/rounding-numbers.js:2
var rounded = math.round(1.5);   
              ^

ReferenceError: math is not defined
    at Object.<anonymous> (/vagrant/javascripting/rounding-numbers.js:2:15)
    at Module._compile (module.js:643:30)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/rounding-numbers.js"' }
vagrant [javascripting]> javascripting verify rounding-numbers.js

# JAVASCRIPTING

## ROUNDING NUMBERS (Exercise 7 of 19)

{ Error: Command failed: node "/vagrant/javascripting/rounding-numbers.js"
/vagrant/javascripting/rounding-numbers.js:2
var rounded = math.round(roundUp);   
              ^

ReferenceError: math is not defined
    at Object.<anonymous> (/vagrant/javascripting/rounding-numbers.js:2:15)
    at Module._compile (module.js:643:30)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/rounding-numbers.js"' }
vagrant [javascripting]> javascripting verify rounding-numbers.js

# JAVASCRIPTING

## ROUNDING NUMBERS (Exercise 7 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# THAT NUMBER IS ROUNDED

 Yep, you just rounded the number 1.5 to 2. Good job.

 In the next challenge we will turn a number into a string.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 12 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                                         
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## NUMBER TO STRING (Exercise 8 of 19)  
   
  Sometimes you will need to turn a number into a string.  
   
  In those instances you will use the .toString() method. Here's an example:  
   
     var n = 256;  
     n = n.toString();  
   
 ## The challenge:  
   
  Create a file named number-to-string.js.  
   
  In that file define a variable named n that references the number 128;  
   
  Call the .toString() method on the n variable.  
   
  Use console.log() to print the results of the .toString() method to the  
  terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify number-to-string.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify number-to-string.js

# JAVASCRIPTING

## NUMBER TO STRING (Exercise 8 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# THAT NUMBER IS NOW A STRING!

 Excellent. Good work converting that number into a string.

 In the next challenge we will take a look at if statements.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 11 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                             
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## IF STATEMENT (Exercise 9 of 19)  
   
  Conditional statements are used to alter the control flow of a program,  
  based on a specified boolean condition.  
   
  A conditional statement looks like this:  
   
     if (n > 1) {  
       console.log('the variable n is greater than 1.');  
     } else {  
       console.log('the variable n is less than or equal to 1.');  
     }  
   
  Inside parentheses you must enter a logic statement, meaning that the  
  result of the statement is either true or false.  
   
  The else block is optional and contains the code that will be executed if  
  the statement is false.  
   
 ## The challenge:  
   
  Create a file named if-statement.js.  
   
  In that file, declare a variable named fruit.  
   
  Make the fruit variable reference the value orange with the type of  
  String.  
   
  Then use console.log() to print "The fruit name has more than five  
  characters." if the length of the value of fruit is greater than five.  
  Otherwise, print "The fruit name has five characters or less."  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify if-statement.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify if-statement.js 

# JAVASCRIPTING

## IF STATEMENT (Exercise 9 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 The fruit name has more than five characters.

 Your Attempt ===================

 The fruit name has more than five characters

 Difference ===================

 The fruit name has more than five characters.

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls if-statement.js'. If you see 'ls: cannot access if-statement.js: No                                                                          
    such file or directory,' then perhaps the file doesn't exist, or has a                                                                          
    different name, or is in a different directory.                           
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting verify if-statement.js 

# JAVASCRIPTING

## IF STATEMENT (Exercise 9 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# CONDITIONAL MASTER

 You got it! The string orange has more than five characters.

 Get ready to take on for loops next!

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 10 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                                 
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## FOR LOOP (Exercise 10 of 19)  
   
  For loops allow you to repeatedly run a block of code a certain number of  
  times. This for loop logs to the console ten times:  
   
     for (var i = 0; i < 10; i++) {  
       // log the numbers 0 through 9  
       console.log(i)  
     }  
   
  The first part, var i = 0, is run once at the beginning of the loop. The  
  variable i is used to track how many times the loop has run.  
   
  The second part, i < 10, is checked at the beginning of every loop  
  iteration before running the code inside the loop. If the statement is  
  true, the code inside the loop is executed. If it is false, then the loop  
  is complete. The statement i < 10; indicates that the loop will continue  
  as long as i is less than 10.  
   
  The final part, i++, is executed at the end of every loop. This increases  
  the variable i by 1 after each loop. Once i reaches 10, the loop will  
  exit.  
   
 ## The challenge:  
   
  Create a file named for-loop.js.  
   
  In that file define a variable named total and make it equal the number 0.  
   
  Define a second variable named limit and make it equal the number 10.  
   
  Create a for loop with a variable i starting at 0 and increasing by 1 each  
  time through the loop. The loop should run as long as i is less than  
  limit.  
   
  On each iteration of the loop, add the number i to the total variable. To  
  do this, you can use this statement:  
   
     total += i;  
   
  After the for loop, use console.log() to print the total variable to the  
  terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify for-loop.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify for-loop.js

# JAVASCRIPTING

## FOR LOOP (Exercise 10 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# THE TOTAL IS 45

 That is a basic introduction to for loops, which are handy in a number of
 situations, particularly in combination with other data types like strings
 and arrays.

 In the next challenge we'll start working with arrays.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 9 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                                   
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## ARRAYS (Exercise 11 of 19)  
   
  An array is a list of values. Here's an example:  
   
     var pets = ['cat', 'dog', 'rat'];  
   
 ### The challenge:  
   
  Create a file named arrays.js.  
   
  In that file define a variable named pizzaToppings that references an  
  array that contains three strings in this order: tomato sauce, cheese,  
  pepperoni.  
   
  Use console.log() to print the pizzaToppings array to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify arrays.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify arrays.js

# JAVASCRIPTING

## ARRAYS (Exercise 11 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# YAY, A PIZZA ARRAY!

 You successfully created an array!

 In the next challenge we will explore filtering arrays.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 8 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting
'

                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































vagrant [javascripting]> javascripting






































































                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                                          
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## ARRAY FILTERING (Exercise 12 of 19)  
   
  There are many ways to manipulate arrays.  
   
  One common task is filtering arrays to only contain certain values.  
   
  For this we can use the .filter() method.  
   
  Here is an example:  
   
     var pets = ['cat', 'dog', 'elephant'];  
       
     var filtered = pets.filter(function (pet) {  
       return (pet !== 'elephant');  
     });  
   
  The filtered variable will now only contain cat and dog.  
   
 ## The challenge:  
   
  Create a file named array-filtering.js.  
   
  In that file, define a variable named numbers that references this array:  
   
     [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];  
   
  Like above, define a variable named filtered that references the result of  
  numbers.filter().  
   
  The function that you pass to the .filter() method will look something  
  like this:  
   
     function evenNumbers (number) {  
       return number % 2 === 0;  
     }  
   
  Use console.log() to print the filtered array to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify array-filtering.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify array-filtering.js

# JAVASCRIPTING

## ARRAY FILTERING (Exercise 12 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# FILTERED!

 Good job filtering that array.

 In the next challenge we will work on an example of accessing array
 values.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 7 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                                   
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## ACCESSING ARRAY VALUES (Exercise 13 of 19)  
   
  Array elements can be accessed through index number.  
   
  Index number starts from zero to array's property length minus one.  
   
  Here is an example:  
   
     var pets = ['cat', 'dog', 'rat'];  
       
     console.log(pets[0]);  
   
  The above code will print the first element of pets array - string cat.  
   
  Array elements must be accessed through only using bracket notation.  
   
  Dot notation is invalid.  
   
  Valid notation:  
   
     console.log(pets[0]);  
   
  Invalid notation:  
   
     console.log(pets.1);  
   
 ## The challenge:  
   
  Create a file named accessing-array-values.js.  
   
  In that file, define array food :  
   
     var food = ['apple', 'pizza', 'pear'];  
   
  Use console.log() to print the second value of array to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify accessing-array-values.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify accessing-array-values.js

# JAVASCRIPTING

## ACCESSING ARRAY VALUES (Exercise 13 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# SECOND ELEMENT OF ARRAY PRINTED!

 Good job accessing that element of array.

 In the next challenge we will work on an example of looping through
 arrays.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 6 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                                   
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## LOOPING THROUGH ARRAYS (Exercise 14 of 19)  
   
  For this challenge we will use a for loop to access and manipulate a list  
  of values in an array.  
   
  Accessing array values can be done using an integer.  
   
  Each item in an array is identified by a number, starting at 0.  
   
  So in this array hi is identified by the number 1:  
   
     var greetings = ['hello', 'hi', 'good morning'];  
   
  It can be accessed like this:  
   
     greetings[1];  
   
  So inside a for loop we would use the i variable inside the square  
  brackets instead of directly using an integer.  
   
 ## The challenge:  
   
  Create a file named looping-through-arrays.js.  
   
  In that file, define a variable named pets that references this array:  
   
     ['cat', 'dog', 'rat'];  
   
  Create a for loop that changes each string in the array so that they are  
  plural.  
   
  You will use a statement like this inside the for loop:  
   
     pets[i] = pets[i] + 's';  
   
  After the for loop, use console.log() to print the pets array to the  
  terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify looping-through-arrays.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify looping-through-arrays.js

# JAVASCRIPTING

## LOOPING THROUGH ARRAYS (Exercise 14 of 19)

{ Error: Command failed: node "/vagrant/javascripting/looping-through-arrays.js"
/vagrant/javascripting/looping-through-arrays.js:2
var i = 0; i > 3; i++ {
                      ^

SyntaxError: Unexpected token {
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:607:28)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/looping-through-arrays.js"' }
vagrant [javascripting]> javascripting verify looping-through-arrays.js

# JAVASCRIPTING

## LOOPING THROUGH ARRAYS (Exercise 14 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 [ 'cats', 'dogs', 'rats' ]

 Your Attempt ===================

 [ 'cat', 'dogs', 'rat' ]

 Difference ===================

 [ 'cats', 'dogs', 'rats' ]

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls looping-through-arrays.js'. If you see 'ls: cannot access                                                                          
    looping-through-arrays.js: No such file or directory,' then perhaps the                                                                          
    file doesn't exist, or has a different name, or is in a different                                                                          
    directory.                                                                
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting verify looping-through-arrays.js

# JAVASCRIPTING

## LOOPING THROUGH ARRAYS (Exercise 14 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# SUCCESS! LOTS OF PETS!

 Now all the items in that pets array are plural!

 In the next challenge we will move from arrays to working with objects.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 5 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                                  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## OBJECTS (Exercise 15 of 19)  
   
  Objects are lists of values similar to arrays, except values are  
  identified by keys instead of integers.  
   
  Here is an example:  
   
     var foodPreferences = {  
       pizza: 'yum',  
       salad: 'gross'  
     };  
   
 ## The challenge:  
   
  Create a file named objects.js.  
   
  In that file, define a variable named pizza like this:  
   
     var pizza = {  
       toppings: ['cheese', 'sauce', 'pepperoni'],  
       crust: 'deep dish',  
       serves: 2  
     };  
   
  Use console.log() to print the pizza object to the terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify objects.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify objects.js

# JAVASCRIPTING

## OBJECTS (Exercise 15 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# PIZZA OBJECT IS A GO.

 You successfully created an object!

 In the next challenge we will focus on accessing object properties.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 4 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                     [COMPLETED]  
   » OBJECT PROPERTIES                                                        
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## OBJECT PROPERTIES (Exercise 16 of 19)  
   
  You can access and manipulate object properties –– the keys and values  
  that an object contains –– using a method very similar to arrays.  
   
  Here's an example using square brackets:  
   
     var example = {  
       pizza: 'yummy'  
     };  
       
     console.log(example['pizza']);  
   
  The above code will print the string 'yummy' to the terminal.  
   
  Alternately, you can use dot notation to get identical results:  
   
     example.pizza;  
       
     example['pizza'];  
   
  The two lines of code above will both return yummy.  
   
 ## The challenge:  
   
  Create a file named object-properties.js.  
   
  In that file, define a variable named food like this:  
   
     var food = {  
       types: 'only pizza'  
     };  
   
  Use console.log() to print the types property of the food object to the  
  terminal.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify object-properties.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify object-properties.js

# JAVASCRIPTING

## OBJECT PROPERTIES (Exercise 16 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# CORRECT. PIZZA IS THE ONLY FOOD.

 Good job accessing that property.

 The next challenge is all about functions.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 3 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                     [COMPLETED]  
   » OBJECT PROPERTIES                                           [COMPLETED]  
   » FUNCTIONS                                                                
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## FUNCTIONS (Exercise 17 of 19)  
   
  A function is a block of code that takes input, processes that input, and  
  then produces output.  
   
  Here is an example:  
   
     function example (x) {  
       return x * 2;  
     }  
   
  We can call that function like this to get the number 10:  
   
     example(5)  
   
  The above example assumes that the example function will take a number as  
  an argument –– as input –– and will return that number multiplied by 2.  
   
 ## The challenge:  
   
  Create a file named functions.js.  
   
  In that file, define a function named eat that takes an argument named  
  food that is expected to be a string.  
   
  Inside the function return the food argument like this:  
   
     return food + ' tasted really good.';  
   
  Inside of the parentheses of console.log(), call the eat() function with  
  the string bananas as the argument.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify functions.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> ^C
vagrant [javascripting]> javascripting verify functions.js 

# JAVASCRIPTING

## FUNCTIONS (Exercise 17 of 19)

─────────────────────────────────────────────────────────────────────────────

# O-oh, something isn't working.

# But don't panic!

─────────────────────────────────────────────────────────────────────────────

## Check your solution:

 Solution ===================

 bananas tasted really good.

 Your Attempt ===================

 Bananas tasted really good.

 Difference ===================

 bBananas tasted really good.

## Additional troubleshooting:

  » Did you type the name of the file correctly? You can check by running                                                                          
    'ls functions.js'. If you see 'ls: cannot access functions.js: No such                                                                          
    file or directory,' then perhaps the file doesn't exist, or has a                                                                          
    different name, or is in a different directory.                           
  » Make sure you didn't omit any parens, or the compiler will not be able                                                                          
    to parse it.                                                              
  » Make sure you don't have any typos in the string itself.                  

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting verify functions.js 

# JAVASCRIPTING

## FUNCTIONS (Exercise 17 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# WOOO BANANAS

 You did it! You created a function that takes input, processes that input,
 and provides output.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have 2 challenges left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                     [COMPLETED]  
   » OBJECT PROPERTIES                                           [COMPLETED]  
   » FUNCTIONS                                                   [COMPLETED]  
   » FUNCTION ARGUMENTS                                                       
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## FUNCTION ARGUMENTS (Exercise 18 of 19)  
   
  A function can be declared to receive any number of arguments. Arguments  
  can be from any type. An argument could be a string, a number, an array,  
  an object and even another function.  
   
  Here is an example:  
   
     function example (firstArg, secondArg) {  
       console.log(firstArg, secondArg);  
     }  
   
  We can call that function with two arguments like this:  
   
     example('hello', 'world');  
   
  The above example will print to the terminal hello world.  
   
 ## The challenge:  
   
  Create a file named function-arguments.js.  
   
  In that file, define a function named math that takes three arguments.  
  It's important for you to understand that arguments names are only used to  
  reference them.  
   
  Name each argument as you like.  
   
  Within the math function, return the value obtained from multiplying the  
  second and third arguments and adding that result to the first argument.  
   
  After that, inside the parentheses of console.log(), call the math()  
  function with the number 53 as first argument, the number 61 as second and  
  the number 67 as third argument.  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify function-arguments.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> javascripting verify function-arguments.js

# JAVASCRIPTING

## FUNCTION ARGUMENTS (Exercise 18 of 19)

{ Error: Command failed: node "/vagrant/javascripting/function-arguments.js"
/vagrant/javascripting/function-arguments.js:1
(function (exports, require, module, __filename, __dirname) { function math (num1, num2, num3)) {
                                                                                              ^

SyntaxError: Unexpected token )
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:607:28)
    at Object.Module._extensions..js (module.js:654:10)
    at Module.load (module.js:556:32)
    at tryModuleLoad (module.js:499:12)
    at Function.Module._load (module.js:491:3)
    at Function.Module.runMain (module.js:684:10)
    at startup (bootstrap_node.js:187:16)
    at bootstrap_node.js:608:3

    at ChildProcess.exithandler (child_process.js:275:12)
    at emitTwo (events.js:126:13)
    at ChildProcess.emit (events.js:214:7)
    at maybeClose (internal/child_process.js:925:16)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:209:5)
  killed: false,
  code: 1,
  signal: null,
  cmd: 'node "/vagrant/javascripting/function-arguments.js"' }
vagrant [javascripting]> javascripting verify function-arguments.js

# JAVASCRIPTING

## FUNCTION ARGUMENTS (Exercise 18 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────

# YOU'RE IN CONTROL OF YOUR ARGUMENTS!

 Well done completing the exercise.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You have one challenge left.

 Type 'javascripting' to show the menu.

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                     [COMPLETED]  
   » OBJECT PROPERTIES                                           [COMPLETED]  
   » FUNCTIONS                                                   [COMPLETED]  
   » FUNCTION ARGUMENTS                                          [COMPLETED]  
   » SCOPE                                                                    
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
 ## SCOPE (Exercise 19 of 19)  
   
  Scope is the set of variables, objects, and functions you have access to.  
   
  JavaScript has two scopes: global and local. A variable that is declared  
  outside a function definition is a global variable, and its value is  
  accessible and modifiable throughout your program. A variable that is  
  declared inside a function definition is local. It is created and  
  destroyed every time the function is executed, and it cannot be accessed  
  by any code outside the function.  
   
  Functions defined inside other functions, known as nested functions, have  
  access to their parent function's scope.  
   
  Pay attention to the comments in the code below:  
   
     var a = 4;    // a is a global variable, it can be accessed by the functions below  
       
     function foo() {  
         var b = a * 3;    // b cannot be accessed outside foo function, but can be accessed by functions  
                         // defined inside foo  
         function bar(c) {  
         var b = 2;  // another `b` variable is created inside bar function scope  
                     // the changes to this new `b` variable don't affect the old `b` variable  
         console.log( a, b, c );  
         }  
       
         bar(b * 4);  
     }  
       
     foo(); // 4, 2, 48  
   
  IIFE, Immediately Invoked Function Expression, is a common pattern for  
  creating local scopes.  
   
  Example:  
   
         (function(){ // the function expression is surrounded by parenthesis  
             // variables defined here  
             // can't be accessed outside  
         })(); // the function is immediately invoked  
   
 ## The challenge:  
   
  Create a file named scope.js.  
   
  In that file, copy the following code:  
   
     var a = 1, b = 2, c = 3;  
       
     (function firstFunction(){  
         var b = 5, c = 6;  
       
         (function secondFunction(){  
             var b = 8;  
       
             (function thirdFunction(){  
                 var a = 7, c = 9;  
       
                 (function fourthFunction(){  
                     var a = 1, c = 8;  
       
                 })();  
             })();  
         })();  
     })();  
   
  Use your knowledge of the variables' scope and place the following code  
  inside one of the functions in scope.js so the output is a: 1, b: 8, c: 6  
   
     console.log("a: "+a+", b: "+b+", c: "+c);  
   
  Check to see if your program is correct by running this command:  
   
     javascripting verify scope.js  
   
 ─────────────────────────────────────────────────────────────────────────────  
  Need help? View the README for this workshop:  
  (http://github.com/sethvincent/javascripting)  
   
 ─────────────────────────────────────────────────────────────────────────────  
   
   » To print these instructions again, run: javascripting print                 
   » To execute your program in a test environment, run: javascripting run                                                                            
     program.js                                                                  
   » To verify your program, run: javascripting verify program.js                
   » For help run: javascripting help                                            
   
vagrant [javascripting]> ^C
vagrant [javascripting]> javascripting verify scope.js 

# JAVASCRIPTING

## SCOPE (Exercise 19 of 19)

 Here's the official solution in case you want to compare notes:

─────────────────────────────────────────────────────────────────────────────
 #EXCELLENT!

 You got it! The second function has the scope we were looking for.

 Run javascripting in the console to choose the next challenge.

─────────────────────────────────────────────────────────────────────────────
 You've finished all the challenges! Hooray!

─────────────────────────────────────────────────────────────────────────────
 Need help? View the README for this workshop:
 (http://github.com/sethvincent/javascripting)

─────────────────────────────────────────────────────────────────────────────

  » To print these instructions again, run: javascripting print               
  » To execute your program in a test environment, run: javascripting run                                                                          
    program.js                                                                
  » To verify your program, run: javascripting verify program.js              
  » For help run: javascripting help                                          

vagrant [javascripting]> javascripting


                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                     [COMPLETED]  
   » OBJECT PROPERTIES                                           [COMPLETED]  
   » FUNCTIONS                                                   [COMPLETED]  
   » FUNCTION ARGUMENTS                                          [COMPLETED]  
   » SCOPE                                                       [COMPLETED]  
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































   
 # JAVASCRIPTING  
   
  javascripting@2.6.1 is already at the latest version.  
   
  Congratulations!  
   
vagrant [javascripting]> javascripting































































                                                                              
   JAVASCRIPTING                                                              
   Select an exercise and hit Enter to begin                                  
   ─────────────────────────────────────────────────────────────────────────  
   » INTRODUCTION                                                [COMPLETED]  
   » VARIABLES                                                   [COMPLETED]  
   » STRINGS                                                     [COMPLETED]  
   » STRING LENGTH                                               [COMPLETED]  
   » REVISING STRINGS                                            [COMPLETED]  
   » NUMBERS                                                     [COMPLETED]  
   » ROUNDING NUMBERS                                            [COMPLETED]  
   » NUMBER TO STRING                                            [COMPLETED]  
   » IF STATEMENT                                                [COMPLETED]  
   » FOR LOOP                                                    [COMPLETED]  
   » ARRAYS                                                      [COMPLETED]  
   » ARRAY FILTERING                                             [COMPLETED]  
   » ACCESSING ARRAY VALUES                                      [COMPLETED]  
   » LOOPING THROUGH ARRAYS                                      [COMPLETED]  
   » OBJECTS                                                     [COMPLETED]  
   » OBJECT PROPERTIES                                           [COMPLETED]  
   » FUNCTIONS                                                   [COMPLETED]  
   » FUNCTION ARGUMENTS                                          [COMPLETED]  
   » SCOPE                                                       [COMPLETED]  
   ─────────────────────────────────────────────────────────────────────────  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CHECK FOR UPDATE                                                           
   EXIT                                                                       
                                                                              








































vagrant [javascripting]> exit
logout
Connection to 127.0.0.1 closed.
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ git --version
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ git --version
git version 2.14.3 (Apple Git-98)
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ git config --global user.name "Zharphyn"
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ git config --global user.email "brad@zharphyn.ca"
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ git-it verify
-bash: git-it: command not found
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ npm install -g git-it
-bash: npm: command not found
Bradleys-MacBook-Pro:lighthouse bradleythiessen$ vagrant ssh
Welcome to Ubuntu 16.04.3 LTS (GNU/Linux 4.4.0-87-generic x86_64)
           .-='-. _db_      .--==-,
          (_  (  _IIII_   _(    )  `.
            (    |" " |-.(  ` ,_  `  )
             '-._HHHHHH  `)---' `'--'
                 |.   |--`
                 |    |      Lighthouse Labs
       _H___,=====;___|      Built # 20171219-141500-8dc7a2e
    n_/____/____/``\__\
   /__|:: :|. .|:::|::|      Direct complaints to /dev/null
_%&|__&%_"_|_"_|_ H|__|__

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage
Last login: Wed Jan 31 01:51:36 2018 from 10.0.2.2
vagrant [vagrant]> npm install -g git it
npm WARN deprecated graceful-fs@1.2.3: please upgrade to graceful-fs 4 for compatibility with current and future versions of Node.js
npm WARN deprecated minimatch@0.2.14: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm WARN deprecated coffee-script@1.3.3: CoffeeScript on NPM has moved to "coffeescript" (no hyphen)
npm WARN deprecated minimatch@0.3.0: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
/home/vagrant/.nvm/versions/node/v8.9.4/bin/it -> /home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/it/bin/it
+ it@1.1.1
+ git@0.1.5
added 55 packages in 1.891s
vagrant [vagrant]> git --version
git version 2.7.4
vagrant [vagrant]> git-it verify
-bash: git-it: command not found

                                                                       
    GIT + GITHUB : VERSION CONTROL + SOCIAL CODING                     
    -----------------------------------------------------------------  
    » GET GIT                                                          
    » REPOSITORY                                                       
    » COMMIT TO IT                                                     
    » GITHUBBIN                                                        
    » REMOTE CONTROL                                                   
    » FORKS AND CLONES                                                 
    » BRANCHES AREN'T JUST FOR BIRDS                                   
    » IT'S A SMALL WORLD                                               
    » PULL, NEVER OUT OF DATE                                          
    » REQUESTING YOU PULL, PLEASE                                      
    » MERGE TADA!                                                      
    -----------------------------------------------------------------  
    HELP                                                               

                                                                       
    GIT + GITHUB : VERSION CONTROL + SOCIAL CODING                     

                                                                       
    GIT + GITHUB : VERSION CONTROL + SOCIAL CODING                     
    -----------------------------------------------------------------  
    » GET GIT                                             [COMPLETED]  
    » REPOSITORY                                          [COMPLETED]  
    » COMMIT TO IT                                                     
    » GITHUBBIN                                                        
    » REMOTE CONTROL                                                   
    » FORKS AND CLONES                                                 
    » BRANCHES AREN'T JUST FOR BIRDS                                   
    » IT'S A SMALL WORLD                                               
    » PULL, NEVER OUT OF DATE                                          
    » REQUESTING YOU PULL, PLEASE                                      
    » MERGE TADA!                                                      
    -----------------------------------------------------------------  
    HELP                                                               
    EXIT                                                               
                                                                       

  #####################################################################
  ##                      ~~  COMMIT TO IT  ~~                       ##
  #####################################################################

  Create a file in your new repository, add something to that file
  and commit those changes to Git.

  Use the guide (see below) for step-by-step instructions.

  ---------------------------------------------------------------------

  » To verify your work for this problem, run: `git-it verify`.
  » Run `git-it` again to launch menu & go onto next challenge

  GUIDE

  » Open the guide in your browser: jlord.github.io/git-it
  » Traditional Chinese guide: jlord.github.io/git-it/index-zhtw.html

  » To view guide offline, copy this address to your browser:
  » /home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/git-it/guide/index.html 
  » /home/vagrant/.nvm/versions/node/v8.9.4/lib/node_modules/git-it/guide/index-zhtw.html


vagrant [hello-world]> vim




















The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox jumped over the lazy dog. The quick brown fox ju
mped over the lazy dog.
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
~                                                                                                                                                               
-- INSERT --                                                                                                                                  1,184         All
