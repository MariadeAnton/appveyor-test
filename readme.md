#Trial
Just a trial repo where I experiment with git and biicode tags.

#1. Appveyor
    - not build commit matching pattern -> working
    - if tag logic:
        + if no tag -> just publish without tag
        + if tag -> publish stable

#2. Perfect Environment variables
   - done

#3. PowerShell scripting
    - if no tag -> publish as dev 
    - if tag -> update biicode parents

#4. PowerShell compares and releases push if updated parents
    - works but finishes as unsuccesful build

#5. just a small update and minor changes
    - else check again
    - re-check