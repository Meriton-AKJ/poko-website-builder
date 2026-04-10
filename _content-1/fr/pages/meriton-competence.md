---
translationKey: meriton-competence
lang: fr
createdAt: 2026-03-19T12:40:00.000Z
uuid: '786214905133'
localizationKey: 4f2b9f31c7aa
name: Meriton compétences
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
span.skill {
    color: #a855f7;
}

.section-perso {
    --color-bg: #f5f5f5;
    background-color: #f5f5f5;
}

.section-perso .item-grid {
    background-color: var(--white);
    --radius-card: 8px;
    border: 1px solid #a855f7;
    --shadow-breakout-clickable: 0 2px 8px rgba(0,0,0,0.06);
    --shadow-breakout-clickable-hover: 0 10px 30px rgba(168,85,247,.35);
    --transform-breakout-clickable-hover: translateY(-2px);
    transition: box-shadow 0.3s ease, transform 0.3s ease;
}

.section-perso .item-grid h3 {
    color: var(--black);
    transition: color 0.3s ease;
}

.section-perso .item-grid:hover h3 {
    color: #a855f7;
}

.section-tech .item-grid h3 {
    color: var(--black);
    transition: color 0.3s ease;
}

.section-tech .item-grid:hover h3 {
    color: #a855f7;
}

.section-tech {
    --color-bg: #f5f5f5;
    background-color: #f5f5f5;
}

.section-tech .item-grid {
    background-color: var(--white);
    --radius-card: 8px;
    border: 1px solid #a855f7;
    --shadow-breakout-clickable: 0 2px 8px rgba(0,0,0,0.06);
    --shadow-breakout-clickable-hover: 0 10px 30px rgba(168,85,247,.35);
    --transform-breakout-clickable-hover: translateY(-2px);
    transition: box-shadow 0.3s ease, transform 0.3s ease;
}

.btn-cv {
    --color-text__button: var(--white);
    --color-bg__button: var(--black);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: #a855f7;
    border-radius: 6px;
    padding: 0.6rem 1.5rem;
    text-decoration: none;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.cta-meriton {
    background-color: rgba(168, 85, 247, 0.2);
    border-radius: 12px;
    padding: 2rem 4rem;
}

.cta-btn {
    --color-text__button: var(--black);
    --color-bg__button: var(--white);
    --color-text__button--hover: var(--black);
    --color-bg__button--hover: #a855f7;
    border-radius: 6px;
    margin: var(--step-0);
    text-decoration: none;
    transition: background-color 0.3s ease, color 0.3s ease;
}
{% endcss %}

{% sectionGrid %}
{% sectionHeader %}
## Compétences techniques en développement web
Je maîtrise [l'HTML]{.skill}, le [CSS]{.skill}, [Github]{.skill}, essentiels pour le développement de sites web. J'apprends également le [JavaScript]{.skill}, [PHP]{.skill}, [Bootstrap]{.skill} et [Figma]{.skill} pour élargir mes compétences et créer des applications web plus dynamiques et interactives.
{% endsectionHeader %}
{% wrapper class="cluster justify-center" %}
{% link url="/_images/cv-meriton_askaj.pdf", text="Télécharger mon CV en Français", linkType="file", class="button btn-cv box" %}
{% link url="/_images/cv-meriton_askaj_en.pdf", text="Télécharger mon CV en Anglais", linkType="file", class="button btn-cv box" %}
{% endwrapper %}
{% endsectionGrid %}

<hr>

{% sectionGrid class="section-perso bleed-bg" %}
{% sectionHeader %}
## Mes compétences personnelles
{% endsectionHeader %}
{% grid type="grid-fluid", columns="3" %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### À l'écoute
À l'écoute et professionnel, je veille à fournir un travail soigné et efficace. Mon objectif est de garantir un résultat de qualité qui répond aux attentes.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Discipliné
L'envie d'apprendre est grande. Je me mets des objectifs afin d'évoluer en autodidacte. Au travail, je suis sérieux et respectueux de mon environnement.
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Évolution continue
En constante évolution, j'apprends de nouvelles technologies et méthodes pour améliorer mes compétences et rester à jour.
{% endwrapper %}
{% endgridItem %}
{% endgrid %}
{% endsectionGrid %}

<hr>

{% sectionGrid class="section-tech bleed-bg" %}
{% sectionHeader %}
## Mes technologies
{% endsectionHeader %}
{% grid type="grid-fluid", columns="2" %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### HTML5
Expert
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### CSS3
Expert
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### GitHub
Expert
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Responsive Design
Expert
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Figma
Intermédiaire
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### JavaScript
En cours
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### React
En cours
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Node.js / Express
En cours
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### PHP
En cours
{% endwrapper %}
{% endgridItem %}
{% gridItem class="breakout-clickable" %}
{% wrapper class="box no-border center text" %}
### Bootstrap
En cours
{% endwrapper %}
{% endgridItem %}
{% endgrid %}
{% endsectionGrid %}

<hr>

{% partial "meriton-intro-cta" %}

<hr>
