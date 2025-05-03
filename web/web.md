# Web Portfolio

## Hogeschool

Ivm semester onderwijs op de hogeschool heb ik opdrachten van studenten nagekeken aangaande:

- HTML

- CSS

- Javascript

- Docker

## PHP

Ik heb verschillende php websites gemaakt, welke inmiddels op een na ([pikido.com](https://pikido.com/)) allemaal weer offline gehaald zijn.

## Wordpress

Ik heb ooit 3 wordpress boeken doorgenomen en vervolgens een geavanceerde **datingsite** gemaakt op basis van Wordpress (date vinden op basis van gezochte specs, op map aangeven waar kandidaten zich bevinden en ermee kunnen chatten, meertalig). Enfin, die heb ik uiteindelijk weer offline gehaald. Het was voornamelijk php programmeren.

## Docker

Ik heb online de "Comprehensive" Docker course gevolgd van "Code with Mosh". Sindsdien host ik al mijn services en websites in docker containers. 

### Amazon AWS

Eerst ook wel op **Amazon AWS** (Lightsail instances), maar nu alleen nog op een **Raspberri pi 4** bij mij thuis.

## Cloudflare, Let's encrypt

De https certificates laat ik gratis genereren via let's encrypt. Ik gebruik Cloudflare als gratis nameservice waar mijn Raspberri Pi 4 het (dynamische) ip nummer van mijn ziggo router periodiek aan doorgeeft.

## React + TypeScript, Context, Immer, Redux, Flask, Node

Ik heb verschillende react cursussen (o.a. wederom van "Code with Mosh" en Youtube tutorials)  gevolgd om daar ook wat gevoel voor te krijgen. Als kapstok project om deze frontend vaardigheden mee te oefenen, maakte ik een online versie van gomoku (5 op een rij), en wel in de volgende smaken:

- [Een versie met alleen **vanilla html, css en javascript**](https://www.pikido.com/gomoku/start) (en **eenvoudig flask backend** met AI code en koppeling naar een **mongo database**).
- Een variant daarvan waarbij de **flask backend op basis van blueprints** werkt (en dus op een overzichtelijke manier geshared kan worden door verschillende flask applicaties)
- Een variant waarbij het frontend met **"vanilla" React** gemaakt is.
- Een variant waarbij ook **Context** is gebruikt.
- [Een variant waarbij ook **Immer** en **Redux** zijn gebruikt](https://www.pikido.com/gomoku_react), en de mongo database via een **Node.js** server wordt bediend (maar de ai van de moves nog wel door een flask service wordt uitgevoerd).

## Reverse proxy

Ik gebruik een reverse proxy om op mijn server het verkeer naar de diverse services te channelen. Zo wordt mijn pikido.com in de basis gehost door een php server, maar worden subfolders ervan weer gehost door andere docker-containers (zoals flask en nginx).
