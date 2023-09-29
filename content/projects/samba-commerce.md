---
title: "Samba Commerce Dashboard"
date: 2023-09-25
draft: false
author: "Muhammad Shalhan Assalam"
tags:
    - E-Commerce
    - Segmentation
    - Data Visualization
    - EDA
    - Tableau
    - Looker
image: /images/samba-commerce/main.jpg
description: ""
toc:
---

## Situation
As data analyst in Samba Commerce, the CEO ask me to make dashboard to capture and understand more metrics and make the business data more comprehensive and insightful. 

### Backround

You are a data analyst at one of the fast growing ecommerce in Brazil named Samba Commerce, which just launched in 2021. Samba Commerce offers more than 15k products, and more than 50 product categories to the customers all over Brazil. There are a number of internal and external variables that support our business growth. We want to utilize more data to support our growth in 2022.

Mr. Ronaldinho (CEO), requested Mr Neymar (head of data) to create a company wide dashboard. Mr Neymar trust you to create the dashboard.

> “Olá, as per my explanation in our Analytics town hall our Company’s **main OKR** (Objectives and Key Results) this year is about **transactions**. So Mr. CEO requested a dashboard for *company-wide* to understand our business performance better. The bigger picture is there in our current dashboard, I need your help to capture more metrics and revamp our dashboard to be **more comprehensive and insightful.**”

### Problem Definition

Samba Commerce aims to solve the problem of lacking a centralized platform for monitoring and analyzing crucial business metrics. Without a dashboard solution, Samba Commerce acknowledges that stakeholders and decision-makers may struggle to access a comprehensive view of key performance indicators (KPIs), potentially resulting in time-consuming data analysis and misalignment among team members and stakeholders.

### Objective

This project aims to create executive and operational dashboards that offer a unified display of critical business metrics. These dashboards will empower stakeholders to oversee business performance, detect trends, analyze data, and make informed choices. The objective is to improve comprehension, productivity, and teamwork by delivering a visual and interactive platform for exploring, analyzing, and communicating data.

- **Who**
    - The dashboard will be used by **various stakeholders within the company**, including executives, managers, and analysts.
- **Why**
    - The dashboard provides them with the data they need **to get insights about the company’s performance**.

## Task & Action

1. First thing, we upload the data source into looker/tableau based on Samba Commerce dataset. 
2. Next, we connect related variable between sheets (same as ERD join function in SQL).
    <br> <img src='/images/samba-commerce/relation.png' alt='Samba Commerce dataset relationship'>

### Dashboard UI
We create 3 menus for this dashboard :
1. Executive Dashboard
2. CRM Dashboard + Extra view

<div class='tableauPlaceholder' id='viz1695987652844' style='position: relative; width: 100%; max-width: 800px; height: 600px;'><noscript><a href='#'><img alt='Executive Dashboard ' src='https://public.tableau.com/static/images/QW/QWS4QGPWR/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared/QWS4QGPWR' /> <param name='toolbar' value='yes' /><param name='static_image' value='https://public.tableau.com/static/images/QW/QWS4QGPWR/1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1695987652844');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if (divElement.offsetWidth > 800) {
        vizElement.style.width = '100%';
        vizElement.style.height = '600px';
    } else if (divElement.offsetWidth > 500) {
        vizElement.style.width = '100%';
        vizElement.style.height = '600px';
    } else {
        vizElement.style.width = '100%';
        vizElement.style.height = '600px';
    }
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>



Now, here's the view of CRM Dashboard
<div class='tableauPlaceholder' id='viz1695987331702' style='position: relative; width: 100%; max-width: 800px; height: 600px;'><noscript><a href='#'><img alt=' ' src='https://&#x2F;&#x2F;public.tableau.com&#x2F;static&#x2F;images&#x2F;GJ&#x2F;GJYKQ7296&#x2F;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;GJYKQ7296' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#x2F;&#x2F;public.tableau.com&#x2F;static&#x2F;images&#x2F;GJ&#x2F;GJYKQ7296&#x2F;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1695987331702');
    var vizElement = divElement.getElementsByTagName('object')[0];
    if (divElement.offsetWidth > 800) {
        vizElement.style.width = '100%';
        vizElement.style.height = '600px';
    } else if (divElement.offsetWidth > 500) {
        vizElement.style.width = '100%';
        vizElement.style.height = '600px';
    } else {
        vizElement.style.width = '100%';
        vizElement.style.height = '600px';
    }
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Another version Looker Studio
<iframe width="790" height="491" src="https://lookerstudio.google.com/embed/reporting/e8f39e97-d185-419d-8914-0828de8573a3/page/VbsZD" frameborder="0" style="border:0" allowfullscreen></iframe>


## Result - Deck

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQSrZDMo910RD70VanqzMntPx8Z4RQsxDr4j54QCjVhdg_fXwMTS0XLXJuy6ZqDlmnVkMqfK8UdjQmc/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="496" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

---

### Attachments

<a href="https://docs.google.com/spreadsheets/d/1Sj_wXgy49BGxqZVmn0L1A8jgUHft-e2d/edit?usp=sharing&ouid=113457939531194487813&rtpof=true&sd=true" target="_blank">>> Dataset Link <<</a> | <a href="https://public.tableau.com/app/profile/muhammad.shalhan.assalam/viz/SambaCommerce_16915976142170/ExecutiveDashboard" target="_blank">>> Tableau Link <<</a> | <a href="https://lookerstudio.google.com/reporting/e8f39e97-d185-419d-8914-0828de8573a3" target="_blank">>> Looker Link <<</a>
---

I'm grateful you took the time to explore my portfolio site and view my work. Your interest means a lot. 

Feel free to provide any feedback or ask questions - I welcome your thoughts. Thank you again for checking out my projects and considering my skills. I appreciate you taking the time to do so.

<a href="https://www.linkedin.com/in/muhammad-shalhan-assalam-b42973200/" target="_blank">>> Let's get in touch on LinkedIn! <<</a> | <a href="https://public.tableau.com/app/profile/muhammad.shalhan.assalam/vizzes" target="_blank">>> Visit my Tableau Profile! <<</a>

