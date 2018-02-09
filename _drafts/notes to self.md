# Problems & want tos

* host first version to show when first css applied.
* Want to float subtitles after headers - vreemd genoeg werkt dit wel met paragraphs...



# How should the gallery be implemented?

## In general

* The title of the gallery will be a header
* Thumbnails will be shown in a grid at 100% container width, with plenty of margin
* Each thumbnail will be accompanied by
	* Price, if applicable
	* Expo status
	* One line of talk, ending with "Read more..." linking to the work page.

## Depending on context

Implemented?
- [x] Kunstenaar
- [x] Werk
- [x] Expo
- [x] Kunstenaars
- [x] Expos

### In a Kunstenaar

Show one picture of each Work. Chronologically, newest first

<ul>
{% for werk in site.werken %}
<li>
{% if werk.kunstenaar == page.title %}

SEND WERK TO GALLERY

{% endif %}
</li>
{% endfor %}

FINALIZE GALLERY; NEWEST FIRST

</ul>

### In a Werk

Show all pictures of the work, highest file size first



### In an Expo

Show a separate gallery for each artist in the Expo, with 4 works per artist.

### On the Kunstenaars page

Show a separate gallery for each artist, with 4 works per artist.

### On the Expos page

Show a separate gallery for each expo, with 4 works per expo.

## How to make the code understand?
