# how-to-install-brew-on-mac


Brew è sostanzialmente un repository dove poter scaricare, 
installare e mantenere aggiornato del software open source.
In pratica lo possiamo vedere come una sorta di app store, s
olo che tutto avviene via linea di comando.



Controllare se brew è installato

## Aprire il terminale e digitare brew :

```
brew

```


Se vi appare 
zsh: command not found: brew

Significa che non è installato.

## Comando per installare brew :

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


Su Mac M1, M2, M3 :

## Eseguire questi 2 comandi :

```
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> ~/.zprofile
```

```
eval "$(/opt/homebrew/bin/brew shellenv)"
```


## Verifica dell'installazione :

```
brew doctor
```

## Per installare un nuovo software
```
brew install NOME_DEL_SOFTWARE
```

## Per visionare tutti i software installati :


```
brew list

```


