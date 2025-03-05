# 🏰 PingCastle  
Un outil puissant pour analyser la sécurité de votre Active Directory et détecter les vulnérabilités avant qu'elles ne deviennent des menaces.  

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Security](https://img.shields.io/badge/security-high-red.svg)  

## 🛡️ Fonctionnalités de Sécurité  
✔️ Détection des comptes à risque  
✔️ Analyse des délégations dangereuses  
✔️ Identification des permissions trop permissives  
✔️ Vérification des anciennes GPO non sécurisées  
✔️ Surveillance des vulnérabilités courantes  

## 📋 Prérequis  
- Windows 7/10/11 ou Windows Server  
- .NET Framework 4.5 ou supérieur  
- Accès avec un compte ayant les droits de lecture sur l'AD  

## 🛠️ Installation  
Téléchargez la dernière version depuis le site officiel ou GitHub :  
```sh
git clone https://github.com/PingCastle/PingCastle.git  
cd PingCastle  
```

## 📖 Guide d'utilisation  

###  Analyse rapide de l'Active Directory  
```sh
PingCastle.exe --healthcheck --server mon-domaine.local
```

###  Génération d'un rapport détaillé  
```sh
PingCastle.exe --healthcheck --server mon-domaine.local --export report.html
```

###  Comparaison avec une analyse précédente  
```sh
PingCastle.exe --compare ancien_rapport.xml nouveau_rapport.xml
```
### Besoin d'aide ?

N'hésite pas a me contacter via discord ou telegram (check mon read.me) pour toute demande d'assistance concernant l'utilisation de l'outil !

---

**by user99x
**
![PingCastle Logo](https://your-image-url.com/image.png)
---
