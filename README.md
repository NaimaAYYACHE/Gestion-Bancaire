# Gestion Bancaire

## Description

L'application Gestion Bancaire permet de gérer l'ensemble des clients et leurs comptes bancaires respectifs au niveau des agences bancaires affiliées à une banque particulière. L'application est destinée aux employés d'une agence bancaire ainsi qu'à un certain nombre d'employés du siège de la banque. Un employé d'une agence a donc accès à l'ensemble des opérations de gestion pour chaque une des agences, gestionnaires, opérations, clients et comptes. Il peut effectuer des opérations telles que l'ajout, la modification, la suppression, la visualisation de la liste et la recherche. De plus, il peut consulter le solde, la liste des clients, la liste des comptes fantômes et les relevés bancaires.

## Fonctionnalités

- Ajout, modification, suppression et visualisation des éléments pour chaque entité (agence, gestionnaire, opération, client, compte)
- Consultation du solde, de la liste des clients, de la liste des comptes fantômes et des relevés bancaires

## Modèle Conceptuel de Projet

![Capture d’écran 2023-10-22 140612](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/22c106fd-45de-40ba-806f-390518f1660f)

## Modèle Physique de Projet

![Capture d’écran 2023-10-22 140650](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/a1f7b5aa-94d8-4c34-ab37-d8a0b8832638)

## Tables et Requêtes de la Base de Données

### a) Tables

<b>Table Agence :</b><br>
  Colonnes :<br>
  ![Capture d’écran 2023-10-22 141138](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/303d7efe-bd8b-49fa-b96d-b44a9bd70739)
  <br>
  Données :<br>
  ![Capture d’écran 2023-10-22 141304](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/3b085e2e-f8ed-4a8d-ad63-e96fb63fbea7)
   <br>
  <b>Table Compte :</b><br>
  Colonnes :<br>
  ![Capture d’écran 2023-10-22 141355](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/de9e7005-76b5-456f-9b00-bfb8a5907f00)
   <br>
  Données : <br>
  ![Capture d’écran 2023-10-22 141433](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/305a9f10-f4e3-4cee-b1cf-8c4f657a969e)
   <br>
  <b>Table Gestionnaire :</b> <br>
  Colonnes :<br>
  ![Capture d’écran 2023-10-22 141511](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/118cfffe-24ea-4e8b-9103-bb58e7fecea5)
   <br>
  Données :<br>
  ![Capture d’écran 2023-10-22 141542](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/b5ea67a9-4566-4ccb-a4d6-029fffdbf403)
   <br>
  <b>Table Client :</b><br>
  Colonnes :<br>
  ![Capture d’écran 2023-10-22 141640](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/3d6bb7fc-0e61-4056-98e5-1280ece13939)
   <br>
  Données :<br>
  ![Capture d’écran 2023-10-22 141724](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/6df9c9bf-a2ca-49f3-98d8-3c0906718bf5)
    <br>
  <b>Table Opérations :</b><br>
  Colonnes :<br>
  ![Capture d’écran 2023-10-22 141806](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/d41c3139-31c7-42d4-8062-a1307c64c074)
  <br>
  Données :<br>
   ![Capture d’écran 2023-10-22 141848](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/e1aeb34b-ad1a-4e6f-9ee3-8f9c1a9beb6e)
    <br>

### b) Création des Tables

![Capture d’écran 2023-10-22 141933](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/6cbbcc50-ef9c-48a1-9f17-73c3b24ea396)
<br><br>
![kk](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/b92eceb8-4831-4cab-8512-419f3b520144)

## Installation

### Prérequis

