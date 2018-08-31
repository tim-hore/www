### Details

| Judul Film | {{ page.video.title }} |
|:---|:---|
| Sutradara | {{ page.video.director }} |
| Pemain | {{ page.video.cast }} |
| Genre | {{ page.video.genre }} |
| Rilis | {{ page.video.release }} |
{% if page.video.producer %}| Produser | {{ page.video.producer }} |{% endif %}
| Rating | {% if page.video.imdb %}{{ page.video.imdb }}{% elsif page.video.rating %}{{ page.video.rating }}{% endif %} |
{% if page.video.distributor %}| Distribusi | {{ page.video.distributor }} |{% endif %}
| Hosting | {% if page.video.hosting %}{{ page.video.hosting }}{% endif %}{% if page.video.hosting1 %}, {{ page.video.hosting1 }}{% endif %}{% if page.video.hosting2 %}, page.video.hosting2 }}{% endif %} |
| Format | {{ page.video.format }} |
| Kualitas | {{ page.video.quality }} |
| Resolusi | {{ page.video.resolution }} |
{% if page.video.duration %}| Durasi | {{ page.video.duration }} |{% endif %}

### Download

{% if page.video.link %}[Link 0]({{ page.video.link }}){:.button} {% endif %}{%if page.video.link1 %}[Link 1]({{ page.video.link1 }}){:.button}{% endif %}{% if page.video.link2 %} [Link 2]({{ page.video.link2 }}){:.button}{% endif %}{% if page.video.link3 %} [Link 3]({{ page.video.link3 }}){:.button}{% endif %}

### Description

