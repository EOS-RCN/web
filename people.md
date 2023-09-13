---
layout: default
title: "people"
permalink: /people
---

<style>
  div.image {
  object-fit: contain;
  <!-- width: 25%; -->
  height: 25%
  min-width: 100px;
  }  
  
div.text-block-main {
  padding-left: 5%
  }
 .profiles {
  min-width:100px;
  }
  .prof-text {
  <!-- width:130%; -->
  }
  
  #heading-image {
  padding-top: 0px;
  padding-bottom: 0px;
  margin-left:0px;
  margin-right:0px;
  align-self:center;
  }
  
  #stakes {
  margin-left:0px;
  margin-right:0px;
  }
  
 @media print, screen and (max-width: 600px) {
  .profiles {
  <!-- margin-right:40px; -->
  min-width:80px;
  }
  .prof-text {
  <!-- width:130%; -->
  }
  }
</style>

<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);align-self:start;">Meet our Team</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Our team is always evolving as we broaden our network of participants. However, our shared commitment to building an ethical open scientific community remains constant. </p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/rcn_org-chart_v6.png" alt="org-chart" style="width=100%;">
        <figcaption></figcaption>
      </figure>
    </div>
  </div>

<div class="text-block-right" style="display:grid;grid-template-rows:1.5em auto 1.5em auto;background-color:#fff;padding-left:0; width:100%;" id="meatblock">
  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;margin-left:2%;width:98%;" id="pi-title">
  <h2 style="color:#42b7bf;margin-bottom:0px; background-color:#fff;z- index:9;position:relative;overflow:visible; border-bottom:1px solid #ec970b;width:100%">The Principal Investigators</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:20px;align-content:center;padding-left:0%;width:95%;margin-left:5%;">
  
    {% for team_member in site.team_members %}
        <div class="text-block-right" style="display:grid;grid-template-columns: auto auto; align-content:center;align-items:center;justify-content:space-evenly;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; padding-top:0px;padding-bottom:0px;width:93%;padding-right:2%; margin-left:3%; border-left: 1px solid #ec970b; padding-left:2%;justify-items:center;max-width:350px;grid-auto-rows: 1fr;">
          <div style="diplay:grid;grid-auto-rows: auto; justify-content:start; align-content:center;padding-right:10%;padding-top:10%;height:90%;align-self:start;" class="prof-text">
            <p style="font-size:15px;font-weight:bold;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.name }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.role }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.email }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.website }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.institution }} </span></p>
          </div>
          
          <div class="image" style="padding:5px;">
            <img src={{ team_member.picture }} style="border:1px solid #ec970b;" class="profiles">
          </div>
        </div>
    {% endfor %} 
  </div>
  <br>
   <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;margin-left:2%;width:98%;" id="personnel-title">
  <h2 style="color:#42b7bf;margin-bottom:0px; background-color:#fff;z- index:9;position:relative;overflow:visible; border-bottom:1px solid #ec970b;width:100%">Other Project Leaders</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:95%;margin-left:5%;">
  
    {% for team_member in site.personnel_members %}
        <div class="text-block-right" style="display:grid;grid-template-columns: auto auto; align-content:center;align-items:center;justify-content:space-evenly;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; padding-top:0px;padding-bottom:0px;width:93%;padding-right:2%; margin-left:3%; border-left: 1px solid #ec970b; padding-left:2%;justify-items:center;max-width:350px;grid-auto-rows: 1fr;">
          <div style="diplay:grid;grid-template-rows: auto auto auto; justify-content:start; align-content:center;padding-right:10%;padding-top:10%;height:90%;align-self:start;" class="prof-text">
            <p style="font-size:15px;font-weight:bold;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.name }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.role }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ team_member.institution }} </span></p>
          </div>
          
          <div class="image" style="padding:5px;">
            <img src={{ team_member.picture }} style="border:1px solid #ec970b;" class="profiles">
          </div>
        </div>
    {% endfor %} 
  </div>
