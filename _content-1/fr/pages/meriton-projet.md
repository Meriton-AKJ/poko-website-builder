---
translationKey: meriton-projet
lang: fr
createdAt: 2026-03-19T12:10:00.000Z
uuid: '449183726501'
localizationKey: 6a9d204ef5aa
name: Meriton projets
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
.section-projets-page {
    --color-bg: #f5f5f5;
    background-color: #f5f5f5;
}

.section-projets-page .item-grid {
    background-color: var(--white);
    --radius-card: 8px;
    --shadow-breakout-clickable: 0 2px 8px rgba(0,0,0,0.08);
    --shadow-breakout-clickable-hover: 0 10px 30px rgba(226,32,11,.5);
    --transform-breakout-clickable-hover: translateY(-2px);
    transition: box-shadow 0.3s ease, transform 0.3s ease;
}

.btn-competences {
    --color-text__button: var(--white);
    --color-bg__button: var(--black);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: #e2200b;
    border-radius: 6px;
    padding: 0.6rem 1.5rem;
    text-decoration: none;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.cta-meriton {
    background-color: rgba(226, 32, 11, 0.15);
    border-radius: 12px;
    padding: 2rem 4rem;
}

.cta-btn {
    --color-text__button: var(--black);
    --color-bg__button: var(--white);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: #e2200b;
    border-radius: 6px;
    margin: var(--step-0);
    text-decoration: none;
    transition: background-color 0.3s ease, color 0.3s ease;
}
{% endcss %}

{% sectionGrid class="section-projets-page bleed-bg" %}
{% sectionHeader %}
## Mes projets
Projets réalisés en formation, d'apprentissage, et conceptuels
{% endsectionHeader %}
{% grid type="grid-fluid", columns="3" %}
{% gridItem class="breakout-clickable" %}
{% image src="/_images/pexels-ella-wei-10655130.webp", alt="Logo du site e-commerce de fleur: MonBouquetPresDeChezMoi.io", aspectRatio="1", width="700" %}

{% wrapper class="box center text" %}
### Site e-commerce fleuriste

Plateforme e-commerce de vente de fleurs simple pour une personnalisation de bouquet entier, avec catalogue produits dynamique et base de données.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% image src="/_images/pexels-mathilde-langevin-12032340.webp", alt="Photo d'une landing page de chaussures", aspectRatio="1", width="700" %}

{% wrapper class="box center text" %}
### Landing page de chaussures

Page de destination moderne et responsive pour la vente de chaussures, avec un design épuré et attrayant.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% image src="/_images/pexels-andrea-devillier-32709984.webp", alt="Photo d'une to do list", aspectRatio="1", width="700" %}

{% wrapper class="box center text" %}
### To Do List

Une To Do List simple avec un visuel moderne pour créer de nouvelles tâches, cocher lorsqu'elles sont finies ou bien les supprimer.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% image src="/_images/pexels-secret-garden-931150.webp", alt="Photo d'un jeu style Warspear Online", aspectRatio="1", width="700" %}

{% wrapper class="box center text" %}
### Jeu style Warspear Online

Jeu en 2D inspiré de Warspear Online, avec un univers immersif où les joueurs peuvent explorer différents environnements, interagir avec des PNJ, accomplir des quêtes et progresser.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% image src="/_images/pexels-amine-photographe-14559000.webp", alt="Une photo d'une landing page pour le menu d'un restaurant", aspectRatio="1", width="700" %}

{% wrapper class="box center text" %}
### Landing page menu restaurant

Page de destination moderne et responsive pour le menu d'un restaurant, avec un design épuré et des boutons d'appel à l'action placés avec soin.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% image src="/_images/pexels-andrea-devillier-32977642.webp", alt="Photo d'une application d'hôtellerie pour la gestion des départements", aspectRatio="1", width="700" %}

{% wrapper class="box center text" %}
### Application hôtellerie

Cette application facilite la communication entre les différents départements d'un hôtel, avec des fonctionnalités pour les responsables et leurs employés.
{% endwrapper %}
{% endgridItem %}
{% endgrid %}

{% wrapper class="center text" %}
{% link url="meriton-competence", text="Quelles sont mes compétences", linkType="internal", collection="pages", class="button btn-competences" %}
{% endwrapper %}

{% endsectionGrid %}

<hr>

{% partial "meriton-intro-cta" %}

<hr>
