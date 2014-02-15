# PGP Public Key

[raw](https://raw.github.com/jb55/identity/master/jb55.asc)
[keybase.io proof](https://gist.github.com/jb55/9013070)

You can use my public key to verify things I sign

## Importing my identity

    curl https://raw.github.com/jb55/identity/master/jb55.asc | gpg --import

## Verifying signatures

    curl https://me.com/thingisigned.txt | gpg --verify

    gpg --verify < fileisigned.txt
    
    pbpaste | gpg --verify
    
    xclip -o | gpg --verify


