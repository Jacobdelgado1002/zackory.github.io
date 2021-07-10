---
layout: page
title: Publications
permalink: /publications/
---

<script>
function showhide(d) {
  var x = document.getElementById(d);
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>

<table cellpadding="10" width="100%">
{% for pub in site.data.publications %}
    <tr>
        <td width="250" height="100">
            <img src="{{pub.image}}" img width="250">
        </td>
        <td><h5><a href="{{pub.pdf}}">{{pub.title}}</a></h5>
            {{pub.authors}}<br>
            <em>{{pub.venue}}</em>, {{pub.year}}
            <div style="font-size:small">
                <em>
                    {% if pub.pdf %}
                        <a href="{{pub.pdf}}">[PDF]</a>
                    {% endif %}
                    {% if pub.projectpage %}
                        <a href="{{pub.projectpage}}">[Project Page]</a>
                    {% endif %}
                    {% if pub.code %}
                        <a href="{{pub.code}}">[Code]</a>
                    {% endif %}
                    {% if pub.bibtex %}
                        <a href="javascript:showhide('bib{{pub.id}}')">[Bibtex]</a>
                    {% endif %}
                    {% if pub.abstract %}
                        <a href="javascript:showhide('abs{{pub.id}}')">[Abstract]</a>
                    {% endif %}
                    {% if pub.video %}
                        <a href="{{pub.video}}">[Video]</a>
                    {% endif %}
                </em>
                <div id="bib{{pub.id}}" style="display:none">
                    <br>
                    <blockquote>
                        <div style="white-space: pre-wrap;">{{pub.bibtex}}</div>
                    </blockquote>
                </div>
                <div id="abs{{pub.id}}" style="display:none">
                    <br>
                    {{pub.abstract}}
                </div>
            </div>
            <br>
        </td>
    </tr>
{% endfor %}
</table>

