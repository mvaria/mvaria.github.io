## Selected Publications

The remainder of this page describes some major themes of my research along with links to selected peer-reviewed publications. You can find a list of all of my publications at <a href="https://dblp.org/pid/59/6288.html">DBLP</a> and <a href="https://scholar.google.com/citations?user=lneZSfIAAAAJ">Google Scholar</a>.


### <i class="fa fa-cloud"></i> Data Analysis for Social Good

I deploy privacy-respecting systems in practice, with a focus on empowerment and accessibility.

<ul>
{% for link in site.data.socialgood.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>



### <i class="fa fa-database"></i> Secure Computing & Search

I design and develop cryptographic systems that allow people to perform collaborative analysis of protected data.

<ul>
{% for link in site.data.securecomp.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>



### <i class="fa fa-balance-scale"></i> Cryptography & Society, Law, and Policy

I examine the social impact of cryptography and the design of cryptosystems that achieve certain legal and policy objectives.

<ul>
{% for link in site.data.lawpolicy.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>



### <i class="fa fa-server"></i> Cryptographic & Distributed Algorithms

I design foundational crypto algorithms, including distributed algorithms that allow parties to reach consensus over an asynchronous network.

<ul>
{% for link in site.data.algorithms.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>


### <i class="fa fa-check-circle"></i> Formal Analysis of Cryptosystems

I construct formal, composable proofs of security for cryptographic protocols and real-world systems.

<ul>
{% for link in site.data.formal.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>


### <i class="fa fa-lightbulb"></i> Privacy & Inference

I develop information theoric bounds on data reconstruction attacks, and characterize the tradeoffs between privacy and utility.

<ul>
{% for link in site.data.inference.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>


### <i class="fa fa-code fa-fw"></i> Program Obfuscation

My <a href="https://dspace.mit.edu/handle/1721.1/64489">PhD thesis</a> provides concrete methods to obfuscate computer programs in a provably secure, virtual black-box manner while preserving their functionality.

<ul>
{% for link in site.data.obfuscation.main %}
<li>
    <strong> <a href="{{ link.pdf }}">{{ link.title }}</a></strong>.
    {{ link.authors }}.
    <em>{{ link.conference }}</em>.
    {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:12px;">[PDF]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:12px;">[Code]</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" style="font-size:12px;">[Project Page]</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" style="font-size:12px;">[BibTeX]</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
</li>
{% endfor %}
</ul>


<!---
<div class="publications">
<ol class="bibliography">

{% for link in site.data.obfuscation.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

{% endfor %}

</ol>
</div>
-->
