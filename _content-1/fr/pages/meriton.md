---
translationKey: meriton
lang: fr
createdAt: 2026-03-19T10:03:00.000Z
uuid: '921295758582'
localizationKey: 0d60fecf2529
name: meriton
eleventyNavigation: null
metadata: null
preview: null
tags: []
status: ''
pageLayout: ''
pageFooter: meriton-footer
pageNav: meriton-nav
generatePage: ''
vars: null
dataList: []
---

{% css %}
.palette-accueil-meriton h1 {
    --color-text__heading: var(--color-text);
}

span.skill {
    color: var(--meriton-green);
}

.btn-contact {
    --color-text__button: var(--black);
    --color-bg__button: var(--white);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: var(--meriton-green-bright);
}

.cards-clickable {
    --shadow-breakout-clickable: 0 0 0 rgba(0,0,0,0);
    --shadow-breakout-clickable-hover: 0 10px 30px rgba(32,226,11,.35);
    --transform-breakout-clickable-hover: translateY(-2px);
}
{% endcss %}

{% wrapper tag="div", class="text-center palette-accueil-meriton" %}
# Meriton Askaj - Développeur web junior en formation

## - A la recherche d'un stage en alternance -

Bonjour, je suis Meriton Askaj, développeur web junior passionné, je crée des expériences digitales modernes et performantes. Je suis en formation en alternance, je maîtrise [l'HTML]{.skill}, le [CSS]{.skill}, [Github]{.skill} et j'apprends le [JavaScript]{.skill}, [PHP]{.skill}, [Bootstrap]{.skill} et [Figma]{.skill}.

{% link url="meriton-projet", text="Voir mes projets", linkType="internal", collection="pages", class="button btn-projet" %}{% link url="meriton-contact", text="Me contacter", linkType="internal", collection="pages", class="button btn-contact" %} {.cluster .justify-center}
{% endwrapper %}

<hr>

{% sectionGrid %}
{% sectionHeader %}
## Sélection de mes projets
Projets réalisés en formation, d'apprentissage, et conceptuels
{% endsectionHeader %}
{% grid type="grid-fluid", columns="3", class="center text" %}
{% gridItem class="cards-clickable" %}
{% image src="/_images/pexels-mathilde-langevin-12032340.webp", alt="Photo d'un site e-commerce fleuriste", width="700", aspectRatio="1" %}

### Site e-commerce fleuriste

Plateforme e-commerce de vente de fleurs simple pour une personnalisation de bouquet entier, avec catalogue produits dynamique et base de données.
{% endgridItem %}
{% gridItem class="cards-clickable" %}
{% image src="/_images/pexels-andrea-devillier-32709984.webp", alt="Photo d'une landing page de chaussures", width="700", aspectRatio="1" %}

### Landing page de chaussures

Page de destination moderne et responsive pour la vente de chaussures, avec un design épuré et attrayant.
{% endgridItem %}
{% gridItem class="cards-clickable" %}
{% image src="/_images/pexels-andrea-devillier-32709984.webp", alt="Photo d'une to do list", width="700", aspectRatio="1" %}

### To Do List

Une To Do List simple avec un visuel moderne pour créer de nouvelles tâches, cocher lorsqu'elles sont finies ou bien les supprimer.
{% endgridItem %}
{% endgrid %}

{% endsectionGrid %}
{% wrapper tag="div", class="center text" %}
{% link url="meriton-projet", text="Voir tous mes projets", linkType="internal", collection="pages", class="button btn-projet" %}
{% endwrapper %}
<hr>

{% sectionTwoColumns %}
{% sectionHeader %}
::: div {.center .text}
## Actuellement disponible
Je recherche activement et suis disponible dès maintenant pour une offre de stage en alternance en tant que développeur web.
:::
{% endsectionHeader %}
{% twoColumns type="switcher" %}
{% twoColumnsItem %}
### Stage rémunéré
Un stage rémunéré, qui se déroulera jusqu'à fin septembre 2026, en parallèle des cours du soir trois fois par semaine.
{% endtwoColumnsItem %}
{% twoColumnsItem %}
### Stage non-rémunéré
Un stage non-rémunéré, d'une durée de 250 heures, en parallèle des cours du soir trois fois par semaine.
{% endtwoColumnsItem %}
{% endtwoColumns %}

{% endsectionTwoColumns %}

{% wrapper tag="div" %}
::: switcher {.v--width-wrap:1px .v--grow-switcher:0}
{% link url="#", text="Télécharger mon CV en Français", linkType="external" %}
{% link url="#", text="Télécharger mon CV en Anglais", linkType="external" %}
:::
{% endwrapper %}

<hr>

{% partial "meriton-intro-cta" %}

<hr>
