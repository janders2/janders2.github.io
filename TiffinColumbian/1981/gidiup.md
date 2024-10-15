
# Working with GitHub

Back to **[Obituaries](obituaries.md)**

These are necessary steps to use GitHub on a standalone basis:

## Install Software:

GitBash

blah, blah

Optionally, Install TortoiseGit

blah, blah

## Generate SSH Keys:

Do the following:

1. First see if there were any ssh keys previously set up in the $HOME directory.  
For Windows users, the containing directory might be `C:\Users\username\.ssh`.  

```sh
    ls -lart $HOME/.ssh
    cat ~/.ssh/id_rsa.pub
```

    No such file or directory

2. Generate a new SSH key pair using "xxxxxxx" as the passphrase:

You do not have to use a password, but of course it is recommended.
The -C is a comment, which in this case represents your email.  
Use the -o option to ssh-keygen to encode your private key in a new, more
secure format.

```sh
ssh-keygen -o -t rsa -b 4096 -C "john.anderson@sapns2.com"
```

## Personalize GIT:

blah, blah

## Download this Site:

Open the root URL in a browser:  https://github.com/janders2/janders2.github.io

Do the following:

```sh
 git clone https://github.com/janders2/janders2.github.io.git
```

