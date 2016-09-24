---
published: false
title: Post 1 title
layout: post
author: Chase Roycroft
category: articles
tags:
- First title
- First tag
- Random other tag
iframe_url: https://www.youtube.com/embed/dQw4w9WgXcQ

---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla eget varius nulla. Proin ullamcorper mollis nulla id elementum. Integer sed est ipsum. Sed vehicula pharetra elit a rhoncus. Praesent ac nulla nisi. Integer ut pulvinar nulla, porttitor sollicitudin mi. Morbi non ullamcorper arcu. Duis at elit a elit venenatis fermentum non id dolor. Aenean tempor convallis semper. Nam ac libero diam. Nullam enim sapien, dignissim at cursus vitae, porta at purus. Vivamus vehicula tincidunt enim vitae lobortis. Sed a pretium dolor.

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>


{% if page.iframe_url %}
    <div class="less-fancy-video-header">
      <iframe
        class="yt-embed"
        src="{{ page.iframe_url }}?&rel=0&showinfo=0&autohide=1&hd=1&wmode=transparent"
        frameborder="0"
        allowfullscreen="true"
        ></iframe>
    </div>
{% endif %}










#explanaation for how to do this:
#https://blog.omgmog.net/post/video-integration-with-jekyll/
