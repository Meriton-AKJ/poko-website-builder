---
translationKey: demo-html5
lang: en
createdAt: 2025-10-24T11:19:00.000Z
uuid: 4bebefc7e99a
localizationKey: 49e6ae094a58
status: noindex
name: Demo HTML5
vars: {}
---
{%  partial "theme1"  %}
{% partial "theme1-css" %}


{% css %}
:root{
--bg-color: var(--theme1-v2-light-contrast);
--color-accent: var(--theme1-v2-light-accent);
--color-typo: var(--theme1-v2-light-typo);  
--color-alt: var(--theme1-v2-light-alt) 
}


{# HEADER #}
nav {
  display: flex;
  justify-content: space-between;
}

#menu ul {
  display: flex;
  list-style: none;
  gap: 2rem;
  
  margin: 0;
  padding: 0;
}

#menu a {
    text-decoration: none;
}

.logo{
    font-weight: bold;
}

{# BUTTON CALL TO ACTION CTA #}
.cta-button{
    background-color: var(--bg-color);
    text-decoration: none;
    color: var(--color-typo);
}

{# MAIN -> HERO #}
.hero{
    display: block;
    text-align: center;
    padding: 5rem;
    margin: 5rem;
}

.hero h2{
    color: bar(--bg-typo);
}

.hero p{
    color: bar(--bg-typo);
}




{% endcss %}

