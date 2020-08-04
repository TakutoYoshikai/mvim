# mvim

## Requirement
OS: Ubuntu
* git
* vim

## installation
```bash
git clone https://github.com/TakutoYoshikai/mvim.git ~/.mvim
echo "export PATH=\$PATH:$HOME/.mvim/bin" >> ~/.bash_profile
source ~/.bash_profile
```

## how to use
open file
```bash
mvim <file>
```

show history and open file
```
mvim -l
#enter file number to open
```

reset history
```bash
mvim -r
```
