---
title: test CCA
permalink: /cca/Sports-and-Games/testcca/
description: ""
---
<head>
	<style>
		
.accordion > input[name="collapse"] {
  position: absolute;
  left: -100vw; /* Behind the scene */
}
			
.accordion .content {
  background: #fff;
  overflow: hidden;
  height: 0;
  transition: 0.5s;
  box-shadow: 1px 2px 4px rgba(0, 0, 0, 0.3);
}
		
		.accordion label {
  color: #fff;
  cursor: pointer;
  font-weight: normal;
  padding: 10px;
  background: #b0100c;
  
}
 
.accordion label:hover,
.accordion label:focus {
  background: #252525;
}
 
.accordion .handle label:before {
  font-family: FontAwesome;
  content: "\f107";
  display: inline-block;
  margin-right: 10px;
  font-size: 1em;
  line-height: 1.556em;
  vertical-align: middle;
  transition: 0.4s;
  
}
 
.accordion > input[name="collapse"]:checked ~ .handle label:before {
    transform: rotate(180deg);
    transform-origin: center;
    transition: 0.4s;
}
	.accordion > input[name="collapse"]:checked ~ .content {
  height: 380px;
  transition: height 0.5s;
}
	</style>
	</head>

<section class="accordion">
  <input type="radio" name="collapse" id="handle1" checked="checked">
  <h2 class="handle">
    <label for="handle1">
    The Visible Short Heading 
    </label>
  </h2>
  
  <div class="content">
    <p>Your detailed contents...</p>  
  </div>
</section>