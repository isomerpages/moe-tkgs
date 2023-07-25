---
title: Clubs & Service Boards
permalink: /cca/clubs-n-service-boards/
description: ""
---



    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 15px;
        }

        .faq-item input {
            position: absolute;
            opacity: 0;
            z-index: -1;
        }

        .faq-item label {
            cursor: pointer;
        }

        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.2s ease-out;
        }

        .faq-item input:checked ~ .faq-answer {
            max-height: 100vh;
        }
    </style>



<h1>FAQs for iPad</h1>

<table>
    <tbody><tr class="faq-item">
        <th>
            <input id="q1" type="checkbox">
            <label for="q1">Question 1</label>
        </th>
        <td class="faq-answer">
            Answer to question 1.
        </td>
    </tr>

    <tr class="faq-item">
        <th>
            <input id="q2" type="checkbox">
            <label for="q2">Question 2</label>
        </th>
        <td class="faq-answer">
            Answer to question 2.
        </td>
    </tr>
    <!-- Add more FAQs as needed -->
</tbody></table>



