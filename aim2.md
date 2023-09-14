---
layout: default
title: Aim 2
permalink: /aim2
---

<style>
  @media print, screen and (max-width:480px) {
   #heading-left {
      padding-bottom: 0%;
      }
}
  li {
  font-size:20px;
  color:#000;
  }
.collapse {
  display: none;
  top: 63px;
  z-index:10000;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  margin-bottom:5%;
}

.show_b {
  display: grid;
  grid-template-rows: auto;
  
}

  .bttn {
  background-color:transparent;
  cursor:pointer;
  border: 0;
  border-bottom:1px solid #ec970b;
  padding-top:1%;
  font-size:17px;
  text-align:left;
  margin-bottom:min(4%,20px);
  }
  .bttn:hover {
  background-color:#faf3e8;
  }

  .bttn:hover p {
  font-weight:bold;
  }
  
  .bttn:hover strong {
  font-weight:900;
  }
  
  strong {
  color:#ec970b;
  }
  
  .bttn_show {
  border: 2.5px solid #ec970b;
  background-color:#faf3e8;
  }

  .bttn_show p {
  font-weight:bold;
  }
  
  .bttn_show strong {
  font-weight:900;
  }
  
    .show_b {
  <!-- width:150%; -->
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
  
  #title, #describe {
  width:100%;
  }
  
    @media print, screen and (max-width: 1070px) {
  #describe {
  width:100%;
  }
  }
  
      @media print, screen and (max-width: 1030px) {
  #describe {
  width:100%;
  }
  }
  
   @media print, screen and (max-width: 730px) {
  #describe {
  width:100%;
  }
  }
  
  
  @media print, screen and (max-width: 1055px) {
   #title {
  width:100%;
  }
  }
  
    @media print, screen and (max-width: 635px) {
   #title {
  width:100%;
  }
  }
  
    @media print, screen and (max-width: 435px) {
   #title, #describe {
  width:100%;
  }
  }
  
  #heading-image {
  width:100%;
  }
  
  #neo:hover #cap {
  display:block;
  }
  
  @media print, screen and (max-width: 720px) {
  .show_b {
  <!-- width:200%; -->
  }
  }
  
  @media print, screen and (max-width: 860px) {
  .show_b {
  width:95%;}
  }
  
    @media print, screen and (max-width: 660px) {
  #heading-image {
  width:90%;}
  }
  
   #main-text {
  <!-- width: 200%; -->
  position: relative;
  } 
  
  #fair-des {
  width:100%;
  margin-left: -20%;
  }
  
 @media print, screen and (max-width: 1300px) {
  #main-text {
  <!-- width: 170%; -->
  } 
  }

  
 @media print, screen and (max-width: 1215px) {
    #fair-des {
  width:100%;
  margin-left: -10%;
  }
  }
  
   @media print, screen and (max-width: 1180px) {
  #main-text {
  <!-- width: 150%; -->
  } 
  
    #fair-des {
  width:100%;
  margin-left: -5%;
  }
  }
  
     @media print, screen and (max-width: 1089px) {
  #main-text {
  <!-- width: 130%; -->
  } 
  
    #fair-des {
  width:100%;
  margin-left: 0%;
  }
  }
  
       @media print, screen and (max-width: 980px) {
  #main-text {
  <!-- width: 110%; -->
  } 
  }

         @media print, screen and (max-width: 890px) {
  #main-text {
  width: 100%;
  } 
  }
  

  </style>
