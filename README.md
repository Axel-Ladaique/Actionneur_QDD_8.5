# Actionneur inspiré d’OpenQDD

## 🦾 À propos du projet

Ce projet est un **actionneur quasi-direct (QDD)** open-source et imprimé en 3D, conçu pour offrir **un couple élevé, un faible rapport de réduction et une grande réversibilité mécanique**.  
Il peut être utilisé dans des applications robotiques dynamiques telles que des robots quadrupèdes, des exosquelettes ou des articulations motorisées.

Le projet est **largement inspiré de [OpenQDD](https://aaedmusa.github.io/projects/openqdd)** développé par *Aaed Musa*, lui-même inspiré par l’**OpenTorque Actuator** de *Gabrael Levine* et le **Cycloidal Actuator** de *James Bruton*.

L’objectif est de proposer un **actionneur compact, efficace et facile à fabriquer**, avec un **rapport de réduction de 8,5:1**, combinant performance, accessibilité et simplicité mécanique.

---

## ⚙️ Caractéristiques principales

- **Rapport de réduction :** 8,5:1  
- **Type d’entraînement :** Engrenage planétaire à dentures hélicoïdales  
- **Pièces imprimées en 3D** (boîtier et engrenages)  
- **Conception compacte et modulaire** adaptée aux articulations de robots  
- **Excellente réversibilité mécanique** pour un contrôle fluide et précis  
- **Compatible avec les moteurs BLDC** (avec codeur intégré ou externe)  
- **Projet open-source** : fichiers CAD, STL et guide d’assemblage inclus  

---

## 🛠️ Assemblage

Voici une vidéo du montage de l’actionneur :  

[![Assemblage de l’actionneur](https://github.com/user-attachments/assets/228cc91b-8264-4b44-a1cc-4c7755f2d989)](https://github.com/user-attachments/assets/228cc91b-8264-4b44-a1cc-4c7755f2d989)

---

## 📸 Galerie

<p align="center">
  <img src="https://github.com/user-attachments/assets/8faadc11-b2a1-46e1-9dd1-4296a8a6f444" width="400">
  <img src="https://github.com/user-attachments/assets/35a93a4e-711d-4f9b-a5d1-7fccd78c8dbd" width="400">
  <img src="https://github.com/user-attachments/assets/68db23bf-bc52-43a9-a21c-31c125671732" width="400">
</p>

---

## 🧮 Table des composants (BOM)

| Composant       | Référence / Modèle | Spécifications clés | Fonction dans le projet | Lien |
|-----------------|------------------|-------------------|------------------------|------|
| Roulement       | 1815 – 2RS       | Étanche 2RS, dimensions standard | Support des axes internes | [AliExpress](https://fr.aliexpress.com/item/1005008512043433.html?spm=a2g0o.order_list.order_list_main.20.5e255e5bX8Y6mn&gatewayAdapt=glo2fra) |
| Roulement       | 608ZZ             | 8 mm × 22 mm × 7 mm, miniature | Supports secondaires / guidages | [AliExpress](https://fr.aliexpress.com/item/1005003772251321.html?spm=a2g0o.order_list.order_list_main.543.5e255e5bX8Y6mn&gatewayAdapt=glo2fra) |
| Moteur BLDC     | AglePower 8308 KV90 | ~22 A max, ~900 W, KV ≈ 90 RPM/V | Moteur principal de l’actionneur | [AliExpress](https://fr.aliexpress.com/item/1005005084172325.html?spm=a2g0o.order_list.order_list_main.25.5e255e5bX8Y6mn&gatewayAdapt=glo2fra) |
| Contrôleur / Driver | ODrive S1       | 12‑48 V, 40 A continu, chopper frein intégré | Commande FOC du moteur | [ODrive Shop](https://eu.odriverobotics.com/shop/odrive-s1) |

---

## 🔗 Références et inspirations

- [OpenQDD – Aaed Musa](https://aaedmusa.github.io/projects/openqdd)  
- [OpenTorque Actuator – Gabrael Levine](https://github.com/Gabrael/OpenTorque-Actuator)  
- [Cycloidal Actuator – James Bruton](https://github.com/XRobots/openDog)



