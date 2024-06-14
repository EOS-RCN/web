---
layout: default
title: Webinar Info
---


<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
   <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="align-self:start;font-size:calc(20px + 3vw);">Webinars</h1>
    <!--  <p style="align-self:start;padding-top:10px;" id="describe">Learn about what we've been up to, and watch out for upcoming events.</p> -->
    </div>
  <!--  <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="notes">
        <img src="./images/akwesasne_notes_1978.png" alt="notes" style="width=100%;border: 1px solid #ec970b;">
        <figcaption id="cap">Excerpt from a book review written by Gary Snyder in the Spring 1978 issue of Akwesasne Notes. Akwesasne Notes, “Akwesasne Notes vol. 10 no. 1,” 
          American Indian Digital History Project, accessed June 12, 2023, http://www.aidhp.com/items/show/48.</figcaption>
      </figure>
    </div> -->
  </div>

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
