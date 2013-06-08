---
layout: post
published: true
title: Geek - Où je suis passé à Cloudflare
author_login: picsoung
author_email: nicolas.grenie@utbm.fr
dotclear_id: 63
date: 2010-10-06 06:24:00.000000000 +02:00
categories:
- Geekeries
tags: []
comments:
- id: 13
  author: picsoung
  author_email: me@nicolasgrenie.com
  author_url: http://nicolasgrenie.com
  date: 10/08/2010 07:29:45
  date_gmt: 2010-10-08 07:29:45.000000000 +02:00
  content: ! '<p>Edit : je viens à l''instant de tester l''efficacité du système,
    le site a été inaccessible pendant 1petite minute et un gentil message user-friendly
    avertissait l''utilisateur :)</p>'
---
<p><img src="/public/illus_billets/.cloudfare_homepage_s.jpg" alt="cloudflare home" style="float:right; margin: 0 0 1em 1em;" title="cloudfare home, oct. 2010" />Vous n’avez certainement rien remarqué et c’est bien normal… J'ai découvert Cloudflare après la lecture d'un <a href="http://fr.techcrunch.com/2010/09/30/techcrunch-disrupt-ce-qui-sest-passe-a-lautre-cote-de-latlantique-la-meilleure-start-up/?utm_source=feedburner&amp;utm_medium=feed&amp;utm_campaign=Feed%3A+francaistechcrunch+%28TechCrunch+en+Francais%29" hreflang="fr">article</a> de Techcrunch France à propos de la conférence Techcrunch Disrupt qui s'est déroulée du 27 au 29 septembre dernier à San Francisco. Le principe de ces trois jours de conférence est de réunir start-up et entrepreneurs du web afin de faire connaître les projets innovants en recherche de fonds. À cette occasion quelques boîtes françaises (<a href="http://dismoiou.fr/" hreflang="fr">Dismoiou</a>, <a href="http://www.boosket.com/en" hreflang="en">Boostket</a>, <a href="http://kwaga.com/" hreflang="fr">Kwaga</a>, <a href="http://www.stribe.com/" hreflang="fr">Stribe</a> et<a href="http://www.wozaik.com/bienvenue" hreflang="fr"> Wozaik</a>) avaient fait le voyage mais n'ont malheureusement pas remportées la récompense de 50 000 $ attribuée à la meilleure des 27 start-up sélectionnées.</p>


<p>C'est <a href="http://www.qwiki.com/" hreflang="en">Qwiki</a> qui s'est hissé sur la première marche du podium. Un service qui devrait révolutionner notre manière de consommer Internet. J'avoue ne pas avoir été spécialement bluffé…
Sur les autres marches on retrouvait <a href="http://www.pinger.com/content/int/" hreflang="en">Pinguer</a> qui édite des applications mobiles et<a href="https://www.cloudflare.com/home.html" hreflang="en"> Cloudflare</a> la fameuse application que j'ai adopté.</p>


<p>Je ne sais pas trop d'ailleurs pourquoi j'ai passé le pas. C'est assez contradictoire j'ai tendance à pas écrire souvent ici mais par contre j'adore ajouter des fonctionnalités. C'est comme ça que j'ai installé les outils de statistiques Google Analytics au début du mois de septembre et Xiti un peu plus tard.</p>


<p>Cloudflare s'annonce comme quelque chose qui doit accélérer notre site. Le bourrer d'amphét' pour qu'il explose le 100m du chargement. Après l'installation j'ai effectivement eu l'impression que ça allait plus vite. Comme à chaque fois cela reste subjectif. On m'aurait dit ça envoie un message aux extraterrestres je l'aurais peut-être cru.</p>


<p>Quoi qu'il en soit c'est très facile d'installation. Il suffit de créer un compte en renseignant l'adresse de son site. Ils s'occupent de trouver les domaines liés et de demander lesquels on veut faire bénéficier de la "supercharge". Pour ma part je l'ai activé sur tout mon domaine nicolasgrenie.com et ses sous domaines pro et blog. On a plus qu'à changer les DNS de son domaine pour les faire pointer chez Cloudflare. Et paf ! C’est fini, à nous la vitesse !</p>


<p><img src="/public/illus_billets/.cloudfare_dashboard_s.jpg" alt="cloudflare dashboard" style="float:left; margin: 0 1em 1em 0;" title="cloudflare dashboard, oct. 2010" />L'idée est simple ils jouent les intermédiaires pour empêcher les vilains visiteurs de mettre le barouf chez vous. Comment&nbsp;? Si quelqu'un accède trop de fois d'un coup à une même page on lui demande de remplir un captcha. Comme c'est un robot y peut pas… L'IP est donc mis en zone de quarantaine, il sera demandé une IP à chaque fois qu'elle essaye de se connecter.</p>


<p>D'après les stats fournies pour l'instant après 5 jours d'utilisation cela m'a permis d'arrêter 4 bots spammeurs, d'économiser 1 854 requêtes, 27MB de bande passante, et les pages se chargent en 0.27sec au lieu de 0.37 \o/ Je suis un homme heureux :)</p>


<p>L'avantage de tout ça c'est que le service est Gratuit, ce qui est plutôt pas mal pour ce genre de service. Comme beaucoup de sites actuellement le système est de type Freemium il faudra donc payer une petite obole pour bénéficier d'autres services.</p>


<p>J'ai donc apprécié la simplicité d'installation, le côté user-friendly de l'interface du Dashboard ainsi que les services (sécurité, accélération, disponibilité H24 de mon site).
On notera également que les concepteurs de Cloudflare font parti du projet Project Honey Pot qui est une espèce de grosse base de données temps réel des spammeurs mis à jour automatiquement grâce aux webmasters qui ont installé ce service sur leur site.</p>


<p>À tester donc amis webmestres !</p>


<p>PS&nbsp;: marre de flickr… j'a installé un plugin gallery au blog donc pour sûr des photos de l'automne américain arrivent prochainement</p>
