---
layout: default
title: "Glossary"
permalink: /glossary
---

<style>
  
div.text-block-main {
  padding-left: 5%
  }

  #heading-image {
  padding-top: 0px;
  padding-bottom: 0px;
  margin-left:0px;
  margin-right:0px;
  align-self:center;
  }
  
  #scroll {
  margin-left:0px;
  margin-right:0px;
  }
  
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
  background-color: #fff;
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
  margin-bottom:4%;
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
  color: #ec970b;
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
  
 
  

</style>



<div class="text-block-right" style="display:grid;grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));background-image:linear-gradient(to left, #fff, 90%, #97b779);padding:0;margin-right:0;width:100%;" id="headingblock">
    <div class="text-block-right" style="display:grid;grid-template-rows:auto auto;background-color:transparent;padding-left:5%;align-content:center;width:95%;" id="heading-left">
      <h1 style="font-size:calc(20px + 3vw);align-self:start;">Glossary</h1>
      <p style="align-self:start;padding-top:10px;" id="describe">Learn more about our key words.</p>
    </div>
   <!-- <div class="text-block-right" style="background-color:transparent;padding-left:0;float:right;justify-self:end; margin-right:5%; margin-left: 5%; width: 90%;max-width:250px;" id="heading-image">
      <figure id="scroll">
        <img src="./images/scroll-trans.png" alt="scroll" style="width=100%;max-width:250px;">
        <figcaption></figcaption>
      </figure>
    </div> -->
  </div>
  
  
  
<div class="text-block-right" style="display:grid;;width:88%;padding-right:7%;padding-left:5%;justify-content:space-between;">
    <div id="main-text">
      <h2>Key Terms</h2> 
        <button class="bttn" id="care" onclick="Func_care()">
            <div><p><strong>The CARE Principles</strong></p></div>
</button>
        <div class="collapse" id="readMore_care">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
          <p><a href="https://datascience.codata.org/articles/10.5334/dsj-2020-043">The CARE principles</a> (Collective Benefit, Authority to Control, Responsibility and Ethics) were formulated by Stephanie Russo Carroll, Ibrahim Garba, Oscar L. Figueroa-Rodriguez and other members of the Research Data Alliance's International Indigenous Data Sovereignty Interest Group, in order to help navigate the tension between 1) protecting Indigenous rights and interests in Indigenous data, and 2) supporting open data. The CARE principles build on a tradition of advocacy for Indigenous Peoples' sovereign rights, and assert that
            <ol>
              <li>the use of Indigenous data must yield collective benefit for Indigenous Peoples</li>
              <li>the authority to control who has access to Indigenous data must lie with Indigenous Peoples</li>
              <li>those who use Indigenous data must recognize their responsibility to build reciprocal relationships with the communities from which the data derive, and </li>
              <li>the use of Indigenous data must occur in a fundamentally ethical framework.</li>
            </ol></p>
          </div>
        </div>
    <br>
        <button class="bttn" id="fair" onclick="Func_fair()">
          <div><p><strong>The FAIR Principles</strong></p></div>
      </button>
        <div class="collapse" id="readMore_fair">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p><a href="https://www.nature.com/articles/sdata201618">The FAIR principles</a> (Findable, Accessible, Interoperable, and Reusable) were formalized by Mark D. Wilkinson, Michael Dumontier, IJsbrand Jan Aalbersberg and other participants at the 'Jointly Designing a Data Fairport' Workshop in Leiden, Netherlands, 2014. These data-centric principles assert that data should be easily findable and described with rich metadata, universally accessible and free to use, interoperable among different data ecosystems, and able to be reused for future scientific analysis. </p>
          </div>
       </div>
        <br>
          <button class="bttn" id="quat" onclick="Func_quat()"> 
            <div><p><strong>The Quaternary Research Community</strong></p></div>
      </button>
          <div class="collapse" id="readMore_quat">
            <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
              <p>The Quaternary research community is a network of scientists and data managers who study the archaeology, climate, and ecology of the Quaternary period, 
                a division of the <a href="https://rock.geosociety.org/net/documents/gsa/timescale/timescl.pdf?v=2022">Cenozoic Era</a>. The Quaternary period began with the Pleistocene Epoch 2.58 million years ago and continues today, and is characterized by long cold ice ages interrupted by short warmer interglacial ages.</p>
            </div>
      </div>
        <br>
     <!-- <button class="bttn" id="data" onclick="Func_data()"> 
          <div><p><strong>Data Science Terminology</strong></p></div>
      </button>
      <div class="collapse" id="readMore_data">
          <div class="read-more-content" style="width:90%;padding-left:5%;padding-right:5%;padding-top:2%;padding-bottom:2%;">
            <p>What words like ontology mean?</p>
          </div>
      </div> -->
    </div>
</div>

<script>
function Func_care() {
  document.getElementById("readMore_care").classList.toggle("show_b");
  document.getElementById("care").classList.toggle("bttn_show");
}

function Func_fair() {
  document.getElementById("readMore_fair").classList.toggle("show_b");
  document.getElementById("fair").classList.toggle("bttn_show");
}

  function Func_quat() {
  document.getElementById("readMore_quat").classList.toggle("show_b");
  document.getElementById("quat").classList.toggle("bttn_show");
}

   function Func_data() {
  document.getElementById("readMore_data").classList.toggle("show_b");
  document.getElementById("data").classList.toggle("bttn_show");
}



</script>
