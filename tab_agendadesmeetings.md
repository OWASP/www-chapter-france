---
title: agendadesmeetings
displaytext: Agenda des meetings
layout:  null
tab: true
order: 2
tags: france
---

Les meetings ont lieu sur une base minimale trimestrielle et se déroulent généralement dans une salle mise à disposition par un sponsor.


# 2023

{% assign page_event_2023 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'event/2023'" %}

{% for page in page_event_2023 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}

# 2022

{% assign page_event_2022 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'event/2022'" %}

{% for page in page_event_2022 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}

# 2021

{% assign page_event_2021 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'event/2021'" %}

{% for page in page_event_2021 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}


# 2020

{% assign page_event_2020 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'event/2020'" %}

{% for page in page_event_2020 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}

# 2019

## Meetup

{% assign page_event_2019 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'event/2019'" %}

{% for page in page_event_2019 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}

## Partenaire

* [Forum de Cybersecurite France-Israel](https://clusif.fr/conferences/forum-de-cybersecurite-france-israel-usa-2019/)
* GSDays


# 2018

Presentation des nouveautés du OWASP Top10 2017 au Forum ADN Ouest le 27 Septembre 2018

### [FORUM DE CYBERSECURITE France-Israël 2018](https://www.eventbrite.fr/e/billets-forum-de-cybersecurite-france-israel-2018-43316132719)

*Nous sommes partenaires de cet événement et seront présent. N'ésitez
pas à venir nous voir*

La Chambre de Commerce France-Israël, en partenariat avec la Chambre de
Commerce et d'Industrie Paris Ile-de-France, organisent le mercredi 14
mars 2018 au Palais Potocki, [27 avenue de
Friedland](https://maps.google.com/?q=27+avenue+de+Friedland&entry=gmail&source=g) à
Paris, le 12ème forum de cybersécurité France-Israël-USA de 8h30 à
18h00.

Le thème de la journée porte sur les solutions cyber de nouvelle
génération. Conférences en plénière le matin suivies d'un networking
lunch, puis de rencontres d'affaires l'après-midi de 14h00 à18h00 avec
série non-stop d'ateliers ouverts au public professionnel, pour
présenter toutes les solutions.

12 sociétés cyber, sélectionnées parmi les meilleures en Israël,
participent au forum. C'est une occasion unique de les rencontrer pour
les spécialistes français qui n'ont pas pu faire le voyage au salon
Cybertech TLV en janvier dernier. Le forum de cybersécurité
France-Israel offre une opportunité ciblée, d'anticiper les tendances du
marché international de la cybersécurité.

Les invités d'honneur sont Markus Braendle, Head of Cybersecurity at
Airbus Cyber Security et Nadav Zafrir, CEO de Team8. Nadav Zafrir est le
fondateur du cyber command israélien et l'ancien patron de l'unité 8.200

Inscription sur EventBrite :
<https://www.eventbrite.fr/e/billets-forum-de-cybersecurite-france-israel-2018-43316132719>

### GSDays 2018

*Nous sommes partenaires des [GSDays 2018](http://www.gsdays.fr/) et
seront présents. Venez nous rencontrer*

### GSDays 2016

Nous sommes partenaires des [GSDays 2016](http://www.gsdays.fr/).
[L'appel a communication est en
ligne](http://www.gsdays.fr/373/actualites/appel-a-communication-2016/)

### PODCAST

[NolimitSecu](http://www.nolimitsecu.fr/) nous a fait l'honneur d'une
interview a retrouver ici : [PODCAST OWASP de
NolimitSecu](http://www.nolimitsecu.fr/owasp/)

### GSDays 2015

Nous serons présent aux [GSDays](http://www.gsdays.fr), et parlerons de
code sécurisé avec le projet OWASP SonarQube . Les slides sont en ligne
[ici](http://www.slideshare.net/SebastienGioria/la-quete-du-code-source-fiable-et-scuris-gsdays-2015)

# Meetings 2016

## Mars 2016

**Date** : 17 Mars 2016

**`Lieu`**` : EPITECH Nantes : `<http://goo.gl/maps/DCQ1a>` - Nantes Java User Group `
**`Horaire`**` : 19h - 20h30 `

`'''Présentation 1 ''' 19h00 REX: Audit de sécurité d'applications Java`
**`Durée``   ``:``   ``20min`**
**`Speakers``   ``:``   ``Marc``   ``Lebrun`**

`'''Présentation 2 : '''19h30 Secure Coding Live !`
`'''Durée : 1h ''''`
**`Speakers``   ``:``   `[`Sebastien``
 ``Gioria`](https://www.owasp.org/index.php/User:SebastienGioria)**

## Juillet 2016

**`Date`**` : `[`7``   ``Juillet``
 ``2016`](/www-pdf-archive/2016-07-07-Meeting_OWASP_Juillet.pdf)
**`Lieu`**` : DragonFly - 215 avenue Georges Clemenceau NANTERRE - Bus 258 depuis la Défense, arrêt Les Fontenelles. `

Le Lounge est en entrant à droite dans le bâtiment, au rez-de-chaussée.

**`Horaire`**` : 18h30-22h`
**`Présentation``   ``1`**` : `[`Owasp``   ``security``   ``Shepherd``
 ``Par``   ``Tarik``   ``El``
 ``Aouadi`](/www-pdf-archive/OWASP-fr_Meeting_Shepherd-demo.pdf)
**`Présentation``   ``2`**` : `[`Bug``   ``Bounty``   ``-``   ``État``
 ``de``   ``l’Art``   ``Par``   ``Yassir``   ``Kazar``
 ``(YogoSha)`](/www-pdf-archive/Yogosha-OWASP.pdf)

Le meeting est disponible sur Youtube :
<https://www.youtube.com/watch?v=oko2_zz1CWQ>

Merci a [DragonFly](https://www.intrinsec.com/) pour la projection et
l'enregistrement live

Liens pour les slides uniquement :

</www-pdf-archive/2016-07-07-Meeting_OWASP_Juillet.pdf>

</www-pdf-archive/OWASP-fr_Meeting_Shepherd-demo.pdf>

</www-pdf-archive/Yogosha-OWASP.pdf>

## Septembre 2016

**Date** :

**`Lieu`**` : A définir - Paris `
**`Horaire`**` : 18h30-22h`
**`Présentation``   ``1`**` : A définir`
**`Présentation``
 ``2`**` : Projet OWASP (a définir) par `[`Sebastien``
 ``Gioria`](mailto:sebastien.gioria@owasp.org)

## Decembre 2016

**Date** :

**`Lieu`**` : A définir - Paris `
**`Horaire`**` : 18h30-22h`
**`Présentation``   ``1`**` : A définir`
**`Présentation``
 ``2`**` : Projet OWASP (a définir) par `[`Sebastien``
 ``Gioria`](mailto:sebastien.gioria@owasp.org)
**`News``   ``OWASP``   ``de``   ``l'année`**

# Meetings 2015

## Decembre 2015

**`Date`**` : 3 Décembre 2015`
**`Lieu`**` : A définir- Paris `
**`Horaire`**` : 18h30-22h`
**`Sponsor`**` : `[`Advens`](http://www.advens.fr)` `
**`Présentation``   ``1`**` : A définir`
**`Présentation``
 ``2`**` : Projet OWASP (a définir) par `[`Sebastien``
 ``Gioria`](mailto:sebastien.gioria@owasp.org)
**`News``   ``OWASP``   ``de``   ``l'année`**

## Septembre 2015

**`Date`**` : 18 Septembre 2015`
**`Lieu`**` : Java User Group, Summer Camp - La Rochelle `
**`Horaire`**` : 17h-18h`
**`Présentation`**` : `[`42``   ``minutes``   ``to``   ``secure``
 ``your``
 ``code`](http://www.slideshare.net/SebastienGioria/42-minutes-to-secure-your-code)

## Mars 2015

**`Date`**` : 19 Mars 2015`
**`Lieu`**` : ChtiJug Lille`
**`Horaire`**` : 19h-22h`
**`Présentation`**` : `[`Secure``   ``Coding``   ``for``   ``Java,``
 ``une``
 ``introduction`](http://www.slideshare.net/SebastienGioria/secure-coding-for-java-une-introduction)

# Meetings 2014

## Juin 2014

**`Date`**` : 5 Juin 2014 `
**`Lieu`**` : Mozilla Paris, 16 Bis Boulevard Montmartre, Paris 75009, France`
**`Horaire`**` : 19h à 22h`
**`Présentation``   ``1`**` : `[`Etat``   ``de``   ``la``   ``Menace,``
 ``et``   ``actualités``   ``de``   ``la``   ``sécurité``
 ``Web`](https://fr.slideshare.net/SebastienGioria/2014-0605mozillaafup-35696709)` - `[`Podcast`](https://air.mozilla.org/talks-owasp-afup-firefoxos-security-mozilla-firefoxos-what-is-owasp-by-sebastien-gioria/)` - `[`Sebastien``
 ``Gioria`](mailto:sebastien.gioria@owasp.org)
**`Présentation``   ``2`**` : `[`La``   ``sécurité``   ``avec``
 ``PHP`](https://fr.slideshare.net/hellosct1/la-securiteetphp)` - `[`Podcast`](https://air.mozilla.org/talks-owasp-afup-firefoxos-security-mozilla-firefoxos-security-in-php-by-christophe-villeneuve/)` - Christophe Villeneuve AFUP `
**`Présentation``
 ``3`**` : Firefox OS - `[`Podcast`](https://air.mozilla.org/talks-owasp-afup-firefoxos-security-mozilla-firefoxos-application-security-by-stephanie-ouillon/)` - Stéphanie Ouillon / Mozilla`

## OWASP European Chapter Tour 2013, Sophia-Antipolis, France, 24 Juin 2013

**`Présentation`**` : "`[`Synthèse`](https://www.owasp.org/images/1/10/Synth%C3%A8se.ppt)`"`
**`Présentation`**` : "`[`Introduction`](/www-pdf-archive/EuTour_-_Owasp_Eurecom.pdf)`"`
**`Présentation`**` : "`[`The``   ``Role``   ``of``   ``Web``
 ``Hosting``   ``Providers``   ``in``   ``Detecting``   ``Compromised``
 ``Websites`](/www-pdf-archive/EuTour-providers.pdf)`"`
**`Présentation`**` : "`[`Behind``   ``the``   ``Scenes``   ``of``
 ``Web``
 ``Attacks`](/www-pdf-archive/EuTour-webhoneypots.pdf)`"`
**`Présentation`**` : "`[`Logic``   ``Vulnerabilities``   ``in``
 ``eCommerce``   ``Web``
 ``Applications`](/www-pdf-archive/Pellegrino-OWASP_EUTour2013.pdf)`"`

**`Résumé`**` :  `

Meeting de grande qualité, présentations très intéressantes. Nous
remercions EURECOM pour avoir eu l'amabilité d'héberger le meeting,
ainsi que les speakers pour leur prestation très appréciée\!

**`Speaker`**` : Aurélien Francillon: Maître de Conférences, Département "Réseaux et sécurité", EURECOM`
**`Speaker`**` : Davide Balzarotti: Maître de Conférences, Département "Réseaux et sécurité", EURECOM`
**`Speaker`**` : Giancarlo Pellegrino: Doctorant, Département "Réseaux et sécurité", EURECOM et chercheur, SAP AG EURECOM`
**`Speaker`**` : Ely de Travieso: Owasp France, Directeur Phonesec`
**`Speaker`**` : Maurizio Abbà: Etudiant en Master, EURECOM`
**`Speaker`**` : Davide Canali: Doctorant, Département "Réseaux et sécurité", EURECOM`

## Looking Forward… and Beyond, Distinctiveness Through Security Excellence

**`Présentation`**` : "`[`Looking``   ``Forward…``   ``and``
 ``Beyond`](https://www.owasp.org/images/5/50/Looking_Forward%E2%80%A6_and_Beyond.pptx)`"`
**`Résumé`**` :  `

Here is a presentation I gave in Sept for a big Software maker in an
internal meeting. This presentation aims to be re-used at your
convenience depending the needs / your context. Designed into 3 parts,
this presentation is / could be useful for local Chapters, any Security
Awareness purposes, or people and firms interested about OWASP and
willing to join the Foundation as Member. The first 2 parts are more an
update for those who are not yet familiar with OWASP, the 3rd part being
more specific because about a hot topic that is gaining importance in
the context of Application Security. 1st part is about OWASP. 2nd part
is an update about the main OWASP Projects and Reboot. 3rd part is about
Legal, the evolution of the legal framework, with a focus on the
question "Developers, Software makers held liable for code?" I hope this
helps anyway. Enjoy and feel free to email me, all comments welcome\!

**`Speaker`**` : Ludovic Petit `

## 28 Mars 2012 Meeting du premier trimestre

**`Lieu`**` : Groupe Y Audit - 69 Rue de la Boëtie - 75 Paris - Métro Saint Philippe du Roule `
**`Horaire`**` : Ouverture des portes 17h30 - Début de la présentation 18h`
**`Présentation`**` : "`[`Top``   ``Ten``   ``Web``
 ``Defenses`](https://www.owasp.org/images/6/6d/Developer_Top_Ten_Core_Controls_v4.1.pptx)`"`
**`Résumé`**` :  `

Application programmers need to learn to code in a secure fashion if we
have any chance of providing organizations with proper defenses in the
current threatscape. This talk will discuss the 10 most important
security-centric computer programming techniques necessary to build
low-risk web-based applications. Access Control is a necessary security
control at almost every layer within a web application. This talk will
also detail several of the key access control anti-patterns commonly
found during website security audits. These access control anti-patterns
include hard-coded security policies, lack of horizontal access control,
and "fail open" access control mechanisms. In reviewing these and other
access control problems, we will discuss and design a positive access
control mechanism that is data contextual, activity based, configurable,
flexible, and deny-by-default - among other positive design attributes
that make up a robust web-based access-control mechanism.

**`Speaker`**` : Jim Manico `

Jim Manico is the VP of Security Architecture at WhiteHat Security. Jim
has been a web application developer since 1997. He has also been an
active member of OWASP since 2008 supporting projects that help
developers write secure code.

**`Enregistrement``   ``en``   ``ligne``
 ``sur`**` : `<http://201203owaspfr.eventbrite.com/>

## 7 et 8 Février 2012 - [Techdays Microsoft 2012](http://www.microsoft.com/france/mstechdays/)

Sébastien présentera un talk sur [HTML5et la
Sécurité](http://www.microsoft.com/france/mstechdays/programmes/parcours.aspx?SessionID=62e02774-6045-4be8-80ff-8332a793ad4f)
le 7 Février 2012 à 17h30. Plus d'informations sur la page dédiée aux
TechDays Microsoft 2012. ==

## 6 Janvier 2012 - Nouveau Groupe de Travail sur la Sécurité des Web Services au [CLUSIF](http://www.clusif.fr)

Dans la continuité du Groupe de Travail sur la Sécurité des Application
Web initialement créé en 2009, le CLUSIF a lancé un nouveau groupe de
travail autour de la sécurité des WebServices. N'hésitez pas à
participer si vous êtes intéressés. Le CLUSIF recherche des utilisateurs
pour ce groupe de travail et des personnes en environnements Microsoft
pour disposer d'un panel le plus large possible pour ce document

Contact : [Sébastien Gioria](mailto:sebastien.gioria@owasp.org)

## 19 Décembre 2011 - Publication du deuxième document du [CLUSIF](http://www.clusif.fr) sur la Sécurité des Applications Web

Le CLUSIF a publié son deuxième document sur la [Défense en profondeur
des applications
Web](http://www.clusif.fr/fr/production/ouvrages/pdf/CLUSIF-2011-Defense-en-profondeur-des-applications-Web.pdf).
Ce document fait suite au [premier document publié
en 2009](http://www.clusif.fr/fr/production/ouvrages/pdf/CLUSIF-2009-Securite-des-applications-Web.pdf)

## 15 Décembre 2011 Conférence du [CLUSIF](http://www.clusif.fr) sur la [sécurité des applications Web](http://www.clusif.fr/fr/infos/event/#conf111215)

Le CLUSIF a présenté la conférence Sécurité des Applications Web le
jeudi 15 décembre 2011 au cercle National des Armées. Le programme était
:

  - Mise en place d'une politique de sécurité applicative : retour
    d'expérience d'un RSSI par Philippe LARUE - Responsable Sécurité -
    [CBP](http://www.cbp-prevoyance.com/)
  - Revue de code source, ou test sécurité applicatif, quel est le plus
    efficient pour évaluer un niveau de sécurité applicatif ? par
    Sébastien GIORIA - Consultant Senior [Groupe
    Y](http://www.groupey.fr) et leader du chapitre Français de
    [l'OWASP](https://www.owasp.org) - OWASP France
  - Les enjeux réglementaires de la protection des informations en ligne
    par Garance MATHIAS - Avocat - Cabinet d'Avocats

Les présentations sont disponibles sur le site du
[CLUSIF](http://www.clusif.fr), les vidéos de l'intervention seront
aussi disponible.

## 2 Décembre 2011 - [OWASP BeNeLux 2011 Conference - University of Luxembourg](OWASP_BeNeLux_2011_Conference_-_University_of_Luxembourg )

Ludovic had a talk about "[WebApp Security and Legal
aspects](https://www.owasp.org/index.php/BeNeLux_OWASP_Day_2011#tab=Conference.2C_December_2nd)"
on Dec 2.

  - **Overview**
      - This presentation aims to be used by anybody willing to spread
        the voice of OWASP. See this as an Awareness session.
      - Use it and use it again.
      - Try to open your mind, just met me know if I can help.

<!-- end list -->

  - **Abstract Title:
    "\[<https://www.owasp.org/images/5/55/Do_you>..._Legal_-_OWASP_BeNeLux_Day_-_2_Dec_2011.pptx
    Do you... Legal?\]"**
      - The OWASP core mission is to make application security visible,
        so that people and organizations can make informed decisions
        about true application security risks. However, if you do not
        pay enough attention to many aspects of Legal compliance, you'll
        see why Web Application Security is somehow linked to Legal and
        Regulatory aspects as well as... Corporate Responsability, so
        yours. Who is accountable for what, what about each other's
        responsibility? Nowadays, the legal constraints oblige us to
        comply via technical means, whatever the local framework, and
        this is specially true for Web Application Security, many
        sensitive informations having to be handled through these web
        interfaces. A such, what do you think about your Security Policy
        compliance with your local Legal framework? Compliant? Sure?
        Really? Interesting isn't it? Let's have a talk about this.

### [EUROPE - ENISA’s Who-is-Who Directory on Network and Information Security](EUROPE_-_ENISA’s_Who-is-Who_Directory_on_Network_and_Information_Security )

We are pleased to announce that OWASP France is part of the [ENISA’s
Who-is-Who
Directory](http://www.enisa.europa.eu/publications/studies/who-is-who-directory-2011).

The ENISA is the European Network and Information Security Agency. [The
ENISA Who-is-Who Directory on Network and Information
Security 2011](http://www.enisa.europa.eu/publications/studies/who-is-who-directory-2011/at_download/fullReport)
contains information on NIS stakeholders, such as national and European
authorities and NIS organisations, contact details, websites, and areas
of responsibilities or activities. This Directory serves as the "yellow
pages" of Network and Information Security (NIS) in Europe. As such, it
is a useful tool for those working closely with NIS issues in Europe.

# Chapter Meeting 2014

## Juin 2014

**`Date`**` : 5 Juin 2014 `
**`Lieu`**` : Mozilla Paris, 16 Bis Boulevard Montmartre, Paris 75009, France`
**`Horaire`**` : 19h à 22h`
**`Présentation``   ``1`**` : `[`Etat``   ``de``   ``la``   ``Menace,``
 ``et``   ``actualités``   ``de``   ``la``   ``sécurité``
 ``Web`](https://fr.slideshare.net/SebastienGioria/2014-0605mozillaafup-35696709)` - `[`Podcast`](https://air.mozilla.org/talks-owasp-afup-firefoxos-security-mozilla-firefoxos-what-is-owasp-by-sebastien-gioria/)` - `[`Sebastien``
 ``Gioria`](mailto:sebastien.gioria@owasp.org)
**`Présentation``   ``2`**` : `[`La``   ``sécurité``   ``avec``
 ``PHP`](https://fr.slideshare.net/hellosct1/la-securiteetphp)` - `[`Podcast`](https://air.mozilla.org/talks-owasp-afup-firefoxos-security-mozilla-firefoxos-security-in-php-by-christophe-villeneuve/)` - Christophe Villeneuve AFUP `
**`Présentation``
 ``3`**` : Firefox OS - `[`Podcast`](https://air.mozilla.org/talks-owasp-afup-firefoxos-security-mozilla-firefoxos-application-security-by-stephanie-ouillon/)` - Stéphanie Ouillon / Mozilla`

# Chapter Meetings 2013

## Q1 2013

**`Date`**` : 7 février 2013`
**`Lieu`**` : Gemalto - Salle Plazza, 6 rue de la Verrerie, 92197 Meudon-sur-Seine `
**`Horaire`**` : 18h30 à 21h`
**`Présentation`**` : Update sur les `**`Projets``
 ``OWASP`**`, Ludovic`
**`Présentation`**` : `**`Evolution``   ``du``   ``Cadre``   ``Légal``
 ``-``   ``Developers,``   ``Software``   ``makers``   ``held``
 ``liable``   ``for``
 ``code?`**[`1`](https://www.owasp.org/images/2/2a/Chapter_Meeting_OWASP_France_-_7_Feb_2013.pdf)` Ludovic`
**`Présentation`**` : `**`Données``   ``personnelles:``   ``le``
 ``nouveau``   ``projet``   ``de``   ``règlement``
 ``européen`**[`2`](http://www.donneespersonnelles.fr/donnees-personnelles-le-nouveau-projet-de-reglement-europeen)`, Thiébaut Devergranne`
**`Breaking``   ``News`**` : Présentation de l`**`'OWASP``   ``France``
 ``Day`**` que  nous souhaitons organiser en mars, Ludovic & Sébastien`
**`Appel``   ``à``   ``contribution`**` : `**`Traduction``   ``OWASP``
 ``Top``   ``Ten``   ``2013`**`, Ludovic & Sébastien`
**`Update`**` : `**`Relations``
 ``Partenaires`**` & `**`Adhésions`**`, Ely de Travieso`

Pour nous accompagner lors de ce meeting, Thiébaut Devergranne, docteur
en droit et consultant. Thiébaut travaille en droit des nouvelles
technologies depuis plus de 10 ans, dont 6 passés au sein des services
du Premier Ministre.

`'`***`Speakers`***`' : Ludovic Petit, Sébastien Gioria, Ely de Travieso, Thiébaut Devergranne`
**`Enregistrement``   ``en``   ``ligne``
 ``ici`**` : `<https://www.eventbrite.com/event/4615236296>

**`Date`**` : 12 mars 2013`
**`Lieu`**` : Solucom, Tour Franklin, 100-101 Terrasse Boieldieu, 92042 Paris La Défense `
**`Horaire`**` : 09h00 à 12h30`
**`Présentation`**` : Secure Coding (en Anglais), Jim Manico`
**`Présentation`**` : Sécurité Applicative: l’Organisation, clé de la réussite!, Gérôme Billois`
**`Présentation`**` : OWASP News & Update, Ludovic Petit & Sébastien Gioria`
**`Appel``   ``à``   ``contribution`**` : `**`Traduction``   ``OWASP``
 ``Top``   ``Ten``   ``2013`**`, Ludovic & Sébastien`

**`Présentation``   ``globale`**` : `**`Chapter``   ``Meeting``
 ``OWASP``   ``France``   ``12``
 ``Mars`**[`3`](https://www.owasp.org/images/2/2d/Chapter_Meeting_OWASP_France_12_Mars.pdf)

Les sujets abordés par Jim Manico: **Authentication Best Practices for
Developers:** This module will discuss the security mechanisms found
within an authentication (AuthN) layer of a web application. We will
review a series of historical authentication threats. We will also
discuss a variety of authentication design patterns necessary to build a
low-risk high-security web application. Session management threats and
best practices will also be covered. This module will include several
technical demonstrations and code review labs.

**Access Control Design Best Practices:** Access Control is a necessary
security control at almost every layer within a web application. This
talk will discuss several of the key access control anti-patterns
commonly found during website security audits. These access control
anti-patterns include hard-coded security policies, lack of horizontal
access control, and "fail open" access control mechanisms. In reviewing
these and other access control problems, we will discuss and design a
positive access control mechanism that is data contextual, activity
based, configurable, flexible, and deny-by-default - among other
positive design attributes that make up a robust web-based
access-control mechanism.

`'`***`Speakers`***`' : Jim Manico, Gérôme Billois, Ludovic Petit, Sébastien Gioria`
**`Enregistrement``   ``en``   ``ligne``
 ``obligatoire`**` : `<http://owaspfrance12mars2013.eventbrite.com/>

# Appel à contribution OWASP France

Ici seront relayés les différents appels à contributions du Chapitre
(Sponsors, talks, etc.).

# Appel à contributions externes

Ici seront relayés les appels à contributions que nous estimons
interessants pour le Chapitre.

# Meetings 2012

## Q1 2012

**`Date`**` : 28 Mars 2012`
**`Lieu`**` : Groupe Y Audit - 69 Rue de la Boëtie - 75 Paris - Métro Saint Philippe du Roule `
**`Horaire`**` : Ouverture des portes 17h30 - Début de la présentation 18h`
**`Présentation`**` : Web Application Access Control Design Excellence`
**`Résumé`**` : Access Control is a necessary security control at almost every layer within a web application. `
`                   This talk will discuss several of the key access control anti-patterns commonly found during `
`                    website security audits. These access control anti-patterns include hard-coded security policies, `
`                    lack of horizontal access control, and "fail open" access control mechanisms. In reviewing these`
`                    and other access control problems, we will discuss and design a positive access control mechanism `
`                    that is data contextual, activity based, configurable, flexible, and deny-by-default - among other`
`                    positive design attributes that make up a robust web-based access-control mechanism.`
**`Speaker`**` : Jim Manico`
**`Enregistrement``   ``en``   ``ligne``
 ``ici`**` : `<http://201203owaspfr.eventbrite.com/>

## Q2 2012

  - Date : To be defined
  - Time : To be defined
  - Venue : Groupe Y Audit - 69 Rue de la Boëtie - 75008 Paris
  - Program :
      - Talk 1 :
          - Lang :
          - Speaker bio

<!-- end list -->

  -   - Talk 2 :
          - Speaker bio
          - Lang :

## Q3 2012

  - Date : To be defined
  - Time : To be defined
  - Venue : Groupe Y Audit - 69 Rue de la Boëtie - 75008 Paris
  - Program :
      - Talk 1 :
          - Lang :
          - Speaker bio

<!-- end list -->

  -   - Talk 2 :
          - Speaker bio
          - Lang :

## Q4 2012

  - Date : To be defined
  - Time : To be defined
  - Venue : Groupe Y Audit - 69 Rue de la Boëtie - 75008 Paris
  - Program :
      - Talk 1 :
          - Lang :
          - Speaker bio

<!-- end list -->

  -   - Talk 2 :
          - Speaker bio
          - Lang :

# 2011 Meetings

### [May 2011 - Paris Meeting](May_2011_-_Paris_Meeting )

\[Logo to be placed here\]

We are honored to welcome **Jim Manico** during his European Tour in the
Netherlands, Belgium and France.

  - **Overview**
      - Apart from OWASP's Top 10, most OWASP Projects are not widely
        used and understood. In most cases this is not due to lack of
        quality and usefulness of those Document & Tool projects, but
        due to a lack of understanding of where they fit in an
        Enterprise's security ecosystem or in the Web Application
        Development Life-cycle.
      - This course aims to change that by providing a selection of
        mature and enterprise ready projects together with practical
        examples of how to use them.
      - The course will be very practical where demonstration and
        hands-on exercises will be provided for the tools covered.
      - If you are interested in participating in the hands on portion
        of the course, please bring a laptop.

<!-- end list -->

  - **Abstract Title: "[The Ghost of XSS Past, Present and Future. A
    Defensive
    Tale](https://www.owasp.org/images/f/f4/Future_of_XSS_v4.pptx)"**
      - This talk will discuss the past methods used for XSS defense
        that were only partially effective. Learning from these lessons,
        will will also discuss present day defensive methodologies that
        are effective, but place an undue burden on the developer. We
        will then finish with a discussion of future XSS defense
        mythologies that shift the burden of XSS defense from the
        developer to various frameworks. These include auto-escaping
        template technologies, browser-based defenses such as Content
        Security Policy, and Javascript sandboxes such as the Google
        CAJA project and JSReg.

<!-- end list -->

  - **Speaker**
      - **Jim Manico** is a managing partner of Infrared Security with
        over 15 years of professional web development experience. Jim is
        also the Chair of the OWASP Connections Committee, one of the
        Project Managers of the OWASP ESAPI Project, a participant and
        manager of the OWASP Cheatsheet series, the Producer and host of
        the OWASP Podcast Series, the Manager of the OWASP Java HTML
        Sanitizer project and the manager of the OWASP Java Encoder
        project. When not OWASP'ing, Jim lives on of island of Kauai
        with his lovely wife Tracey.

<!-- end list -->

  - **Date**
      - May 24, 2011

<!-- end list -->

  - **Venue**
      - Paris

<!-- end list -->

  - **Registration**
      - [Click
        here](http://www.regonline.com/Register/Checkin.aspx?EventID=971375)

## 26 Avril 2011

**Le 26 Avril 2011 dans les locaux de [GROUPE
Y](http://www.groupey.fr/nos-cabinets-paris.html) :**

  - 9:00:
    [Introduction](https://www.owasp.org/images/2/2f/Agenda_26th_April_2011.pptx)
    - **Ludovic Petit** & **Sébastien Gioria**
  - 9:30: [OpenSAMM](https://www.owasp.org/images/3/36/OPENSAMM2.pptx) -
    **Antonio Fontes** (Chapter Leader OWASP Geneva)
  - 11:00: [OWASP Cloud Top 10
    Project](https://www.owasp.org/images/c/cf/OWASP_Cloud_Top_10.pptx)
    - **Ludovic Petit** (Chapter Leader OWASP France & OWASP Global
    Education Committee Member)
  - 11:45: [OWASP
    ESAPI](https://www.owasp.org/images/5/5c/ESAPI_Swingset_talk_at_Paris.ppt)
    - **Fabio Cerullo** (Chapter Leader OWASP Ireland & Global Education
    Committee)
  - 14:15: [OWASP Testing
    Guide](https://www.owasp.org/images/3/38/OWASP_Testing_Guide.pptx) -
    **Sébastien Gioria** (French Chapter Leader & OWASP Global Education
    Committee Member)
  - 15:15: [OWASP 02 Platform - Live Session](http://o2platform.com) -
    **Dinis Cruz** (OWASP O2 Project Leader)
  - 16:30: [OWASP Code
    Review](https://www.owasp.org/images/9/96/OWASP-Paris2011-VV-CodeReview.pdf)
    - **Victor Vuillard**

# 2009 Meetings

**Le 6 Mai 2009 à 17h30 à [L'EPITECH](http://www.epitech.eu) :**

  - 17h30 : Accueil des participants
  - 18h - 18h 15 : [Welcome et overview of
    agenda](http://www.owasp.org/images/d/dc/OWASP_Paris_Meeting_-_May_2009.pdf)
    **(Board OWASP France)**
  - 18h30 - 19h : [Attaques sur les Web
    Services](http://www.owasp.org/images/6/6b/2009-05-06-OWASPFR-WebServices.pdf)
    - **Renaud Bidou**
  - 19h15 - 19h45 : [Software Security Initiatives in the Real
    World](http://www.owasp.org/images/8/82/2009-05-06-OWASPFR-OpenSAM.pdf)
    - **Claudio Merloni**
  - 20h : Close

A propos des Speakers :

'**'Renaud Bidou :** ''Directeur Technique de DenyAll. Il travaille
depuis plus de 10 ans dans la sécurité et a publié de nombreux articles
et white-papers touchant à des sujets aussi variés que les dénis de
service, les portknockers, les botnets, la mise en place d’un SOC,
l’analyse graphique d’attaques ou encore les techniques de
contournements.

'''''Claudio Merloni : '''''Claudio Merloni est Software Security
Consultant chez Fortify Software. Ses expériences dans le domaine de la
sécurité embrassent la sécurité applicative, revue de code,
architectures sécurisées, analyse des risques, conformité, test de
sécurité à niveau réseau, système et applicatif, monitoring, contrôle
d'accès. Il a participé a plusieurs conférences, entre lesquelles
BlackHat et CONFidence.

**Le Lieu : EPITECH**

Amphi 2

14-16 rue Voltaire

94276 Kremlin Bicêtre Cedex

*Moyens d'accès Métro*

  - ligne 7 : Porte d'Italie

*Bus*

  - ligne 47, 125, 131, 185 : Roger Salengro
  - ligne 186 : Pierre Brossolette

*Voiture*

  - périphérique : sortie Porte d'Italie

# Translation effort

  - The **OWASP TOP Ten 2010 in French** is
    [available](http://owasptop10.googlecode.com/files/OWASP%20Top%2010%20-%202010%20French.pdf)
  - 2010-08-30 : La version française du Top 10 2010 est disponible
    [4](http://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project)
  - 2008-02-15 : Le Top10 2007 est en version Française [Format
    PDF](https://www.owasp.org/index.php/Image:OWASP_Top_10_2007_-_French.pdf),
    [Format
    Word](https://www.owasp.org/index.php/Image:OWASP_Top_10_2007_-_French.doc)
  - 2007-11-16 : [Folio 2 pages
    Recto/verso](https://www.owasp.org/images/5/52/Owasp_tryptique.pdf)
    de présentation pour Infosecurity.
  - 2007-02-27 :
    [Newsletter_francaise_num%C3%A9ro_1](Newsletter_francaise_num%C3%A9ro_1 )
  - 2007-06-20 : Présentation de l'OWASP faite à NY en Juin 2007
    [5](https://www.owasp.org/images/7/71/20070620-FR-OWASP_NY_Keynote.ppt)

# Old News

  - 2009-06-09 : [Intervention sur les
    WAF](http://www.owasp.org/images/d/d2/20090609-CERT-IST-WAF-v0.1.pdf)
    lors du Forum [CERT-IST](http://www.cert-ist.com)
  - 2009-02-03 : L'OWASP France sera présent à [PCI
    Paris](http://www.pci-portal.com/events/event-info/paris). La
    présentation est : [l'OWASP et l'exigence 6.5 de
    PCI-DSS](https://www.owasp.org/images/f/fb/20090203-OWASP_PCI-Global_2009_Paris_-_v03.ppt)
  - 2008-11-19 : L'OWASP France sera présent sur [Infosecurity
    France](http://www.infosecurity.com.fr/FR/badge?ref=OWAW) à Paris :

[<https://www.owasp.org/images/8/88/Infosecurity.gif>](http://www.infosecurity.com.fr/index.php?argRedirect=FR%7Cbadge&Lang=FR&ref=OWAW)

  - 2008-07-08 : L'OWASP France a présenté le projet OWASP à
    l'[OSSIR](http://www.ossir.org). La présentation est disponible sur
    le site de
    [l'OWASP](https://www.owasp.org/images/9/94/20080708-OWASP_OSSIR.ppt)
  - 2008-02-15 : Le Top10 2007 est en version Francaise
  - 2008-02-11 : Présentation aux [TechDays 2008
    Microsoft](http://www.owasp.org/images/0/09/20080129-OWASP_TechDays_France_.ppt)
  - 2007-11-22 : Présentation a Infosecurity France [de
    l'OWASP](http://www.owasp.org/images/8/85/20071122-OWASP_Infosecurity_France.ppt)
  - 2007-11-07 : Interview dans le [Journal du
    Net](http://www.journaldunet.com/developpeur/itws/071106-securite-applicative-owasp.shtml)
  - 2007-10-05 : L'OWASP France présentera les enjeux de la sécurité des
    [Services WEB à Infosecurity France
    le 22/11/2007](http://www.infosecurity.com.fr/?Jpto=116&KM_Session=f345bb91df954e6cbc0148328f109e94&CurrentNode=518&Lang=FR&IdNode=708)
  - 2006-12-18 : Mise en place de l'association pour supporter le groupe
    OWASP
  - 2006-12-14 : Le Hub OWASP Viaduc a vu le jour
    <http://www.viadeo.com/hub/affichehub/?hubId=002fj37grgb7o7n>
  - 2006-12-13 : Naissance du chapitre Francais de l'OWASP. Une liste de
    diffusion est disponible.[Abonnez
    vous](http://lists.owasp.org/mailman/listinfo/owasp-france)
