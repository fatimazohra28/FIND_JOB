
# 🎯 Projet PFE - Plateforme de Recrutement

Ce projet est une application web Full Stack utilisant **Laravel** pour le backend et **React** pour le frontend.

---

## 🧪 Technologies utilisées

- Laravel 10 (API RESTful)
- React.js (dans `resources/js/frontend1`)
- MySQL (base de données)

---

## 🚀 Instructions d'installation

### Backend (Laravel)

1. Cloner le projet
```bash
git clone https://github.com/fatimazohra28/projet_PFE.git
cd projet_PFE
```

2. Installer les dépendances PHP
```bash
composer install
```

3. Copier le fichier `.env`
```bash
cp .env.example .env
```

4. Générer la clé d'application
```bash
php artisan key:generate
```

5. Configurer la base de données dans `.env`, puis :
```bash
php artisan migrate
```

6. Lancer le serveur Laravel :
```bash
php artisan serve
```

---

### Frontend (React)

1. Aller dans le dossier du frontend
```bash
cd resources/js/frontend1
```

2. Installer les dépendances Node.js
```bash
npm install
```

3. Lancer le serveur React :
```bash
npm run dev
```

---

## ✅ Résultat

Une plateforme de recrutement avec :
- Création de comptes utilisateurs
- Recherche et publication d’offres
- Authentification
- Interface utilisateur moderne

---
### 👥 Rôles dans l’application FIND_JOB :

L'application propose une séparation claire des rôles avec des interfaces et fonctionnalités adaptées à chaque type d'utilisateur :

#### 🧑‍💼 Admin :
- Gère les utilisateurs (recruteurs et candidats)
- Valide ou supprime les annonces publiées
- Supervise l’ensemble des activités sur la plateforme
- Accède à un tableau de bord d’administration

#### 🧑‍🔧 Recruteur :
- Crée et gère son propre profil entreprise
- Publie, modifie et supprime ses offres d'emploi
- Consulte les candidatures reçues
- Communique avec les candidats via la plateforme

#### 👩‍💻 Candidat :
- Crée un compte personnel avec CV / profil
- Parcourt les offres d’emploi disponibles
- Postule aux offres directement via l’interface
- Suit l’état de ses candidatures

Cette structure permet une gestion fluide et sécurisée des interactions entre les utilisateurs et renforce l’expérience globale de la plateforme.

🧕 Réalisé par Fatima-Zohra Zelmati

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