<div class="text-block-main" style="display:grid;grid-template-columns: auto; margin-right:0px; width:100%;">
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;position:relative;" id="heading-left">
      <h1 id="title" style="font-size:calc(20px + 3vw);"> Aim 2: Advance Data Curation and Stewardship </h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Engaging Early Career Researchers, Disciplinary Scientists, and Data Managers</p>
    </div>
    <!-- <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%; align-self:center;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;max-width:500px;" id="neo">
        <img src="./images/neo_trans.png" alt="neotoma-eco" style="width:100%">
        <figcaption id="cap">Neotoma draws together a community of data managers and disciplinary practitioners working in Quaternary science. Williams, Grimm, Blois et al, 2018: The Neotoma Paleoecology Database, a multiproxy international, community-curated data resource. <i>Quaternary Research.</i></figcaption>
      </figure>
    </div> -->
  </div>
  <div class="text-block-right" style="display:grid;width:88%;padding-right:7%; padding-left:5%;justify-content:space-between;">
    <div>
    <h2>Overview</h2>
    <div id="main-text">
      <p>The Quaternary sciences have developed multiple mid-scale repositories containing large amounts of related but heterogeneously structured data. We must approach curation of this data from two perspectives. On the one hand, we must work with disciplinary scientists to train them in best practices for collecting and publishing data to support dissemination and reuse; on the other hand, we must also work with the data  managers to design best practices that facilitate data stewardship. As our RCN evolves, our activities may change. Currently we are planning the following activities. </p>
      <h2>Activities</h2> 

        <button class="bttn" id="os-casestudy" onclick="Func_oscasestudy()">
          <div><p><strong>Doing Open Science Across Disparate Data Types</strong></p></div>
      </button>
        <div class="collapse" id="readMore_os-casestudy">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p> Quaternary and modern organismal  and environmental data can be linked by place and time, despite differing data types. For example, organismal occurrence data is typically georeferenced with a latitude and longitude, as well as both date of collection and, for non-modern collections, temporal age of the  specimen. Workflows to combine organismal and environmental data (both paleo and modern) are already being created by many different data practitioners, but many are either not reproducible or not formalized into a published and shareable pipeline. By leveraging existing tools  to access and create interoperable data, and methods already commonly used by data practitioners to link data sources by spatial region and temporal span, we will create a model open science workflow aimed at data practitioners within the broader Quaternary science community. Developing this case study and workflow will highlight potential interoperability issues among Quaternary and modern data resources and feed into Aim 1 interoperability work. Using this workflow, we can create a simple biology-motivated case study investigating macro-scale biodiversity change in relation to environmental and anthropogenic changes. </p>
          </div>
       </div>
      <br>
          <button class="bttn" id="pracs" onclick="Func_pracs()"> 
            <div><p><strong>Guidance for Practitioners</strong></p></div>
      </button>
          <div class="collapse" id="readMore_pracs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Given the complexity of data resources within our disciplinary communities, a key need is guidance aimed at data generators on the set of options for data curation within different disciplinary communities. Early career researchers will also be engaged in data curation, and one outcome of their activities will be documentation of best practices to support the onboarding of data. This documentation may include
                <ul>
                  <li>a resource describing the scope of data repositories amongst the community,</li> 
                  <li>goals and aims of different community-curated data repositories,</li>
                    <li>types of data and formats accepted by community-curated data repositories, and </li> 
                  <li>checklists to facilitate ease of use.</li>
              </ul></p>
<p>The adoption of ethical open science principles depends not just on technical advances but also on establishing a culture of openness, literacy, and trust in FAIR and CARE principles. In order to disseminate ethical and open curatorial practices amongst the broader community, we will lead and facilitate training and outreach workshops at professional society meetings. To do this, we will convert the various best practices documentation into training videos and other introductory resources aimed at the core disciplinary practitioner communities. </p>
            </div>
      </div>
      <br>
      <button class="bttn" id="year3" onclick="Func_year3()"> 
          <div><p><strong>Guidance for Data Managers</strong></p></div>
      </button>
      <div class="collapse" id="readMore_year3">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>Interoperability and reproducibility are only part of the open science puzzle. Repositories require trust and practitioners require skills to implement sustainable ethical open science practices. We will promote the adoption of better data science and curation practices to support ethical open science in the future, and to preserve the critical role that small- and mid-scale data resources provide in the information architecture of the sciences. We will support the adoption of best practices through continued engagement with early career researchers and other RCN members. We will also focus on software practices that can support trust in online data repositories. 
</p>
          </div>
      </div>
    </div>
    </div>
  <!-- <div>
        <figure style="margin-right:0px;min-width:220px;" id="fair-des">
        <img src="./images/FAIR Diagram_v8.png" alt="FAIR Project Design" style="width:100%">
        <figcaption style="text-align:center;"></figcaption>
        </figure>
    </div> -->
  </div>
</div>

<script>
function Func_y2web() {
  document.getElementById("readMore_y2-web").classList.toggle("show_b");
  document.getElementById("y2-web").classList.toggle("bttn_show");
}

function Func_oscasestudy() {
  document.getElementById("readMore_os-casestudy").classList.toggle("show_b");
  document.getElementById("os-casestudy").classList.toggle("bttn_show");
}

  function Func_pracs() {
  document.getElementById("readMore_pracs").classList.toggle("show_b");
  document.getElementById("pracs").classList.toggle("bttn_show");
}

   function Func_year3() {
  document.getElementById("readMore_year3").classList.toggle("show_b");
  document.getElementById("year3").classList.toggle("bttn_show");
}



</script>
