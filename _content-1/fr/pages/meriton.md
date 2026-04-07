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

.button.btn-projet {
    color: #fff;
    background-color: #000;
    border-radius: 6px;
    padding: 0.6rem 1.5rem;
    text-decoration: none;
}

.button.btn-projet:hover {
    color: #000;
    background-color: var(--meriton-green-bright);
    transition: ease 0.8s;
}

.button.btn-contact {
    color: #000;
    background-color: #fff;
    border-radius: 6px;
    padding: 0.6rem 1.5rem;
    text-decoration: none;
}

.button.btn-contact:hover {
    color: #000;
    background-color: var(--meriton-green-bright);
    transition: ease 0.8s;
}

.section-projets {
    --color-bg: #f5f5f5;
    background-color: #f5f5f5;
}

.section-projet {
    --color-bg: #f5f5f5;
    background-color: #f5f5f5;
    padding: var(--step-2);
}

.section-projets .item-grid {
    background-color: #fff;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    transition: transform 0.8s ease;
}

.section-projets .item-grid:hover {
    box-shadow: 0 10px 30px rgba(32,226,11,.35);
    transform: scale(1.05);
}

.section-disponible {
    text-align: center;
}

.section-disponible .item-two-columns {
    background-color: #f9f9f9;
    border: 1px solid var(--meriton-green-bright);
    border-radius: 6px;
    padding: var(--step-0);
    transition: transform 0.8s ease;
}

.section-disponible .item-two-columns:hover {
    box-shadow: 0 8px 20px var(--meriton-green-bright);
    transform: scale(1.02);
}

.button.file-btn {
    color: #000;
    background-color: #fff;
    border: 2px solid var(--meriton-green-bright);
    border-radius: 6px;
    padding: 0.6rem 1.5rem;
    text-decoration: none;
}

.button.file-btn:hover {
    background-color: var(--meriton-green-bright);
    color: #000;
    transition: ease 0.8s;
}

.cta-meriton {
    background-color: rgba(32, 226, 11, 0.314);
    border-radius: 12px;
    padding: 2rem 4rem;
}

.button.cta-btn {
    background-color: #fff;
    color: #000;
    margin: var(--step-0);
    text-decoration: none;
}

.button.cta-btn:hover {
    background-color: var(--meriton-green-bright);
    color: #fff;
    transition: ease 0.3s;
}
{% endcss %}

{% wrapper tag="div", class="text-center palette-accueil-meriton" %}
# Meriton Askaj - Développeur web junior en formation

## - A la recherche d'un stage en alternance -

Bonjour, je suis Meriton Askaj, développeur web junior passionné, je crée des expériences digitales modernes et performantes. Je suis en formation en alternance, je maîtrise [l'HTML]{.skill}, le [CSS]{.skill}, [Github]{.skill} et j'apprends le [JavaScript]{.skill}, [PHP]{.skill}, [Bootstrap]{.skill} et [Figma]{.skill}.

{% link url="meriton-projet", text="Voir mes projets", linkType="internal", collection="pages", class="button btn-projet" %}{% link url="meriton-contact", text="Me contacter", linkType="internal", collection="pages", class="button btn-contact" %} {.cluster .justify-center}
{% endwrapper %}

<hr>

{% sectionGrid class="section-projets bleed-bg" %}
{% sectionHeader %}
## Sélection de mes projets
Projets réalisés en formation, d'apprentissage, et conceptuels
{% endsectionHeader %}
{% grid %}
{% gridItem class="box" %}
{% image src="/_images/pexels-mathilde-langevin-12032340.webp", alt="Photo d'un site e-commerce fleuriste", width="700", aspectRatio="1" %}

::: div {.box}
### Site e-commerce fleuriste

Plateforme e-commerce de vente de fleurs simple pour une personnalisation de bouquet entier, avec catalogue produits dynamique et base de données.
:::
{% endgridItem %}
{% gridItem class="box" %}
{% image src="/_images/pexels-andrea-devillier-32709984.webp", alt="Photo d'une landing page de chaussures", width="700", aspectRatio="1" %}

::: div {.box}
### Landing page de chaussures

Page de destination moderne et responsive pour la vente de chaussures, avec un design épuré et attrayant.
:::
{% endgridItem %}
{% gridItem class="box" %}
{% image src="/_images/pexels-andrea-devillier-32709984.webp", alt="Photo d'une to do list", width="700", aspectRatio="1" %}

::: div {.box}
### To Do List

Une To Do List simple avec un visuel moderne pour créer de nouvelles tâches, cocher lorsqu'elles sont finies ou bien les supprimer.
:::
{% endgridItem %}
{% endgrid %}

{% endsectionGrid %}

{% wrapper tag="div", class="center text section-projet bleed-bg" %}
{% link url="meriton-projet", text="Voir tous mes projets", linkType="internal", collection="pages", class="button btn-projet" %}
{% endwrapper %}

<hr>

{% sectionTwoColumns class="section-disponible" %}
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

{% wrapper tag="div", class="cluster" %}
{% link url="/_images/cv-meriton_askaj.pdf", text="Télécharger mon CV en Français", linkType="file", class="button file-btn box" %}
{% link url="/_images/cv-meriton_askaj_en.pdf", text="Télécharger mon CV en Anglais", linkType="file", class="button file-btn box" %}
{% endwrapper %}

<hr>

{% partial "meriton-intro-cta" %}

<hr>
