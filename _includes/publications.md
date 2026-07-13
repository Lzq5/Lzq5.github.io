<div class="publications-heading">
  <h2 id="publications">Publications</h2>
</div>

<div class="publications" id="publications-list">
<ol class="bibliography">

{% for link in site.data.publications.main %}
{% include publication_item.html link=link %}
{% endfor %}

</ol>
</div>
