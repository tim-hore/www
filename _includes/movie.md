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
{% if page.video.duration %}| Durasi | {{ page.video.duration }} |{% endif %}

### Description

**Synopsis:** Set in the near-future, technology controls nearly all aspects of life. But when Grey, a self-identified technophobe, has his world turned upside down, his only hope for revenge is an experimental computer chip implant called Stem.

**Awards:** 1 win.
**Budget:** $5,000,000 (estimated)
{% if page.poster %}
| P O S T E R |
|:---:|
| ![{{ page.title }}]({{ page.poster }}) |
| {{ page.title }} |
{% endif %}

### Download/Streaming

| Link Download |
|:---:|
| Hosting: {% if page.video.hosting %}{{ page.video.hosting }}{% endif %}{% if page.video.hosting1 %}, {{ page.video.hosting1 }}{% endif %}{% if page.video.hosting2 %}, {{ page.video.hosting2 }}{% endif %} |
| Kualitas: {{ page.video.quality }} |
| Resolusi: 480p, 720p, 1080p |
| Format: {{ page.video.format }} |
{% if page.video.link %}| Download: [{{ page.video.hosting }}]({{ page.video.link }}){:.btn.btn--primary} {% endif %}{% if page.video.link1 %}[{{ page.video.hosting1 }}]({{ page.video.link1 }}){:.btn.btn--primary}{% endif %}{% if page.video.link2 %} [{{ page.video.hosting2 }}]({{ page.video.link2 }}){:.btn.btn--primary}{% endif %}{% if page.video.link3 %} [{{ page.video.hosting3 }}]({{ page.video.link3 }}){:.btn.btn--primary}{% endif %} |{% endif %}
| Penerjemah: {{ page.video.translator }} |
{% if page.video.stream %}| Link Streaming [{{ page.video.stream }}]({{ page.video.streamlink }}){:.btn.btn--primary} [{{ page.video.stream1 }}]({{ page.video.streamlink1 }}){:.btn.btn--primary} |{% endif %}
