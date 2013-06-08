---
layout: post
published: true
title: Disable comment box on Facebook like button
author_login: picsoung
author_email: nicolas.grenie@utbm.fr
dotclear_id: 188
date: 2011-10-31 02:14:00.000000000 +01:00
categories:
- Geekeries
tags: []
comments: []
---
<p><img src="/public/illus_billets/1-Facebook.png" alt="1-Facebook.png" title="1-Facebook.png, oct. 2011" /></p>


<p>Having a website is cool, having a social website is better :)
SEO is not the only way to drive traffic to your website anymore, you need a social presence to get more people coming on your site.
If are looking for an easy way to make your website social you can use services like <a href="http://www.addthis.com/" hreflang="en" title="AddThis">AddThis</a>, with a small line of javascript, your users will be able to share your website on main social networks.</p>


<p>That's super easy but you might be the kind of person who likes to manage everything and want to code your own stuff.</p>


<p>Implementing a like button is also super simple go on this page
http://developers.facebook.com/docs/reference/plugins/like/</p>


<p>And get the code you need to implement to have a nice-looking Like button :)</p>


<p>Recently Facebook add a comment functionality but you may want to disable it.
Add these few lines of CSS and the comment box won't show up&nbsp;:</p>

<pre>[CSS]
.fb_edge_widget_with_comment{
  position: absolute;
}

.fb_edge_widget_with_comment span.fb_edge_comment_widget iframe.fb_ltr {
  display: none !important;
}
</pre>


<p>Now you have old-style like button without a comment box :)
Have fun "hacking" Facebook :)</p>