<br>
  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;margin-left:2%;width:98%;" id="advise-title">
   <h2 style="color:#42b7bf;margin-bottom:0px; background-color:#fff;z-index:9;position:relative;overflow:visible; border-bottom:1px solid #ec970b;width:100%;">The Advisory Committee</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:95%;margin-left:5%;">
  
      {% for advise_member in site.advise_members %}
        <div class="text-block-right" style="padding-left:0%;width:100%;display:grid;grid-template-columns: auto auto; align-content:center;align-items:center;justify-content:space-evenly;justify-items:start;border-bottom:1px solid #ec970b; border-right:1px solid #ec970b; padding-top:0px;padding-bottom:0px;width:93%;padding-right:2%; margin-left:3%; border-left: 1px solid #ec970b; padding-left:2%;justify-items:center;max-width:350px;grid-auto-rows: 1fr;">

          <div style="diplay:grid;grid-template-rows: auto auto auto; justify-content:start; align-content: center;font-size:15px;padding-left:8%;width:92%;padding-right:10%;padding-top:10%;height:90%;align-self:start;" class="prof-text">
            <p style="font-size:15px;font-weight:bold;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ advise_member.name }}</span></p>
            <p style="font-size:15px;"><span style="margin-top:2px;margin-bottom:2px;display:inline;">{{ advise_member.institution }}</span></p>
          </div>
          
          <div class="image" style="padding:5px;">
            <img src={{ advise_member.picture }} style="border:1px solid #ec970b;" class="profiles">
          </div>
          
        </div>
      {% endfor %} 
  </div>



  <div class="text-block-right" style="display:grid;grid-template-columns:auto;padding:0px;margin-left:2%;width:98%;" id="repository-image">
  <h2 style="color:#42b7bf;margin-bottom:0px; background-color:#fff;z- index:9;position:relative;overflow:visible; border-bottom:1px solid #ec970b;width:100%">Related Repositories</h2>
  </div>
  <div class="text-block-right" style="flex-direction:row;flex-wrap:wrap;padding-top:0px;align-content:center;padding-left:0%;width:90%;margin-left:5%;margin-right:5%; justify-content:center;">
   <img src="./images/rcn_stakes.png" style="border:1px solid #ec970b;margin-top:15px;" usemap="#repomap">
  <map name="repomap">
  <area shape="rect" coords="26,62,118,123" alt="Neotoma" href="https://www.neotomadb.org/">
  <area shape="rect" coords="210,38,300,125" alt="PBDB" href="https://paleobiodb.org/#/">
  <area shape="rect" coords="28,162,114,253" alt="EarthLife" href="https://earthlifeconsortium.org/">
  <area shape="rect" coords="125,190,195,270" alt="Cabah" href="https://epicaustralia.org.au/">
     <area shape="rect" coords="208,170,310,220" alt="futres" href="https://futres.org/">
    <area shape="rect" coords="40,337,166,394" alt="neon" href="https://www.neonscience.org/">
    <area shape="rect" coords="181,375,292,440" alt="gbif" href="https://www.gbif.org/">
    <area shape="rect" coords="320,362,489,410" alt="flmnh" href="https://www.floridamuseum.ufl.edu/">
    <area shape="rect" coords="504,363,608,445" alt="isample" href="https://isamplesorg.github.io/home/">
    <area shape="rect" coords="630,56,608,445" alt="opencontext" href="https://opencontext.org/">
    <area shape="rect" coords="630,90,733,190" alt="zan" href="https://zooarchnet.org/">
    <area shape="rect" coords="753,94,905,155" alt="tdar" href="https://core.tdar.org/">
    <area shape="rect" coords="636,198,721,281" alt="dinaa" href="https://alexandriaarchive.org/dinaa/">
    <area shape="rect" coords="759,165,880,210" alt="card" href="https://www.canadianarchaeology.ca/">
    <area shape="rect" coords="739,220,901,276" alt="sead" href="https://www.sead.se/">
        <area shape="rect" coords="655,335,775,444" alt="noaa" href="https://www.ncei.noaa.gov/products/paleoclimatology">
    <area shape="rect" coords="784,330,917,439" alt="lipd" href="https://lipd.net/">
</map>
  </div>
</div>
  
  
 
