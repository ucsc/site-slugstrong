---
layout: page
title: Tracking COVID-19
description: >
  Tracking COVID-19.  
sidebar: false
category: reporting
weight: 2
button:
  bg: '#3d7068ff'
  color: '#fff'
  icon: "flask-10.svg"
back: "/reporting-covid/"
back_text: Back
---
  {% if page.back %}
The COVID-19 dashboard provides a regularly updated status on COVID-19 at UCSC. The UCSC testing data in the dashboard will be updated on those days when complete testing data is available for a 24-hour period during which asymptomatic testing was conducted. This data will help inform decisions about on-campus operations and activities.

The data includes the daily total number of tests run through the UCSC Molecular Diagnostic Lab and the daily total of new cases. The data includes a seven-day average positivity rate for all tests performed through the campus testing program.

UCSC cautions against drawing broad conclusions from the data about the prevalence of COVID-19 on campus, particularly since the student data set includes symptomatic and asymptomatic individuals and only data collected through the campus testing program. 
<a href="{{ page.back }}" class="pill tracking-back">{% include svg/arrow-72.svg %}{{ page.back_text }}</a>
{% endif %}
<script type='text/javascript' src='https://visualizedata.ucop.edu/javascripts/api/viz_v1.js'></script><div class='tableauPlaceholder' style='width: 1000px; height: 850px;'><object class='tableauViz' width='1000px' height='850px' style='display:none;'><param name='host_url' value='https%3A%2F%2Fvisualizedata.ucop.edu%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='&#47;t&#47;UCSCpublic' /><param name='name' value='COVID-19TestingDashboardUCSC&#47;COVID-19Graphs' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='showAppBanner' value='true' /><param name='display_count' value='n' /><param name='isGuestRedirectFromVizportal' value='y' /></object></div>
