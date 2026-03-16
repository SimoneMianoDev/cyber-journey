# Bandit Writeups

## Livello 0 
**Obiettivo:** connettersi al server via SSH
**Comando:** ssh bandit0@bandit.labs.overthewire.org -p 2220
**Cosa ho imparato:** come connettersi via ssh ad una porta specifica 

## Livello 0 → 1
**Obiettivo:**  Trovare la password contenuta in un file chiamato «readme»
**Comando:** ssh bandit0@bandit.labs.overthewire.org -p 2220
**Cosa ho imparato:** come funziona SSH

## Livello 1 → 2
**Obiettivo:** Trovare la password contenuta in un file chiamato -
**Comando:** cat ./-
**Cosa ho imparato:** i file con nomi speciali vanno letti con ./

## Livello 2 → 3
**Obiettivo:** Trovare la password contenuta in un file chiamato --spaces in this filename--
**Comando:** cat "./--spaces in this filename--"
**Cosa ho imparato:** che per nomi con spazi devo usare " "

## Livello 3 → 4
**Obiettivo:** Trovare la password contenuta in un file nascosto 
**Comando:** ls -a 
**Cosa ho imparato:** per visualizzare cartelle nascoste devo usare ls -a
