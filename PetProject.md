# <a name="5"></a>Pet Projects

[Zurück zur Übersicht](README.md)

<div class="page"/>

### Feb. 2024 - Heute

> _Entwicklung (Desing eingekauft bei [hibootstrap](https://hibootstrap.com/))_   
\- [streetsurfclub.ch](https://streetsurfclub.ch){:target="_blank"}

## Vereinswebsite StreetSurfClub Luzern
> Bereitstellen eines zeitgenössischen Headless Frontends mit Darkmode und 'Mobile First' - Ansatz für [Google Blogger](https://www.blogger.com/) 

|Einsatz|Technologie|
|-------|-----------|
|Frontend| Angular 19, Tailwind CSS - hosted auf [Netlify](https://www.netlify.com/) |
|Backend | [Google Blogger](https://www.blogger.com/)|

### Jun. 2023 - Heute

> _Entwicklung_   

## Campagn Mailer
> Massenmail- Versand für Newsletter- Subscriber via CSV Import in Python

|Einsatz|Technologie|
|-------|-----------|
|Scripting| Python |
|Backend | Mail / SMS Provider [Postmark](https://postmarkapp.com)|

### Jul. 2022 - Heute

> _Design & Entwicklung_   
\- [laundry-calendar.netlify.app](https://laundry-calendar.netlify.app){:target="_blank"}

## Waschküchen- Verwaltung Laundry-Calendar
> Teilen von knappen Ressourcen (zB. Haushaltgeräte im Mehrfamilienhaus) mit 'Mobile First' - Ansatz

|Einsatz|Technologie|
|-------|-----------|
|Frontend| Angular 19, Tailwind CSS, Angular Material - hosted auf [Netlify](https://www.netlify.com/) |
|Auth| Netlify Identity |
|Backend | .Net Core mit Signal R - hosted via Docker auf [Render](https://render.com/)|
|DB | Redis - hosted auf [Render](https://render.com/)|

### Okt. 2020 - Heute

> _Design & Entwicklung_    
\- [up.schlosswochen.ch](https://up.schlosswochen.ch/){:target="_blank"}

## Anmeldeportal Ferienangebot "Schlosswochen"
> Anmeldeportal im Darkmode mit Emailbestätigung

|Einsatz|Technologie|
|-------|-----------|
|Frontend| Angular 19, Bootstrap - hosted auf [Netlify](https://www.netlify.com/) |
|Backend | Serverless Functions - hosted auf [Netlify](https://www.netlify.com/) |
|DB | MongoDB - hosted auf MongoDB Atlas [mongodb](https://www.mongodb.com)|
|Mail / SMS Provider | [Postmark](https://postmarkapp.com)|


### Okt. 2019 - Heute

> _Design & Entwicklung_    
\- [schlosswochen.ch](https://www.schlosswochen.ch/){:target="_blank"}

## Website Ferienangebot "Schlosswochen"
> Website mit Newsletter- Sammlung

|Einsatz|Technologie|
|-------|-----------|
|Frontend| Angular 19, Tailwind CSS, Angular Material - hosted auf [Netlify](https://www.netlify.com/) |
|Backend | Markdown- Files - hosted auf [Github](https://github.com) |
|DB | MongoDB - hosted auf MongoDB Atlas [mongodb](https://www.mongodb.com)|



### Okt. 2019 - Heute

> _Entwicklung (Design gekauft bei [3rdwavemedia](https://themes.3rdwavemedia.com))_   
\- [petruschka.ch](https://www.petruschka.ch/){:target="_blank"}

## Website Figurentheater 'Petruschka' Luzern
> Website mit Backendanbindung und externem Ticketing

|Einsatz|Technologie|
|-------|-----------|
|Frontend| Angular 19, Bootstrap 5 - hosted auf [Netlify](https://www.netlify.com/) |
|Backend | Serverless Functions - hosted auf [Netlify](https://www.netlify.com/) |
|DB | MongoDB - hosted auf MongoDB Atlas [mongodb](https://www.mongodb.com)|
|Ticketing| Eventfrog, Datenabzug via .NET Core WebAPI nach MongoDB und Naturmuseum Luzern, Datenabzug via Python Script nach MongoDB |

### Okt. 2019 - Heute

> _Entwicklung (Design gekauft bei [3rdwavemedia](https://themes.3rdwavemedia.com))_   
\- [petruschka.ch](https://www.petruschka.ch/){:target="_blank"}

## Website Figurentheater 'Petruschka' Luzern
> Website mit Backendanbindung und externem Ticketing

|Einsatz|Technologie|
|-------|-----------|
|Frontend| Angular 19, Bootstrap 5 - hosted auf [Netlify](https://www.netlify.com/) |
|Backend | Serverless Functions - hosted auf [Netlify](https://www.netlify.com/) |
|DB | MongoDB - hosted auf MongoDB Atlas [mongodb](https://www.mongodb.com)|
|Ticketing| Eventfrog, Datenabzug via .NET Core WebAPI nach MongoDB und Naturmuseum Luzern, Datenabzug via Python Script nach MongoDB |








## Feb. 2017 - Heute

### Design & Entwicklung Webapplikation

> Neuentwicklung www.kinderkultur.ch als Webapplikation mit Datenbankanbindung mit dem Ziel, als eigenständiges CMS fungieren zu können. Noch nicht produktiv.

* Frontend: Browseranwendung
  * [TS](https://www.typescriptlang.org)- Framework: [Angular 6](https://angular.io/docs) mit [Ejected Angular Cli](https://github.com/angular/angular-cli/wiki/eject)  
  * Bundling: [Webpack 3.6](https://webpack.js.org)
  * CSS- Framework: [Bootstrap 4](https://getbootstrap.com) mit [SASS / SCSS](https://sass-lang.com)

* Backend: [ASP.NET Core 2.1](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-2.1) Web-API (REST)
  * CRUD & Patch
  * API Versioning
  * Authetifizierung via [.NET Core Identity](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-2.1&tabs=visual-studio%2Caspnetcore2x) und [JWT](https://tools.ietf.org/html/rfc7519)
  * Logging via [NLog](http://nlog-project.org)
  * [EntityFramework Core](https://docs.microsoft.com/en-us/ef/core/) auf [MariaDB](https://mariadb.org/)
  * [.Net MongoDB Driver](https://docs.mongodb.com/ecosystem/drivers/csharp/) auf [MongoDB](https://www.mongodb.com)
  * Swagger ([NSwag](https://docs.microsoft.com/en-us/aspnet/core/tutorials/getting-started-with-nswag?view=aspnetcore-2.1&tabs=visual-studio%2Cvisual-studio-xml))
  * Repository Pattern with Dependency Injection and ViewModels
  * [AutoMapper](http://automapper.readthedocs.io) via Dependency Injection
  
* Database: SQL & NOSQL
  * Content:  [MongoDB](https://www.mongodb.com) Entwicklung auf lokalem Server
  * Authentifizierung: [MariaDB](https://mariadb.org/) (MySQL-Derrivat), auf [Docker](https://www.docker.com)-Container

* Versionsverwaltung
    * [Git](https://git-scm.com) auf [GitHub- Repository](https://github.com/DonCorleone/KinderKultur_Docker)

* Enwicklungsumgebung Hardware
  * Apple MacBook Pro

* Entwicklungsumgebung Software:
  * MacOS 10.13 (High Sierra)
  * Visual Studio Code (TypeScript, HTML, SCSS, C#, MongoShell)
  * Postman (API-Testing)
  * Robo 3T (Mongo-DB)
  * Sequel Pro (Maria-DB)

* Produktivumgebung Hardware (Noch nicht online)
  * Synology Diskstation (Dockerfähiger Webserver mit RAID 2)
  
---

## Nov. 2015 - Heute

### Technisches Design, Umsetzung & Wartung Website

> Entwurf & Umsetzung responsive Website (Ohne Design)  
[www.kinderkultur.ch](http://www.kinderkultur.ch)

* Frontend:
  * [HTML5](https://www.w3.org/TR/html5/)
  * CSS3 mit [Bootstrap 3.6](http://bootstrapdocs.com/v3.3.6/docs/getting-started/)
* Backend: -
* Database: -

<div class="page"/>

[Übersicht](README.md)
