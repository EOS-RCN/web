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
              <li>Symposium 3 (2025): <a target="_blank" href="https://eos-rcn.github.io/web/symposium2025">Agenda</a>, <a target="_blank" href="https://drive.google.com/drive/folders/1RELrNfykXBO32Xd6Y5L7YYRDMhwVvV5X">Google Drive Directory</a></li>
              </ol>
</p>
            </div>
      </div>
  <div class="collapse" id="readMore_info-landscape">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>Led by Lieberman, LeFebvre, Thomer, and Balk, we developed a <a href="https://zenodo.org/records/14537346">structured self-reflection tool</a> to engage in a deep-dive reflection about ethical open science, FAIR, and CARE within both our personal scientific practice and within the policies of our organizations. We expect that our answers to these questions will change over time. The purpose of this self-reflection is to gain an initial honest assessment of where we are as practitioners and where our repositories are now in terms of implementing the FAIR and CARE principles in our scholarship.</p>
          </div>
        </div>

  <div class="collapse" id="readMore_reading">
  <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p>We have begun a reading group in order to learn together about a variety of topics relating to the intertwining of our repositories with legacies of colonial violence. Readings so far have included: 
          <ul>    <li>11/12/25: <a href="https://www.inthelibrarywiththeleadpipe.org/2025/digital-opaque/"> Purcell et al. 2025 </a>, on an ethical intervention in the display of biomedical material with fraught collection histories </li>
            <li>10/08/25: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5302085/"> Levin & Leonelli 2016</a>, situating the Open Science movement with respect to questions of value </li>
            <li>09/10/25: <a href="https://conbio.onlinelibrary.wiley.com/doi/10.1111/conl.13090"> Derham et al. 2025 </a> & <a href="https://conbio.onlinelibrary.wiley.com/doi/10.1111/conl.13107"> Fletcher's response</a>, an exchange on the relationship between rewilding and Indigenous land care</li>
            <li>08/13/25: <a href="https://asistdl.onlinelibrary.wiley.com/doi/10.1002/asi.24938"> Mattern et al. 2024 </a> on a political-economic theory of undersharing research data </li>
            <li>07/09/25: <a href="https://www.jstor.org/stable/44744739?seq=1"> Devictor and Bensaude-Vincent 2016 </a> on the "invention" of global biodiversity </li>
            <li>06/11/25: <a href="https://journals.sagepub.com/doi/full/10.1177/0306312718772086"> Mirowski 2018 </a> on the political economic context of the Open Science movement </li>
            <li>05/14/25: <a href="https://doi.org/10.1515/opar-2020-0213"> Borjesson 2021 </a> surveying knowledge infrastructure architectures in archaeology </li>
            <li>04/17/25: <a href="https://www2.archivists.org/groups/native-american-archives-section/protocols-for-native-american-archival-materials-information-and-resources-page"> Protocols for Native American Archival Material </a> </li>
            <li>03/11/25: <a href="https://digital.lib.washington.edu/server/api/core/bitstreams/4456a262-4c1e-4dc9-b4bd-abc56f3e799b/content"> Palmer et al. (2025)</a> on contextual integrity for Indigenous data </li>
            <li>02/11/25: <a href="https://www.nature.com/articles/s41467-024-53480-2"> Jennings et al. (2025)</a> on governance of Indigenous data in open earth systems science</li>
            <li>01/08/25: <a href="https://www.tandfonline.com/doi/full/10.1080/08003831.2024.2410112" target="_blank"> Taitingfong et al. (2025)</a> on implementing CARE with FAIR through Indigenous Peoples' protocols</li>
            <li>11/08/24: <a href="https://drive.google.com/file/d/1S-qEj0_GCSnFRub4QmChps_f4iaq6mOC/view" target="_blank"> McKinley et al. (2023)</a> on evaluation of geoscience education programs using Traditional Knowledge</li>
            <li>10/09/24: <a href="https://www.anticolonialresearchlibrary.org/wp-content/uploads/2024/06/Frontiers-in-Ecol-Environ-2024-Gazing-Wolf-Centering-Indigenous-Knowledges-in-ecology-and-beyond.pdf" target="_blank">Gazing Wolf et al. (2024)</a> on centering Indigenous knowledges in ecology</li>
    <li>06/20/24: <a href="https://datascience.codata.org/articles/10.5334/dsj-2024-037" target="_blank">O'Brien et al. (2022)</a> on guidance for implementing CARE in earth science data repositories</li>
      <li>05/07/24: <a href="https://www.nature.com/articles/s41559-021-01608-8" target="_blank">Raja et al. (2022)</a> on sampling bias resulting from parachute science in paleontology</li>
      <li>04/02/24: <a href="https://philsci-archive.pitt.edu/21039/1/FAIRandCAREData-April6-2022.pdf" target="_blank">Sterner & Elliott (2022)</a> on the communities privileged by FAIR and CARE data principles</li>
    <li>03/05/24: <a href="https://clas.osu.edu/sites/clas.osu.edu/files/Tuck%20and%20Yang%202012%20Decolonization%20is%20not%20a%20metaphor.pdf" target="_blank">Tuck & Yang (2012)</a> on the use and abuse of the language of decolonization, and </li>
    <li>02/06/24: <a href="https://www.gida-global.org/ieee-provenance" target="_blank">a draft IEEE standard</a> for recording Indigenous data provenance.</li>
      <li>11/29/23: <a href="https://www.tandfonline.com/doi/abs/10.1080/14926150903118342">Hatcher et al. (2009)</a> on integrating two-eyed seeing into educational curricula</li>
      <li>10/25/23: <a href="https://www.cambridge.org/core/journals/advances-in-archaeological-practice/article/nagpra-nexus-institutional-integrity-and-the-evolving-role-of-archaeological-laboratories/9792A90811AF5CC351B2DD59BD5529A7">Thompson et al. (2023)</a> on using NAGPRA to more broadly revisit an archaeological lab's relationship to the curation of artifacts with Indigenous cultural affiliation</li>
    <li>09/27/23: <a href="https://www.cambridge.org/core/journals/advances-in-archaeological-practice/article/care-principles-and-the-reuse-sharing-and-curation-of-indigenous-data-in-canadian-archaeology/D94CDC00AC7FD5E365A28C668C2812AF">Gupta et al. (2023)</a> on the CARE principles in Canadian archaeology</li>
    </ul></p>
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



<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript">
  $(document).ready(function() {
    if (window.location.href.indexOf("reading") > -1) {
      document.getElementById("readMore_reading").classList.toggle("show_b");
      document.getElementById("reading").classList.toggle("bttn_show");  
    }
  });
</script>

<script type="text/javascript">
  $(document).ready(function() {
    if (window.location.href.indexOf("pracs") > -1) {
      document.getElementById("readMore_pracs").classList.toggle("show_b");
      document.getElementById("pracs").classList.toggle("bttn_show");
    }
  });
</script>
