# TnutTnut
Projet camion radiocommandé Arduino

Tout dans le désordre pour le moment :

2 projets imbriqués.

Le premier sera facile avec la gestion moteurs / roues / puissance / alim

Le second rajoutera la notion de roues directionnelles (besoin d'une conception mécanique)


## Projet facile

### Concept

Camion possédant 4 roues :
  - Les 2 de devant seront sur un essieu mobile
  - Les 2 à l'arrière seront chacune pilotées par un moteur
  
2 batteries :
  - Une pour alimenter l'arduino (9V)
  - Une pour alimenter les différents moteurs (12 V)
  
3 moteurs :
  - 2 moteurs DC pour chaque roue arrière
  - 1 servomoteur pour l'essieu dirigeable
  
1 carte électronique + 1 shield :
  - Si RF alors Arduino nano (facile)
  - Si WiFi alors nodeMCU (et pas de shield) (assez difficile)
  - si Bluetooth alors Nano (facile si piloté par PC)
  
1 pont en H pour le pilotage des moteurs DC

1 PCB à cause de la haute consommation des moteurs

**Un buzzer pour faire _Tnut Tnut_**

### Liste des pièces

**_To be filled

### Réalisation du code

- [ ] Choix du mode de communication
- [ ] Pilotage du servomoteur
- [ ] Pilotage des 2 moteurs à l'aide d'un pont en H
- [ ] Réalisation de l'interface de communication sans fil
- [ ] Mise en place des roues + Réalisation d'un support physique
- [ ] Augmentation de la puissance des moteurs arrières et réalisation du PCB _Alimentation_
- [ ] Ajout de l'arbre de direction à l'avant

### Réalisatiçon mécanique

**_To be filled
