<h1 align="center">💬 Mini Tchat PHP</h1>

<p align="center">Mini application de discussion avec inscription, connexion et messages persistés en base MySQL.</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-7%2B-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/MVC-architecture-334155?style=flat-square" alt="MVC" />
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap" />
</p>

## À propos

Ce projet met en pratique une architecture MVC en PHP orienté objet : contrôleurs, modèles, templates et classe de connexion PDO sont séparés. Il propose un parcours simple d'inscription, de connexion et de publication de messages.

## Fonctionnalités

- création de compte ;
- connexion et déconnexion ;
- affichage des messages ;
- publication de messages pour les utilisateurs connectés ;
- persistance MySQL avec PDO ;
- interface Bootstrap.

## Installation locale

Prérequis : PHP avec PDO MySQL et MySQL/MariaDB.

1. Créer une base mini-tchat.
2. Importer [sql/mini-tchat.sql](sql/mini-tchat.sql).
3. Adapter la connexion dans src/lib/database.php si nécessaire.
4. Servir le projet depuis sa racine :

    php -S localhost:8000 -t public

Ouvrir ensuite http://localhost:8000.

## Contexte

Exercice de formation consacré à PHP, la POO, MVC, PDO et les sessions. Les contrôles de sécurité et la configuration sont volontairement limités à un usage local pédagogique.

## Auteur

[Christopher Semard](https://github.com/christophersemard)
