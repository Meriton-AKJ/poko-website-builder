---
translationKey: meriton-contact
lang: fr
createdAt: 2026-03-19T12:55:00.000Z
uuid: b1c7c6f2a2d4
localizationKey: 0b1d2a3c4e5f
name: Contact Meriton
eleventyNavigation: null
metadata: null
preview: null
tags: []
status: ''
pageLayout: ''
pageFooter: 'meriton-footer'
pageNav: ''
generatePage: ''
vars: null
dataList: []
---

{% css %}
.section-contact {
    --color-bg: #f5f5f5;
    background-color: #f5f5f5;
    --color-text__a: #c9a227;
}

.section-contact .item-grid {
    background-color: var(--white);
    --color-bg: var(--white);
    --radius-card: 8px;
    border: 1px solid #c9a227;
    --shadow-breakout-clickable: 0 2px 8px rgba(0,0,0,0.06);
    --shadow-breakout-clickable-hover: 0 8px 24px rgba(201,162,39,.35);
    --transform-breakout-clickable-hover: translateY(-2px);
    transition: box-shadow 0.3s ease, transform 0.3s ease;
}

.section-contact .item-grid h3 {
    color: var(--black);
    transition: color 0.3s ease;
}

.section-contact .item-grid:hover h3 {
    color: #c9a227;
}

.section-formation .item-grid {
    --radius-card: 6px;
    border: 1px solid #c9a227;
    padding: var(--step-0);
    text-align: left;
}

.section-travaux .item-grid {
    --radius-card: 6px;
    border: 1px solid #c9a227;
    padding: var(--step-0);
    text-align: right;
}

.section-dispo .item-two-columns {
    background-color: #f9f9f9;
    border: 1px solid #c9a227;
    --radius-card: 6px;
    padding: var(--step-0);
    text-align: center;
    --shadow-breakout-clickable-hover: 0 8px 20px rgba(201,162,39,.4);
    --transform-breakout-clickable-hover: scale(1.02);
    transition: box-shadow 0.3s ease, transform 0.3s ease;
}

.section-bref .item-grid h4 {
    color: #c9a227;
    font-size: var(--step-3);
}

.btn-cv-contact {
    --color-text__button: var(--white);
    --color-bg__button: var(--black);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: #c9a227;
    border-radius: 6px;
    padding: 0.6rem 1.5rem;
    text-decoration: none;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.cta-meriton {
    background-color: rgba(201, 162, 39, 0.15);
    border-radius: 12px;
    padding: 2rem 4rem;
}

.cta-btn {
    --color-text__button: var(--black);
    --color-bg__button: var(--white);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: #c9a227;
    border-radius: 6px;
    margin: var(--step-0);
    text-decoration: none;
    transition: background-color 0.3s ease, color 0.3s ease;
}
{% endcss %}

{% sectionGrid%}
{% sectionHeader %}
## Contactez-moi
N'hésitez pas à me contacter pour une opportunité de stage en alternance si mon profil vous a fait de l'œil !
{% endsectionHeader %}
{% endsectionGrid %}

{% sectionGrid class="section-contact bleed-bg" %}
{% sectionHeader%}
## Comment me contacter
{% endsectionHeader %}
{% grid type="grid-fluid", columns="5" %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Email
{% link url="meritonaskaj01@gmail.com", text="meritonaskaj01@gmail.com", linkType="email" %}
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Téléphone
(+32) 0487/ 72/ 54/ 35
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### LinkedIn
{% link url="https://www.linkedin.com/in/meriton-askaj", text="Meriton Askaj", linkType="external" %}
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### GitHub
{% link url="https://github.com/Meriton-AKJ", text="Meriton-AKJ", linkType="external" %}
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Localisation
Belgique, Bruxelles, EFP (Uccle)
{% endwrapper %}
{% endgridItem %}
{% endgrid %}
{% endsectionGrid %}

<hr>

{% sectionGrid class="section-formation" %}
{% sectionHeader %}
## Formations & Certifications
{% endsectionHeader %}
{% grid type="grid-fluid", columns="1" %}
{% gridItem %}
**EFP, Uccle: Formation en Alternance, Développeur Web Front-end**

30/09/2024, En cours
{% endgridItem %}
{% gridItem %}
**Lycée Émile Max, Schaerbeek: Diplôme Secondaire Général, CESS Math-Sciences**

2019, 2021
{% endgridItem %}
{% endgrid %}
{% endsectionGrid %}

<hr>

{% sectionGrid class="section-travaux" %}
{% sectionHeader %}
## Travaux effectués
{% endsectionHeader %}
{% grid type="grid-fluid", columns="1" %}
{% gridItem %}
**Développeur web, mookai ASBL: Stagiaire**

05/02/26, 10/04/26
{% endgridItem %}
{% gridItem %}
**Réceptionniste, Novotel Brussels Airport: CDD**

16/01/25, 31/01/26
{% endgridItem %}
{% gridItem %}
**Inventoriste, Skillflex: Intérim**

01/09/23, 01/07/24
{% endgridItem %}
{% endgrid %}
{% endsectionGrid %}

<hr>

{% sectionTwoColumns class="section-dispo" %}
{% sectionHeader %}
{% wrapper class="center text" %}
## Actuellement disponible
Je recherche activement et suis disponible dès maintenant pour une offre de stage en alternance en tant que développeur web.
{% endwrapper %}
{% endsectionHeader %}
{% twoColumns type="switcher" %}
{% twoColumnsItem class="breakout-clickable" %}
### Stage rémunéré
Un stage rémunéré, qui se déroulera jusqu'à fin septembre 2026, en parallèle des cours du soir trois fois par semaine.
{% endtwoColumnsItem %}
{% twoColumnsItem class="breakout-clickable" %}
### Stage non-rémunéré
Un stage non-rémunéré, d'une durée de 250 heures, en parallèle des cours du soir trois fois par semaine.
{% endtwoColumnsItem %}
{% endtwoColumns %}
{% endsectionTwoColumns %}

{% wrapper class="cluster" %}
{% link url="/_images/cv-meriton_askaj.pdf", text="Télécharger mon CV en Français", linkType="file", class="button btn-cv-contact box" %}
{% link url="/_images/cv-meriton_askaj_en.pdf", text="Télécharger mon CV en Anglais", linkType="file", class="button btn-cv-contact box" %}
{% endwrapper %}

<hr>

{% sectionGrid class="section-bref" %}
{% sectionHeader %}
### En bref...
{% endsectionHeader %}
{% grid %}
{% gridItem %}
{% wrapper class="center text" %}
#### 1+

Années d'expérience
{% endwrapper %}
{% endgridItem %}
{% gridItem %}
{% wrapper class="center text" %}
#### 6+

Projets réalisés
{% endwrapper %}
{% endgridItem %}
{% gridItem %}
{% wrapper class="center text" %}
#### 4+

Technologies maîtrisées
{% endwrapper %}
{% endgridItem %}
{% gridItem %}
{% wrapper class="center text" %}
#### 100%

Motivation
{% endwrapper %}
{% endgridItem %}
{% endgrid %}

{% endsectionGrid %}

<hr>

{% partial "meriton-intro-cta" %}

<hr>
