# EUSART

Quoi ?

L'EUSART gère les UART, SPI-bus, et communication IrDA. (InfraredDATA)

Pourquoi ?

La communication série est fréquemment utilisée dans les systèmes embarqués et l'EUSART permet une communication efficace avec une large gamme de périphériques externes.

Comment ?

L'EUSART dispose d'un large choix de commandes modes, formats de trame et débits en bauds. Le mode multiprocesseur permet à l'EUSART de rester inactif lorsqu’il n’est pas abordé. La prise en charge de 16 FIFO et DMA permet des débits de données élevés avec un minimum Intervention du CPU et il est possible de transmettre et recevoir de grandes trames pendant que le MCU reste dans un état de EM1 sleep.

## Introduction

Le récepteur et émetteur série asynchrone universel amélioré (EUSART) est un module d'E/S série très flexible. Il prend en charge la communication UART asynchrone full duplex ainsi que SPI, MicroWire. Il peut également s'interfacer avec les appareils IrDA.

## Description fonctionnel

Cette section décrit toutes les fonctionnalités EUSART possibles. Veuillez vous référer à la fiche technique de l'appareil pour voir les fonctionnalités d'un EUSART spécifique. l'instance prend en charge.