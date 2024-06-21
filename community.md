---
layout: default
title: Community Building
permalink: /community
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
      <h1 id="title" style="font-size:calc(20px + 3vw);">Community Building & Reflection</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Convening stakeholders in Quaternary data</p>
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
      <p>We are creating a community-based network focused on facilitating dialogue and collaboration among communities and individuals who are vested in different forms of environmental data about the past, including their cultural and natural provenance and stewardship. We actively reflect on Western scientific approaches to open Quaternary science, and aim to facilitate cross-cultural dialogue across disciplinary, professional, and personal cultural backgrounds and traditions of participants.</p>
      <h2>Activities</h2> 
      <div style="display:grid;grid-template-columns:1fr 2fr;height:fit-content;">
        <div id="buttons">
        <button class="bttn" id="info-landscape" onclick="Func_infolandscape()">
            <div><p><strong>Structured Self-Reflection</strong></p></div>
</button>
      
  <br>
          <button class="bttn" id="case-study" onclick="Func_casestudy()"> 
            <div><p><strong>Annual Symposia</strong></p></div>
      </button>
        
    <br>
          <button class="bttn" id="pracs" onclick="Func_pracs()"> 
            <div><p><strong>Webinar Series</strong></p></div>
      </button>
          <br>
          <button class="bttn" id="reading" onclick="Func_reading()"> 
            <div><p><strong>Reading Group</strong></p></div>
      </button>
      </div>
      <div id="texts" style="margin-left:2vw;">
          <div class="collapse" id="readMore_pracs">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>We have organized a webinar series for experts in informatics to offer lessons to our community. Topics so far have included
              <ul>
              <li>a series of introductions to Quaternary databases,</li>
              <li>an overview of the past and present intertwining of paleontology with structures of domination, and </li>
              <li>a guide from LocalContexts on using their cultural metadata fields.</li>
              </ul>
             <p> Click <a href="https://eos-rcn.github.io/web/webinarview" target="_blank">here</a> to learn more.</p></p>

            </div>
      </div>
        <div class="collapse" id="readMore_case-study">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>We meet yearly in-person to advance project aims, with focused time for group reflection on how to think together about implementing ethical open science in our data ecosystems, furthering all our aims. All symposia will include activities specifically devoted to advancing FAIR and CARE principles, in order to help set desired professional norms and provide examples of how CARE implementation can be advanced. 
              <ol>
              <li>Symposium 1 (2023): <a target="_blank" href="https://eos-rcn.github.io/web/symposium2023">Agenda</a>, <a target="_blank" href="https://drive.google.com/drive/folders/1U6gJujYwoEdjTn71YNIv6yMio2H23gSP">Google Drive Directory</a></li>
              <li>Symposium 2 (2024): <a  target="_blank" href="https://eos-rcn.github.io/web/symposium2024">Agenda</a>, <a target="_blank" href="https://drive.google.com/drive/folders/1mhUOxJekxAIlwwpbFUun540j2fOiIIsW">Google Drive Directory</a></li>
              </ol>
</p>
            </div>
      </div>
  <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>Led by Lieberman, LeFebvre, Thomer, and Balk, we developed a structured self-reflection tool to engage in a deep-dive reflection about ethical open science, FAIR, and CARE within both our personal scientific practice and within the policies of our organizations. We expect that our answers to these questions will change over time. The purpose of this self-reflection is to gain an initial honest assessment of where we are as practitioners and where our repositories are now in terms of implementing the FAIR and CARE principles in our scholarship.</p>
          </div>
        </div>

  <div class="collapse" id="readMore_reading">
  <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>We have begun a reading group in order to learn together about a variety of topics relating to the intertwining of our repositories with legacies of colonial violence. Readings so far have included, among others, 
    <ul><li><a href="https://www.nature.com/articles/s41559-021-01608-8" target="_blank">Raja et al. (2022)</a> on sampling bias resulting from parachute science in paleontology</li>
    <li><a href="https://clas.osu.edu/sites/clas.osu.edu/files/Tuck%20and%20Yang%202012%20Decolonization%20is%20not%20a%20metaphor.pdf" target="_blank">Tuck & Yang (2012)</a> on the use and abuse of the language of decolonization, and </li>
    <li><a href="https://www.gida-global.org/ieee-provenance" target="_blank">a draft IEEE standard</a> for recording Indigenous data provenance.</li></ul></p>
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
          if (document.getElementById("readMore_reading").classList.contains("show_b")) {
  document.getElementById("readMore_reading").classList.toggle("show_b");
  document.getElementById("reading").classList.toggle("bttn_show");
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

            if (document.getElementById("readMore_reading").classList.contains("show_b")) {
  document.getElementById("readMore_reading").classList.toggle("show_b");
  document.getElementById("reading").classList.toggle("bttn_show");
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

        if (document.getElementById("readMore_reading").classList.contains("show_b")) {
  document.getElementById("readMore_reading").classList.toggle("show_b");
  document.getElementById("reading").classList.toggle("bttn_show");
  }
    
}

  function Func_reading() {
  document.getElementById("readMore_reading").classList.toggle("show_b");
  document.getElementById("reading").classList.toggle("bttn_show");

    if (document.getElementById("readMore_case-study").classList.contains("show_b")) {
  document.getElementById("readMore_case-study").classList.toggle("show_b");
  document.getElementById("case-study").classList.toggle("bttn_show");
  }

      if (document.getElementById("readMore_info-landscape").classList.contains("show_b")) {
  document.getElementById("readMore_info-landscape").classList.toggle("show_b");
  document.getElementById("info-landscape").classList.toggle("bttn_show");
  }

    if (document.getElementById("readMore_pracs").classList.contains("show_b")) {
  document.getElementById("readMore_pracs").classList.toggle("show_b");
  document.getElementById("pracs").classList.toggle("bttn_show");
  }

    
}




</script>
