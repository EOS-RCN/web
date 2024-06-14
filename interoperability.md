---
layout: default
title: Improving Interoperability
permalink: /interoperability
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
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;grid-template-columns:3fr 1fr;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;position:relative;" id="heading-left">
      <h1 id="title" style="font-size:calc(20px + 3vw);">Improving Interoperability</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Building interconnected and open data resources</p>

    </div>
              <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end; margin-right:5%; margin-left: 5%; width: 90%;" id="heading-image">
      <figure id="stakes">
        <img src="./images/rcn_aims-trans.png
" alt="org-chart" style="width=100%;">
        <figcaption></figcaption>
      </figure>
    </div>

  </div>
  <div class="text-block-right" style="display:grid;width:95%;padding-left:5%;justify-content:space-between;">
    <div>
     <h2>Overview</h2>
    <div id="main-text">
      <p>We are developing a network of data managers, research practitioners, disciplinary experts, and early career researchers focused on identifying gaps and mismatches among Quaternary data resources, in order to improve interoperability among them. We are focusing on: <ul>
      <li>outreach to data managers and assessment of the current Quaternary informatics landscape,</li>
      <li>identifying areas for crosswalk development to resolve conflicts between existing ontologies and to help support the adoption of CARE aims,</li>
        <li>identifying points of connection between repositories, where the addition of related identifiers could help bridge silos, and</li> 
        <li>building on existing initiatives to make data resources more open and interconnected.</li></ul></p>
      <h2>Activities</h2> 
      <div style="display:grid;grid-template-columns:1fr 2fr;height:fit-content;">
        <div id="buttons">
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p><strong>An Informatics Landscape Analysis</strong></p></div>
</button>
      
  <br>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p><strong>Creating Interoperable Data</strong></p></div>
      </button>
        
    <br>
          <button class="bttn" id="pracs" onclick="Func_pracs()"> 
            <div><p><strong>Constituent Database Landing Pages</strong></p></div>
      </button>
      </div>
      <div id="texts" style="margin-left:2vw;">
          <div class="collapse" id="readMore_pracs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>One of our focal repositories, the <a href="https://www.neotomadb.org/" target="_blank">Neotoma Paleoecology Database</a>, is a federated database constituted by a set of more specialized paleoecological databases that focus on the curation of data from some particular configuration of time, space, and proxy type. We are developing landing pages for these constituent Neotoma databases that offer up-to-date information on the spatial and temporal coverage of the database in question, as well as information on the kinds of datasets contained in the database, the people who have contributed data to the database, and the growth of the database over time. These constituent database landing pages increase the transparency of Neotoma's holdings, allowing for enhanced exploration of paleoecological data. They also facilitate the identification of errors in our stewardship (for instance, they make it easy to see records that purport to concern 8 billion year old pollen!)</p>
              <p>In addition to the development of these database landing pages, we have modified Neotoma's already existing dataset-landing pages to include cultural provenance information at the site level. We have begun to map the extent of Indigenous territories intersecting Neotoma sites as recorded by the <a href="https://native-land.ca/" target="_blank">Native Land</a> project, and link to the Native Land landing pages for those territories.</p>

            </div>
      </div>
        <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Quaternary science often yields heterogeneous datasets. These complex records can include physical specimens (e.g., faunal remains, sediment cores, human artifacts), assemblage-level occurrence data, trait measurements (e.g., stable isotopic ratios, osteometrics), and chronologies. A diverse set of data repositories now curate Quaternary data, but different elements of the data and metadata from a single site may be better fits for some data repositories than others and repositories may overlap in scope. This presents disciplinary practitioners with the daunting task of navigating an increasingly opaque data ecosystem, and choosing the better resource for data upload often depends on tacit expertise. This working group will develop a set of tools and recommendations for navigating this complex landscape, through case studies of particular sites. 
</p>
            </div>
      </div>
  <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>Led by Thomer and Raia, we are conducting interviews with data resource users and repository managers to understand use of community-curated data resources, needs and visions for interoperability of these resources, and data ethics related to FAIR and CARE principles. The findings from this study will be used to inform technical improvements to community-curated data resources and development of guidelines to enable researchers to make their data more interoperable, reproducible, and ethical. </p>
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
