# Flatiron WSL Bashrc

bashrc used for Flatiron Students to make their prompt familiar.

### requirements

You will need `dos2unix` to convert windows endings `\r\n` to unix endings `\n`.

```
sudo apt-get install dos2unix
```

### installation
Make a backup of your .bashrc.
```
mv ~/.bashrc ~/.bashrc.bak
```
Download the .bashrc file
```
curl -R "https://raw.githubusercontent.com/Enoch2k2/flatiron-wsl-bashrc/master/.bashrc" >> $HOME/.bashrc
```
Convert the file to use unix endings 
```
dos2unix .bashrc
```