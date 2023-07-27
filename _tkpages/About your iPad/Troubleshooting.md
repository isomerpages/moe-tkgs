---
title: Troubleshooting
permalink: /hidden-pages/about-your-ipad/troubleshooting/
description: ""
third_nav_title: About your iPad
---
<style>
        .faq-item {
            margin-bottom: 5px;
        }

        .faq-item input {
            position: absolute;
            opacity: 0;
            z-index: -1;
        }

        .faq-item label {
            cursor: pointer;
	          font-size: 18px;
        }

        .faq-answer {
            max-height: 0;
	          font-size: 15px;
            overflow: hidden;
            transition: max-height 0.2s ease-out;
	          color: #e00d11;
        }

        .faq-item input:checked ~ .faq-answer {
            max-height: 100vh;
        }
    </style>


<h3>iPad Related</h3>
<div class="faq-item">
    <input id="q1" type="checkbox">
    <label for="q1">iPad is not responding.</label>
    <p class="faq-answer">Please perform a force restart for your iPad.<br> Click <a rel="noopener" target="_blank" href="https://support.apple.com/en-us/HT212017">here</a>&nbsp;for instruction on how to do so. <br></p>
	</div>
<div class="faq-item">
    <input id="q2" type="checkbox">
    <label for="q2">iPad is laggy/slow.</label>
    <p class="faq-answer">Please check that there is sufficent space left in your iPad. We recommend to have at least 1GB of free storage space in order for iPad to function properly. <br></p>
</div>
<div class="faq-item">
    <input id="q3" type="checkbox">
    <label for="q3">iPad is always struck on Mobile Guardian page.</label>
    <p class="faq-answer">Please make sure that your iPad is connected to an active internet connection and with <a rel="noopener" target="_blank" href="/hidden-pages/about-your-ipad/the-dont/">Low Power Mode</a>&nbsp;switched off.<br></p>
</div>
<div class="faq-item">
    <input id="q4" type="checkbox">
    <label for="q4">Apps requires updating.</label>
    <p class="faq-answer">Please launch the Mobile Guardian app to trigger the updating of apps. Click <a rel="noopener" target="_blank" href="/hidden-pages/about-your-ipad/approved-apps/">here</a>&nbsp;for more information<br></p>
</div>

<h3>Logitech Rugged Combo 3 Related</h3>
<div class="faq-item">
    <input id="q5" type="checkbox">
    <label for="q5">My keyboard is not working.</label>
    <p class="faq-answer">Remove the iPad from the casing and reinsert it again.<br>Should the keyboard remains unresponsive, please approach the ICT personnel for help.</p>
</div>

<h3>Apple Pencil</h3>
<div class="faq-item">
    <input id="q6" type="checkbox">
    <label for="q6">Pencil is not responding.</label>
    <p class="faq-answer">Please ensure that the pencil is fully charged and bluetooth on the iPad is switched on. If problem persist, please re-pair the pencil to your iPad again.<br></p>
	</div>
<div class="faq-item">
    <input id="q7" type="checkbox">
    <label for="q7">Pencil is connected but not responding.</label>
    <p class="faq-answer">Restart your iPad and check if the tip on the Pencil requires replacement.<br></p>
</div>
<div class="faq-item">
    <input id="q8" type="checkbox">
    <label for="q8">Pencil could not be inserted into iPad for charging.</label>
    <p class="faq-answer">Check if the charging port on the iPad is not obstructed.<br></p>
</div>

<!-- Use the following code to add more -->
<!--
<div class="faq-item">
    <input type="checkbox" id="q<continue with previous number>">
    <label for="q<continue with previous number>">.</label>
    <p class="faq-answer"><br></p>
</div>
-->