# how-to-install-brew-on-mac


Controllare se brew è installato

Aprire il terminale e digitare brew :

```
brew

```


Se vi appare 
zsh: command not found: brew

Significa che non è installato.

Comando per installare brew :

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


Su Mac M1, M2, M3 :

Eseguire questi 2 comandi :

```
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> ~/.zprofile
```

```
eval "$(/opt/homebrew/bin/brew shellenv)"
```


Verifica dell'installazione :

```
brew doctor
```






