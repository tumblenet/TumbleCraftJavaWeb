---
layout: page
title: Apply
image: /uploads/2018-04-16_20.07.27.png
---
<div class="card text-white bg-dark">
  <div class="card-body">
    {% for rank in site.data.ranks %}
    <p>{% include display-name.html rank=rank.id user="Example: This is text" %}<p>
    {% endfor %}
</div>
</div>
<br>
<br>
<p>I want {% include rank.html rank="voter" %}: [click here](/vote)</p>
<br>
<br>
<iframe src="https://goo.gl/forms/ZaJMArEi4B9bIPy33" frameborder="0" width="100%" height="100%" marginheight="0" marginwidth="0" seamless="true" style="overflow: scroll;height: -webkit-fill-available;width: -webkit-fill-available;" >Loading...</iframe>
