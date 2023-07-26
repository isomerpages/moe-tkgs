---
title: Troubleshooting
permalink: /hidden-pages/about-your-ipad/troubleshooting/
description: ""
third_nav_title: About your iPad
---
<style>
        .faq-item {
            margin-bottom: 20px;
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
        }

        .faq-item input:checked ~ .faq-answer {
            max-height: 100vh;
        }
    </style>



<div class="faq-item">
    <input id="q1" type="checkbox">
    <label for="q1">My iPad is not responding</label>
    <p class="faq-answer">Please perform a force restart for your iPad.<br> Click <a rel="noopener" target="_blank" href="https://support.apple.com/en-us/HT212017">here</a> for instruction on how to do so. </p><p>
</p></div>
<div class="faq-item">
    <input id="q2" type="checkbox">
    <label for="q2">My keyboard is not working</label>
    <p class="faq-answer">Remove the iPad from the casing and reinsert it again.<br>Should the keyboard remains unresponsive, please approach the ICT personnel for help.</p>
</div>
<div class="faq-item">
    <input id="q3" type="checkbox">
    <label for="q3">My iPad is laggy/slow.</label>
    <p class="faq-answer">Please reboot your iPad</p>
</div>
<div class="faq-item">
    <input id="q4" type="checkbox">
    <label for="q4">Question 2</label>
    <p class="faq-answer">Answer to question 2.</p>
</div>

<!-- Add more FAQs as needed -->