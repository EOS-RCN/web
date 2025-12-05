---
layout: default
title: Webinar Info
---


<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
   <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="align-self:start;font-size:calc(20px + 3vw);">Webinars</h1>
    </div>
  </div>

<div id="encompass" style="display:grid;grid-template-columns: 5fr 1fr;">
   

   <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;padding-left:0%;width:67%;align-content:start;padding-top:0px;margin-top:20px;border-top: 1px solid #ec970b;min-width:293px;">
     {% assign posts = site.posts | where_exp: "item", "item.tags contains 'webinar'" %}
      {% for post in posts %}
      <div class="text-block-right" style="display:grid; grid-template-columns: auto auto; justify-content: start; border-bottom: 1px solid #ec970b;width:95%;padding-top:2%;padding-bottom:2%;">
          {% if post.image %} 
            <img src={{ post.image }} width="180vw" alt="{{ post.alt }}" style="max-width:500px;">
          {% endif %}
          {% if post.image == %}
            <div class="test" style="width:180px;">
              <!-- <p style="">empty</p> -->
            </div>
          {% endif %}
        <div style="display:grid;grid-template-rows: auto auto;padding-left:20px;align-content:start">
        <p style="font-size:14px;">{{ post.date | date_to_string }}</p>
        <p><a href="{{ post.url | relative_url }}">{{ post.title }}</a></p>
         </div>
      </div>
{% endfor %}

</div>

<div id="linker">
<p>
   Find our channel of recorded webinar videos <a href="https://www.youtube.com/watch?v=DB-87ZbdSnE&list=PLlz1bp5bLPvDcSKIy5M4ULvk-9Q7gKnX_" target="_blank">here.</a>
</p>
   
</div>
</div>