Assurez-vous d'avoir les éléments suivants installés sur votre système :

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Oracle Database](https://www.oracle.com/database/)
- [Java Swing](https://docs.oracle.com/javase/tutorial/uiswing/)

### Étapes d'Installation

1. Clonez ce référentiel sur votre machine locale.
2. Configurez la base de données Oracle en éditant le fichier de configuration.
3. Exécutez les scripts SQL pour initialiser la base de données.
4. Lancez l'application en utilisant Java Swing.


## Captures d'Écran

<b>a) Menu Général :</b><br>
Le menu offre un accès facile aux différents formulaires disponibles, permettant aux gestionnaires de sélectionner rapidement le formulaire souhaité en cliquant sur son icône respective.<br><br>
![Capture d’écran 2023-10-22 143021](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/9735d34d-2e35-4950-ad11-f6b49479bb1b)<br><br>
<b>b) Agence :</b><br>
Pour accéder au formulaire « Agence » il suffit de cliquer sur l'icon d'Agence ou Dans le Menu General<br><br>
![Capture d’écran 2023-10-22 143328](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/62134b7e-668f-4346-8921-c951e5a68aa5)<br><br>
Dans ce formulaire, vous avez la possibilité de modifier, supprimer et rechercher les informations relatives à l'agence bancaire, telles que le nom, l'adresse et le numéro de téléphone. Pour effacer les zones de texte, cliquez sur l'icône correspondante, pour naviguer entre les différentes options, cliquez sur les icônes appropriées, et pour retourner au Menu Général, utilisez l'icône 'Home'
<br><br>
![Capture d’écran 2023-10-22 143638](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/cc6ef610-3385-4bc0-ab3c-c2fa3f83728b)<br><br>

<b>c) Gestionnaires :</b><br>
Pour accéder au formulaire de gestionnaire, il vous suffit de cliquer sur « Gestionnaires ». Dans ce formulaire, vous avez la possibilité d'ajouter un nouveau gestionnaire ou de modifier les coordonnées d'un gestionnaire existant, telles que le nom et le poste. Les icônes situées en bas vous permettent de naviguer pour visualiser, chercher, ajouter et supprimer des gestionnaires au sein de l'agence.<br><br>

![Capture d’écran 2023-10-22 151042](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/2eff8dbe-496c-443a-aa68-2ed31d0f34e9) <br><br>

<b>d) Clients : </b><br>
Tout comme le formulaire précédent, ce formulaire permet de visualiser les clients de l'agence ainsi que d'ajouter, de supprimer ou de rechercher un client.. <br><br>

![Capture d’écran 2023-10-22 151220](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/f98698ec-82af-49f5-b880-22499e2fcf0d)<br><br>

<b>e) Comptes :</b><br>
Lors de l'ajout d'un nouveau client, il est nécessaire de créer son compte en sélectionnant l'option 'Comptes'. Ensuite, vous pouvez renseigner l'identifiant du client et le type de compte (épargne, courant, etc.), ainsi que les dates d'ouverture et de validité du compte.
<br><br>
![Capture d’écran 2023-10-22 151514](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/9c458b9c-a46e-4dbb-9f17-7ae5715dbcbc)
<br><br>
<b>f) Opérations :</b><br>
Pour réaliser une opération, veuillez sélectionner l'option « Effectuer une opération »."
Dans cette section, vous avez la possibilité d'effectuer diverses opérations bancaires telles que le versement d'espèces, les virements, le dépôt de chèques, etc. Vous pouvez spécifier le titre, la date de l'opération, ainsi que le montant initial et le montant à ajouter. De plus, vous avez la possibilité de consulter les opérations précédentes.<br><br>
![image](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/21c10e70-bad0-40a0-93f3-84bc9a12f107)<br><br>

<b>g) Relevé Bancaire :</b><br>
Pour générer le relevé bancaire d'un compte, cliquez simplement sur « Relevé Bancaire ».<br><br>

![image](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/eac653e9-6ad1-4b08-b77d-802e3a515230)<br><br>


<b>h) Comptes fantômes :</b><br>
Pour afficher les comptes fantômes ou les comptes vide de l’agence il suffit de 
cliquer sur « comptes fantômes »<br><br>
![image](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/1ae334e0-b81e-4a91-aac8-6d74a6223ffe)<br><br>

<b>i) Solde :</b><br>
En sélectionnant « Solde » dans le menu, vous pouvez consulter le solde d'un client.<br><br>

![image](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/6868499e-d59c-47b1-bafb-42ab7015ef67)<br><br>

<b>j) Liste des Clients :</b><br>
En sélectionnant « Liste des Clients » dans le menu, vous pouvez consulter la liste des clients.<br><br>

![image](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/a207b1fa-0f6b-4ad3-953c-82a3c9121956)<br><br>

<b>k) Liste des Gestionnaires :</b><br>
En sélectionnant « Liste des Gestionnaires » dans le menu, vous pouvez consulter la liste des gestionnaires.<br><br>

![image](https://github.com/NaimaAYYACHE/Gestion-Bancaire/assets/105889744/f0af8549-4c59-4664-8b3e-5ef9ee063206)

