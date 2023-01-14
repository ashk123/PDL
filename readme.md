Document of PDL ( package downloading lainOS )

<<<<<<< HEAD
# Description

        PDL is a small tool for downloading and installing packages, its not a package system
        its sub-package system
        (you can read more about it in sub-package system side)
        PDL can handle network, wtih git repository this feature that allows you
        to download any packages from internet with .pdl file, and patch it into the PDL database
        like other package system you can update your pdl files with PDL git repository.
        You can made a .pdl file and share it with your friend, or push it into PDL repository
        we made this just for fun!, you can use it for your important works or fun moments

# PDL git repository

        PDL have a git repository in laingit and github, 
        you can choose one of these options for your work
        in client, when you want to update your pfl files, you can choose your repository
        for uploading, we must see all your installation commands, 
        after that we save it into repository

# Why PDL ?

        PDL just created for reason to have a visual package downloader in LainOS
        we don't wanted to create a main packaging system like apt or any things like that
        we made a simple program for users that people can understand easily, 
        how package downloaders work
        you can use or not, its your choice, it's easy for work and install. 
        (check LainOS website for new updates)

# Can I work on it as FAN ?

        Absolutely yes!, we want other users made better features for PDL
        If you want to made your custom PDL, you should do these works :
        1. clone PDL source code from LainOS github
        2. add or modify your custom features
        3. push it into your own github and send your git-rep link to us <br>
        3-2. or send .zip file as a email to us

# Dev Information

        Database: sqlite3 V3.34.1 <br>
        Programming Language: Bash V5.1.4 <br>
        OS: LainOS (debian)


# Have good time with PDL !
=======
*This is PDL beta version 3.5*
*We add more features on this version, but is still beta*
*features:*
- Install: you can install programs on single mode, that means you can download special program without upgrade your whole system
- Make: you can make your patch file, without doing anything, just use `pdl make <your_patch_file_name>` and pdl automaticly make
a patch file for you
- API: added a github api for installing programs with better way
- Search: you can search your patch file, use `pdl search <patch_file_name>`
- Net menu item is changed, now you can search your package with name instead of selecting

*Notice: if you want to make this version better, you can but just don't fork this on your main repo, this version is not stable!*
>>>>>>> 50ae7db8ad00935b617baf7d1fdac36630d74216
