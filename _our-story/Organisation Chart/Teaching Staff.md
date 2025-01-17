---
title: Teaching Staff
permalink: /our-story/Organisation-Chart/Teaching-Staff/
description: ""
third_nav_title: Organisation Chart
variant: markdown
---
<div class="yck-component">
<ul class="jekyllcodex_accordion">
  <li>
    <input type="checkbox" id="accordion1">
    <label for="accordion1">Design and Enterprise Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/01DNT2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/02DNT2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/03dnt2025.png">
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion2">
    <label for="accordion2">Humanities Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/01humanities2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/02humanities2025.png">
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion3">
    <label for="accordion3">Mathematics and Principles of Accounts Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/01mathspoa2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/02mathspoa2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/03mathpoa2025.png">
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion4">
    <label for="accordion4">Mother Tongue Languages Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/01mtl2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/02mtl2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/03mtl2025.png">
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion5">
    <label for="accordion5">Physical Education Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/01pe2025.png">
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion6">
    <label for="accordion6">Science Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/01science2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/02science2025.png">
        <img src="/images/Our%20Story/Organisation%20Chart/03science2025.png">
      </p>
    </div>
  </li>
  <li>
    <input type="checkbox" id="accordion7">
    <label for="accordion7">English Language Department</label>
    <div>
      <p>
        <img src="/images/Our%20Story/Organisation%20Chart/Teaching%20Staff/English%20Language%20Department/English_R17.png">
      </p>
    </div>
  </li>
</ul>
</div>

<style>
.yck-component .jekyllcodex_accordion li {
    margin-bottom: 10px;
	  list-style: none;
  }

.yck-component .jekyllcodex_accordion input[type="checkbox"] {
    display: none;
  }

.yck-component .jekyllcodex_accordion label {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    cursor: pointer;
	 font-size: clamp(1.2656rem, 1.2363rem + 0.1467vw, 1.35rem);
  }
	
.yck-component .jekyllcodex_accordion label::before {
	   display: none;
}
 
.yck-component .jekyllcodex_accordion label::after {
    content: '+';
    transition: transform 0.3s ease;
  }

.yck-component .jekyllcodex_accordion input[type="checkbox"]:checked + label::after {
    transform: rotate(45deg);
  }
	
.yck-component .jekyllcodex_accordion div {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease-out, opacity 0.3s ease-out;
    opacity: 0;
  }

.yck-component .jekyllcodex_accordion input[type="checkbox"]:checked + label + div {
    max-height: 1000px;
    opacity: 1;
    transition: max-height 0.3s ease-in, opacity 0.3s ease-in;
  }

.yck-component .jekyllcodex_accordion img {
    max-width: 100%;
    height: auto;
  }
	
</style>