---
layout: default
title: Outreach
permalink: /outreach
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
 /* margin-bottom:5%; */
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
  margin-bottom:1%;
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
  border: 3px solid rgba(151,183,121,0.7);
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
  
  #quilter:hover #cap {
  display:block;
  }
    
  .read-more-content {
  background-color: #fff;
  }
  
  @media print,screen and (max-width: 680px) {
  .read-more-content p {
  font-size: 0.15em;
  }
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

  
    #heading-image {
  <!-- width:120%; -->
  }
  
      @media print, screen and (max-width: 660px) {
  #heading-image {
  width:90%;}
  }
  
 #main-text {
  width: 90%;
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
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;grid-template-columns: 3fr 1fr;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;position:relative;" id="heading-left">
      <h1 id="title" style="font-size:calc(20px + 3vw);">Outreach & Education</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Training for the next
      generation of Quaternary informaticians</p>
    </div>
                  <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/eos_circle.png
" alt="org-chart" style="width=100%;">
        <figcaption></figcaption>
      </figure>
    </div>


  </div>
  <div class="text-block-right" style="display:grid;width:95%;padding-left:5%;justify-content:space-between;">
    <div>
     <h2>Overview</h2>
    <div id="main-text">
      <p>Our goal is to help scholars across career levels navigate an increasingly complex data ecosystem and to practice ethical science in their work.</p>
      <h2>Activities</h2> 
      <div style="display:grid;grid-template-columns:1fr 2fr;height:fit-content;">
        <div id="buttons">
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p><strong>Doing Open Science Across Disparate Data Types</strong></p></div>
</button>
      
  <br>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p><strong>FAIR/CARE Educational Material</strong></p></div>
      </button>
        
    <br>
          <button class="bttn" id="pracs" onclick="Func_pracs()"> 
            <div><p><strong>Database Recommender</strong></p></div>
      </button>
      </div>
      <div id="texts" style="margin-left:2vw;">
          <div class="collapse" id="readMore_pracs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Quaternary science often yields heterogeneous datasets. These complex records can include physical specimens (e.g., faunal remains, sediment cores, human artifacts), assemblage-level occurrence data, trait measurements (e.g., stable isotopic ratios, osteometrics), and chronologies. A number of repositories that specialize in the curation of each of these distinct data elements has arisen, ranging from individual researcher databases to museums to online data aggregators. While many of these resources enable high-quality Quaternary data preservation, they also present disciplinary practitioners with the daunting task of navigating an increasingly opaque data ecosystem.</p> 
              <p>To help researchers navigate this complex data ecosystem, we are developing database recommender tools. These tools will allow researchers to input some basic datasets parameters (e.g., time and region, kind of specimen, kind of measurement) and output data curation recommendations.</p>

            </div>
      </div>
        <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Our aim is to introduce future scientists to principles of ethical open data and Indigenous data sovereignty. We are therefore developing modular curricula, which can be inserted into introductory undergraduate courses in data science or ecology, to familiarize students with the FAIR principles and CARE principles. Students will explore case studies focused on Quaternary data that cause them to consider the oftentimes invisible infrastructures and practices that enable FAIR and CARE-aligned data curation, as well as explore what gaps there are in Quaternary data with regard to FAIR and CARE. 
</p>
            </div>
      </div>
  <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>Disparate data types are already being combined by data practitioners via linked open data (LOD). These linkages rely on knowing the spatial region and temporal span of an observation or data record. These workflows adhere to the FAIR data principles.</p>

<p>Similar to FAIR principles, CARE principles have become widely adopted - but seemingly only in the communities most obviously affected in the Natural Sciences: Indigenous, Archaeological, Anthropological, Zooarchaeological, and Ethnography disciplines. Much of the adherence to CARE has been through new, ground-up development of data resources. The incorporation of CARE into biological and paleontological data use is lacking, partly due to historic reasons and partly due to lack of awareness by communities.</p>

<p>Our goal is to incorporate CARE data principles and practices into already established data resources that adhere to FAIR and Open Science principles. While some of this work requires infrastructure building, much of this work can be done by influencing the practices of data users to effect change in the ethos of the next generation of data practitioners.</p>

<p>This project will have three outcomes: 1) the development of a working methodology for incorporating CARE practices into research that spans time and disciplines; 2) the use of this methodology for a scientific research endeavor; and 3) the teaching of this methodology to early career researchers, in order to effect change in our communities.</p>
          </div>
        </div>
</div>
    </div>
    </div>

  </div>
</div>
</div>
<script>
  function Func_infolandscape() {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");

    if (document.getElementById("readMore_pracs").classList.contains("show_b")) {
  document.getElementById("readMore_pracs").classList.toggle("show_b");
  document.getElementById("pracs").classList.toggle("bttn_show");
  }

    if (document.getElementById("readMore_case-study").classList.contains("show_b")) {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");
  }
    
}


  function Func_casestudy() {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");

  if (document.getElementById("readMore_pracs").classList.contains("show_b")) {
  document.getElementById("readMore_pracs").classList.toggle("show_b");
  document.getElementById("pracs").classList.toggle("bttn_show");
  }

        if (document.getElementById("readMore_info-landscape").classList.contains("show_b")) {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
  }
    
}



  function Func_pracs() {
  document.getElementById("readMore_pracs").classList.toggle("show_b");
  document.getElementById("pracs").classList.toggle("bttn_show");

    if (document.getElementById("readMore_case-study").classList.contains("show_b")) {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");
  }

      if (document.getElementById("readMore_info-landscape").classList.contains("show_b")) {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
  }
    
}




</script>
