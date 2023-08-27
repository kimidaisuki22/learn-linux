
## Change default shell
chsh @your_shell@


## Install `bash-completion` to auto completion
 apt install bash-completion

 setup auto completion
 in ~/.bashrc
```
# enable bash-completion
if ! shopt -oq posix; then
  if [ -f /usr/share/bash-completion/bash_completion ]; then
    . /usr/share/bash-completion/bash_completion
  elif [ -f /etc/bash_completion ]; then
    . /etc/bash_completion
  fi
fi
```


## Short cuts
<C-u> delete this line
<C-h> delete a character
<C-s> stop screen output
<C-q> resume screen output


##
$EDITOR
$VISUAL
sudo update-alternatives --config editor


## Find file

`find @path@ -name @pattern@`
`locate -d @path@ @pattern@`


## Profiles

/etc/pam.conf
/etc/environment
/etc/default/locale

~/.profile
~/.bash_profile
~/.bashrc

## LANG

$LANG=@ISO639@_@ISO3166@.UTF-8

LANG=en_US.UTF-8

## PATH

## Redirect

```
@command@  <<
__DELIMITER

@content@

__DELIMITER
```
will output @content@, if you use <<- instead of <<, '\t' will be ignore at the head of line.

## Alias

alias l='ls -al'
