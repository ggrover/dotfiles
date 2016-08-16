#Backup existing files

mv ~/.profile ~/.profile.bk
mv ~/.gitconfig ~/.gitconfig.bk

# Create links
ln -s ~/dotfiles/.profile ~/.profile
ln -s ~/dotfiles/.gitconfig ~/.gitconfig
