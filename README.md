# FCSC 2020 Hello Rootkitty (Harder)


Une machine a été infectée par le rootkit Hello Rootkitty qui empêche la lecture de certains fichiers. 
Votre mission : aider la victime à récupérer le contenu des fichiers affectés. Une fois connecté en SSH (ctf:ctf),
lancez le wrapper pour démarrer le challenge.

Une version plus simple de cette épreuve est disponible ici : Hello Rootkitty.

Bonus : Arriverez-vous à obtenir un shell en root ?



Fichiers :
- [bzImage](bzImage)
- [initramfs.example.cpio](initramfs.example.cpio)
- [ecsc.ko](ecsc.ko)



Auteur : [Cryptanalyse](https://twitter.com/Cryptanalyse)

Origine : [Hello Rootkitty (Harder)](https://hackropole.fr/fr/challenges/pwn/fcsc2020-pwn-hello-rootkitty-harder/)


## Connectez vous en WEBSSH
> http://localhost


-----------

## Ou directement avec ssh
> ssh -p 2222 ctf@localhost


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2020-pwn-hello-rootkitty-harder.git

> cd fcsc2020-pwn-hello-rootkitty-harder


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2020-pwn-hello-rootkitty-harder/