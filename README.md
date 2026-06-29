# Bash-Scripting-Notes


# Day 1

**Topic:** Introduction to Bash Scripting

**Commands learned:**
- `nano` - create or edit script files
- `chmod +x` - make a script executable
- `./script.sh` - run a script from the current directory
- `pwd` - print current working directory
- `ls` - list files in a directory
- `whoami` - show current user
- `hostname` - display system hostname
- `date` - show current date and time

**Key concepts:**
- `Bash Script` = a file containing multiple shell commands executed sequentially.
- `Shebang` tells the system which interpreter should run the script.
- Standard Bash shebang:
  
  `#!/usr/bin/env bash`

- Scripts must have **execute permission** before they can run.
- `./` tells the shell to run a file from the current directory.
- Without `./`, the shell only searches executable files inside `$PATH`.



**Script structure:**
A minimal Bash script usually looks like this:
```bash
#!/usr/bin/env bash

echo "Hello from Bash!"



    Create a script file:

                                                                    
nano first_script.sh

    Add the Bash code.

    Make the script executable:

                                                                    
chmod +x first_script.sh

    Run the script:

                                                                    
./first_script.sh

Today I learned:

    Bash scripts automate repetitive command-line tasks.
    The shebang (#!/usr/bin/env bash) ensures the correct interpreter runs the script.
    Scripts must have execute permission to run.
    Relative paths (./script.sh) are required when running scripts in the current directory.
    Bash scripts can combine multiple Linux commands into a single automated workflow.

Practice:

                                                                    
nano hello_devops.sh

#!/usr/bin/env bash

echo "Welcome to DevOps Journey"
echo "User: $(whoami)"
echo "Hostname: $(hostname)"
echo "Date: $(date)"

                                                                    
chmod +x hello_devops.sh
./hello_devops.sh


End of Day 1. 2026 June 29



