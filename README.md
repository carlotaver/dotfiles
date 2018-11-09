# Mis dotfiles

## 0. Generar `ssh` keys

COnsultar [Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

### Pasos

```sh
> ssh-keygen -t rsa -b 4096 -C "carlotaverdejofernandez@gmail.com"
> bash
> eval "$(ssh-agent -s)"
> fish
> ssh-add ~/.ssh/id_rsa
> sudo apt-get install xclip
> xclip -sel clip < ~/.ssh/id_rsa.pub
```

Finalmente,nosotros necesitamos perform los pasos desde el 2 [Añadir ssh keys para cuenta github ]([https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account)

## COmo instalar

Sigue estes pasos

```sh
> cd ~/projects
> git clone git@github.com:carlotaver/dotfiles.git
> cd dotfiles
> cp ./gitconfig ~/.gitconfig
```
