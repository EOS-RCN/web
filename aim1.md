---
layout: default
title: Aim 1
permalink: /aim1
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
<div class="text-block-main" style="display:grid;grid-template-columns: auto;margin-right:0px;width:100%;">
  
<div class="text-block-right" style="display:grid;background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;align-content:center;justify-content:space-between;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;position:relative;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);"> Aim 1: Improve Interoperability and Reproducibility </h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Building Interconnected and Open Data Resources</p>
    </div>
  <!--  <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end;max-width:460px; margin-right:5%; margin-left: 5%;" id="heading-image">
      <figure style="margin-left:0px;margin-right:0px;max-width:300px;" id="quilter">
        <img src="./images/interoperable_quilt.png" alt="quilt" style="width:100%">
        <figcaption id="cap">Making systems interoperable is a kind of quilting. Image originally from Rocky Mountain Quilt Museum. Thomer and Rayburn, 2023: “A Patchwork of Data Systems”: Quilting as an Analytic Lens and Stabilizing Practice for Knowledge Infrastructures. <i>Science, Technology, & Human Values.</i></figcaption>
      </figure>
    </div> -->
  </div>
  <div class="text-block-right" style="display:grid; width:88%;padding-right:7%; padding-left:5%;justify-content:space-between;">
    <div>
    <h2>Overview</h2>
    <div id="main-text">
      <p>Our work is just beginning and will likely evolve over time. Currently, we plan to develop a network of data managers, research practitioners, disciplinary experts, and early career researchers focused on identifying gaps and mismatches among Quaternary data resources, in order to improve interoperability among them. We will particularly prioritize: <ul>
      <li>outreach to data managers and assessment of the current Quaternary informatics landscape,</li>
      <li>identifying areas for crosswalk development to resolve conflicts between existing ontologies and to help support the adoption of CARE aims,</li>
        <li>identifying points of connection between repositories, where the addition of related identifiers could help bridge silos, and</li> 
        <li>building on existing initiatives to make data resources more open and interconnected.</li></ul></p>
      <h2>Activities</h2> 
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p><strong>An Informatics Landscape Analysis</strong></p></div>
</button>
        <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>The aim of this analysis is to map the current Quaternary informatics landscape, evaluate current interoperability efforts, and recommend best practices going forward, with a focus on several widely used data resources spanning different domains. </p>
            <p>We will evaluate 
              <ol>
              <li>the semantic  <i>coverage</i> of each repository (e.g. what data elements are captured by each repository, and what are the  specific meanings of those elements?) </li>
              <li>points of <i>convergence and conflict</i> between repositories (e.g. what data elements overlap and which are fundamentally mismatched?)</li>
              <li>the <i>completeness</i> of records within repositories, and</li>
              <li>points for further curatorial intervention—places where additional data curation could make records more accessible, interoperable, or ethical.</li></ol></p>
          </div>
        </div>
  <br>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p><strong>Creating Interoperable Data</strong></p></div>
      </button>
          <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>Many legacy Quaternary datasets are found in specimen-curation repositories, like museums, with database structures designed to capture specimen-specific long-tail data and often curated decades past without regard to FAIR or CARE principles. This case study will focus on expanding FAIR data curation protocols from the ZooArchNet (ZAN) project to 
                <ol>
<li>link legacy museum-curated zooarcheological data across various community-curated data repositories, and</li>
                  <li>align with CARE guidelines and descendant  community priorities.</li></ol></p>
<p>ZAN has already created pathways to standardize, crosswalk and link zooarchaeological datasets across archaeological and biological repositories. In this case study, UF personnel will work with RCN informatics domain experts and repository data managers, in consultation with Indigenous stakeholders, to expand the ZAN protocols. Continued work on data standards alignments, Linked Open Data, and other intersectional methods will  be used to mobilize Darwin Core-enabled legacy zooarchaeological data from the Florida Museum curation database across multiple repositories.</p>
<p>Our work will be grounded in consultation with descendant community members and tribal authorities to ensure that their interests are represented in our decisions of how to integrate CARE principles within open data sharing. Our tribal collaborators will form an integral part of our use case activities, ensuring that any data sharing is culturally appropriate, ethical, and in support of tribal priorities involving the documentation and protection of environmental resources and cultural heritage. This effort will represent a proof-of-concept workflow and produce best-practice guidelines for such interdisciplinary, inter-repository FAIR and CARE open sharing of legacy curated data that will be disseminated via workshops for the archaeological and zooarchaeological communities.  
</p>
            </div>
      </div>
    <br>
      <button class="bttn" id="guidelines" onclick="Func_guidelines()"> 
          <div><p><strong>Guidelines for Data Alignment</strong></p></div>
      </button>
      <div class="collapse" id="readMore_guidelines">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>Data managers will draw on findings from the Mapping the Landscape effort, webinars, hackathon, and the case study to develop specific guidelines for alignment between Quaternary data resources. Unlike many crosswalks, we will focus on aligning repositories rather than individual datasets, and will center the specific integration needs of the Quaternary community. Likely outcomes will include 
              <ul>
                <li>best practices for setting up repository APIs or other access points, </li> 
                <li>crosswalks between repository schemas,</li>
                <li>guidance for the implementation and use of external APIs to help manage links to external data, and</li>
                <li>the use of Science on Schema or other external ontologies for reporting data.</li></ul>  </p>
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
function Func_infolandscape() {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
}

function Func_symphack() {
  document.getElementById("readMore_symp-hack").classList.toggle("show_b");
  document.getElementById("symp-hack").classList.toggle("bttn_show");
}

  function Func_casestudy() {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");
}

   function Func_guidelines() {
  document.getElementById("readMore_guidelines").classList.toggle("show_b");
  document.getElementById("guidelines").classList.toggle("bttn_show");
}



</script>
