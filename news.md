---
layout: default
title: News
weight : 98
permalink: /news
---
<style>

#cal {
  position: relative;
  z-index: 0;
  }
h1#heading-left {
  font-size:40px;
  }
  
#posts-calendar {
  grid-template-columns:66.666% 33.3333%;
  }
@media print,screen and (max-width:620px) {
  #cal {
    width:200px;
  }
  #heading-left {
   padding-top:0px;
   padding-bottom:0px;
   align-content:space-between;
  }
  h1#heading-left {
   font-size:33px;
  }
  #posts-calendar {
  grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));
  }
 }
  
  #cap {
  display:none;
  background-color: #fff;
  position: absolute;
  max-width:180px;
  border: 1px solid #ec970b;
  padding: 1%;
  margin-left: 2%;
  width:86%;
  z-index:10000;
  }
  
  #notes:hover #cap {
  display:block;
  }
</style>


<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
   <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="align-self:start;font-size:calc(20px + 3vw);">Ethical Open Science in the News</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Learn about what we've been up to, and watch out for upcoming events.</p>
    </div>
  <!--  <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="notes">
        <img src="./images/akwesasne_notes_1978.png" alt="notes" style="width=100%;border: 1px solid #ec970b;">
        <figcaption id="cap">Excerpt from a book review written by Gary Snyder in the Spring 1978 issue of Akwesasne Notes. Akwesasne Notes, “Akwesasne Notes vol. 10 no. 1,” 
          American Indian Digital History Project, accessed June 12, 2023, http://www.aidhp.com/items/show/48.</figcaption>
      </figure>
    </div> -->
  </div>

<div class="text-block-right" style="display:flex;flex-direction:row; flex-wrap:wrap;padding-left:3%;width:97%;" id="posts-calendar">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;padding-left:0%;width:67%;align-content:start;padding-top:0px;margin-top:20px;border-top: 1px solid #ec970b;min-width:293px;">
      {% for post in site.posts %}
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

    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto auto;padding-left:0%;width:1000px;">
      <h2> EOS RCN Events Calendar </h2>
      <iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23B39DDB&title=Upcoming%20EOS%20RCN%20Events&src=Y2U1NzRhZTM5Y2JhOTMyNDIyZDAzNjA1MzFlZDE1OGI0ZmQ4MjdiMDY1YmE3Yjk1YjMxNTk1MWVjYTYwNDVlOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23EC970B&ctz=America%2FLos_Angeles" title = "EOS RCN Events Calendar" style="border: 1px solid #ec970b;width:95%;margin-right:5%;" width="400" height="500" frameborder="0" scrolling="no" id="cal"> wmode="transparent" </iframe>
    </div>
</div>


<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jstimezonedetect/1.0.7/jstz.js"></script>


<script type="text/javascript">
  const timeZone1 = new Intl.DateTimeFormat().resolvedOptions().timeZone;
  var timezone = jstz.determine();
  var pref = '<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23B39DDB&title=Upcoming%20EOS%20RCN%20Events&src=Y2U1NzRhZTM5Y2JhOTMyNDIyZDAzNjA1MzFlZDE1OGI0ZmQ4MjdiMDY1YmE3Yjk1YjMxNTk1MWVjYTYwNDVlOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23EC970B&ctz=';
  var suff = '" title = "EOS RCN Events Calendar" style="border: 1px solid #ec970b;width:95%;margin-right:5%;" width="400" height="500" frameborder="0" scrolling="no" id="cal"> wmode="transparent" </iframe>';
  var iframe_html = pref + timezone.name() + suff;
  document.getElementById('cal').innerHTML = iframe_html;
  console.log(iframe_html);
  console.log(timeZone1);
</script>

