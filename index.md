---
layout: page
title: Ribesg's Blog
tagline: new MySelf().blog();
group: navigation
---
{% include JB/setup %}

## About me
My name is Gael Ribes, I'm french. I'm an apprentice working for [Hewlett-Packard][] in Grenoble while studying at the [Ensimag][].

_If you're not french or not used to french educational system, you may not be able to understand what follows in this section. Because of this, I'll just write it in french :)_

Après l'obtention de mon Baccalauréat Scientifique Mention Bien au Lycée René Perrin à Ugine (73) en 2010, je suis allé étudier à l'IUT2 de Grenoble dans la section Informatique. Ce diplôme en poche, j'ai rejoint l'Ensimag par la formation en Apprentissage au début de l'année universitaire 2012-2013. Je passe donc la moitié de mon temps à l'Ensimag et l'autre moitié dans mon entreprise, Hewlett-Packard.

## Bukkit plugins
I started developping [Bukkit][] plugins during the second semester of 2010. This work learnt me the **Java** language, how to use Eclipse, how to use an API dans how to read JavaDocs.
I'm currently working on a new project, between a complete rewrite of _almost_ everything I made during the last 2 years and a new organisation of my plugins : **the N plugins suite**.
If you want more informations about this project : [NPlugins][]

## Posts
<ul>
    {% for post in site.posts limit: site.recent_posts %}
        <li>
            {{ post.date | datetime | date_to_long_string }} - <a href="{{ root_url }}{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>


{% include JB/comments %}

<!--- Under this lines are links defined --->
[Ensimag]: http://ensimag.grenoble-inp.fr/ecole-nationale-superieure-d-informatique-et-de-mathematiques-appliquees-74488.kjsp?RH=ENSIMAG_FR&RF=ENSIMAG_EN "Ensimag"

[Hewlett-Packard]: http://en.wikipedia.org/wiki/Hewlett-Packard "Hewlett-Packard"

[Bukkit]: http://bukkit.org "Bukkit Forums"


[NPlugins]: /bukkit/NPlugins.html "More informations about NPlugins"
