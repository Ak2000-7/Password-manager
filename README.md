
# Password manager

Develop and implement a password manager as a command line application.



## Authors

- [@Anjan Kumar](https://github.com/Ak2000-7)


## Technologies

- Programming language : Python
- Libraries: csv,getpass,pathlib,datetime,sys,pyperclip,array,string
## Deployment

Before running the file you have to run command:

```bash
   pip install pyperclip
```

   

## Features

 - python passman.py add -title instagram -username user123456 -generatepassword (For generating new password)

 - python passman.py copy -title instagram (For copying password)

 - python passman.py delete -title instagram (For deleting a password)

 - python passman.py export -filename exported.csv (For exporting password to exported.csv)

 - python passman.py change -title instagram (For changing password of instagram)

 - python passman.py master -update (For changing master password)


## Usage/Examples

Generating new password for Instagram:

$ passman add -title instagram -username user123456 -generatepassword
--> OK password created and copied to clipboard

Retrieve password for Instagram:
$ passman copy -title instagram
--> Master-Password:
--> Master ok
--> Username: uas123456 | password copied to clipboard



## Support

Steps pretty much are self explanatory. Necessary comments at appropriate places added.

Feel free to ask of any doubts and consider dropping a ⭐ if the repo was of help!

