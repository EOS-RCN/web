---
layout: default
title: research
permalink: /research
---
<style>

div.text-block-main {
  display: grid;
  grid-template-rows: auto auto auto;
  margin-right:0px;
  padding-bottom:0px;
  background: #fff;
  }
div.text-block-right {
  margin-right:0px;
  padding-right:0px;
  width:100%;
  padding-left:0px;
  }
#stakes {
  margin-left: 0px;
  margin-right: 0px;
  }
  h3 {
  color: #000;
  }
  
  #aimses {
  /**
   * User input values.
   */
  --grid-layout-gap: 10px;
  --grid-column-count: 3;
  --grid-item--min-width: 220px;

  /**
   * Calculated values.
   */
  --gap-count: calc(var(--grid-column-count) - 1);
  --total-gap-width: calc(var(--gap-count) * var(--grid-layout-gap));
  --grid-item--max-width: calc((100% - var(--total-gap-width)) / var(--grid-column-count));

  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(max(var(--grid-item--min-width), var(--grid-item--max-width)), 1fr));
  grid-gap: var(--grid-layout-gap);
}
  
 @media print, screen and (max-width: 480px) {
  #stakes, #describe {
    width:200px;
     }
  #headingblock {
    justify-content: left;
    justify-items: center;
     }
  #heading-left, #heading-image, #stakes {
    justify-content: left;
    /* justify-items: center; */
    justify-self: center;
   }
  #heading-image {
    padding-top:0px;
   }
  
  #stakes {
  text-align: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
   }
  #heading-left {
  padding-bottom:0px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  }
  }
  
</style>

<div class="text-block-main" style="display:grid;grid-template-rows:auto auto;margin:0;padding-left:0;width:100%;" id="block1">
  <div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:40px auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);align-self:start;">Our Work</h1>
      <p style="align-self:start;padding-top:10px;margin-top:3%;" id="describe">Building an open and just scientific community</p>
    </div>
    <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/rcn_aims-trans.png" alt="Stakeholders" style="width=100%;">
       <!-- <figcaption>The sets of lead and affiliated data resources involved in this RCN. </figcaption> -->
      </figure>
    </div>
  </div>

<div class="text-block-right" style="display:grid;padding:0;margin-top:1%; margin-left:15%;margin-right:15%;width:60%;padding-left:5%;padding-right:5%;border: 1px solid #ec970b;" id="overview">
  <p style="align-self:start;padding-top:10px; text-align:center;" id="general"> We aim to improve data infrastructure for the Quaternary scientific community.</p> 
  <p style="text-align:center;">We will modify our repositories of fossil specimen data to make their holdings more <strong>accessible</strong>. We will make these repositories more <strong>equitable</strong> as well, especially for the Indigenous nations from whose lands the fossils have been excavated. We will train those who manage these data and those who use them for research purposes in <strong>best practices</strong> to maintain access and equity into the future. </p>
</div>
  
  <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:blue;padding:0px;" id="meatblock">
    <div class="text-block-right" style="display:grid;justify-content:space-around;padding-top:17px;margin-right:0px;padding-left:4.5%;padding-right:4.5%;width:91%;" id="aimses">
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="https://hoffmanick.github.io/fairos/aim1" style="font-size:1.4em">Aim 1:</a> Improve Interoperability and Reproducibility </h3>
        <p> We will develop guidance for interoperability among community-curated data resources and
        promote adoption of broader metadata standards. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="https://hoffmanick.github.io/fairos/aim2" style="font-size:1.4em">Aim 2:</a> Enable FAIR Data Curation and Stewardship </h3>
        <p style="text-align:center;">  We will promote better data science and curation practices among disciplinary practitioners, with a particular focus on early-career disciplinary researchers and develop and promote best practices and standards for data stewardship. </p>
      </div>
      <div class="text-block-right" style="max-width:500px;padding-left:0px;padding-top:0px;padding-bottom:0px;padding-right:5%; border-bottom: 1px solid #ec970b; border-right: 1px solid #ec970b; margin-left:3%; border-left: 1px solid #ec970b; width:90%; padding-left:2%;">
        <h3 style="border-bottom: 1px solid #ec970b;"> <a href="https://hoffmanick.github.io/fairos/aim3" style="font-size:1.4em">Aim 3:</a> Support Equity and Improve Access </h3>
        <p> We will democratize science in a manner that recognizes broader concepts of data ownership and ethical data curation. </p>
      </div>
    </div>
</div>
