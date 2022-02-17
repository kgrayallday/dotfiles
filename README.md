# dotfiles
*nix user customization files 

## HOW TO USE 
dotfiles currently uses git bare repository to stash your files without having to move or symlink your files.

We use an alias to reach into the local git folder from elsewhere in the system where the files we want to add lives:

```alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'```



