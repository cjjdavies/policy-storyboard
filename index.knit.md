---
title: "Evaluating Scotland's AI Strategy - Ethical frameworks for the use of AI for mental health care and research"
output:
  flexdashboard::flex_dashboard:
    storyboard: true
    source: embed
    theme: 
      version: 4
      navbar-bg: "#5D085D"
---
<style>

.section.sidebar {
  font-family: Roboto;
  font-size: 1rem;
}

.storyboard-nav .sbframelist ul li.active {
  font-family: Roboto;
  font-size: 1rem;
  font-weight: 600;
  background: #5D085D;
}

.storyboard-nav .sbframelist ul li:not(.active) {
  font-family: Roboto;
  font-size: 1rem;
}

.storyboard-nav .sbframelist ul li:hover {
  color: white;
  font-family: Roboto;
  font-size: 1rem;
  font-weight: 600;
  background: #758A0C;
}

.intro {
  font-size: 1.5rem;
}

p {
  font-family: Roboto;
  font-size: 1rem;
}

</style>



Sidebar {.sidebar}
------
![](scotlands_ai_strategy.png){width=100%}

Student number: 52198593

Some aspects of this storyboard discuss aspects of mental health that may be distressing. If you feel upset or need someone to talk to, please contact the following in the UK:

[Samaritans - Scotland](https://www.samaritans.org/?nation=scotland): Call 116 123 - calls are free and available 24/7

If you are able, contact your GP for help.

### Introduction

<div class="intro">

Welcome to this storyboard, which has been designed to present an overview of [Scotland's AI Strategy](https://www.scotlandaistrategy.com/) and plans for the use of artificial intelligence in Scotland.

Mental health is an important aspect of everybody's life. These days there are many chatbots and digital apps that claim to be able to help people manage their mental health, but are they safe and effective?

The use of any kind of AI in mental health research and care carries considerable ethical concerns and unique risks. This storyboard considers the specific use of chatbots for managing mental health, and investigates the adequacy of ethical frameworks identified within the Strategy.

This storyboard presents the stages involved in the development of Scotland's AI Strategy, which was published in March 2021, and activities that have occurred since publication.
This Strategy is part of the Scottish Government's ongoing efforts to become 'digital nation' and is linked to more than 20 other policies and strategies, which can be explored in further detail via an interactive network diagram.

Some parts of this storyboard are interactive and can be explored in your browser.

Links to referenced policies and organisations can be found in the Policy Reference Table at the end of the storyboard.

### What is 'mental health'? {data-commentary-width=400}

![Diagram of the bio-psycho-social model of health, by Seth Falco, 2016; <a href="https://creativecommons.org/licenses/by-sa/4.0" title="Creative Commons Attribution-Share Alike 4.0">CC BY-SA 4.0</a>. This image has not been altered from the original.](Biopsychosocial_Model_of_Health_1.png){#fig-biopsychosocial width="50%"}

***
Mental health refers to cognitive, behavioral, and emotional well-being.

At the most fundamental level, mental health is seen as an interaction of biological, physical and social factors, known as the 'bio-psycho-social' model.

This model was first proposed by George Engel in 1977 as an effort to improve understanding of the different aspects of a person can influence good or poor mental health.

### Mental health in Scotland {data-commentary-width=400}

::: {layout-ncol=1}

![](health-boards-map.png){width="90%"}

-----

![Waffle plot showing the proportion of probable suicides for men and women in Scotland registered in 2020](waffle-plot_suicide2020.png){width="100%"}
:::

***

Within Europe, Scotland has the highest rate of 'excess mortality', otherwise known as unexplained mortality, of approximately 5000 people per year. Premature excess mortality - deaths of people under the age of 65 years - have been attributed to alcohol, drugs, suicide and violence. These deaths cannot be explained by deprivation or socio-economic environment.

In Scotland and the rest of the UK, different scales are used to measure well-being and potential mental health problems. One type of scale is the General Health Questionnaire (GHQ). The GHQ-12 scale uses scores from 0 to 12, with a score of 4 or more indicative of possible psychiatric disorders.

Aggregated scores from 2016-2017 revealed that 17% of people in Scotland aged 16 years and over reported a GHQ score of 4 or more. The map of health boards of Scotland shows Glasgow (with a red arrow), whose population has a higher score than the rest of Scotland: 20% of people reported a GHQ-12 score of 4 or more.

Data from [The Scottish Health Survey, 2022](https://scotland.shinyapps.io/sg-scottish-health-survey/)

In 2020 there were 805 probable suicides registered in Scotland. The 'waffle' plot below the map of Scotland illustrates the difference between men: 575 people, or 71%; and women: 230 people, or 29%.

Data from [The Scottish Public Health Observatory, 2022](https://www.scotpho.org.uk/health-wellbeing-and-disease/suicide/data/scottish-trends)

### Development of Scotland's AI Strategy and progress to date

<div class="knitr-options" data-fig-width="576" data-fig-height="460"></div>

```{=html}
<div id="htmlwidget-065b4d7d720b10cf3899" style="width:576px;height:460.8px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-065b4d7d720b10cf3899">{"x":{"data":[{"x":[18083.2,19288.8],"y":[0,0],"text":"","type":"scatter","mode":"lines","line":{"width":1.13385826771654,"color":"rgba(0,0,0,1)","dash":"solid"},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18199,18199,null,18227,18227,null,18512,18512,null,18513,18513,null,18569,18569,null,18708,18708,null,18808,18808,null,18813,18813,null,18815,18815,null,18875,18875,null,18943,18943,null,19024,19024,null,19034,19034,null,19081,19081,null,19191,19191],"y":[0.5,0,null,-0.5,0,null,1,0,null,-1,0,null,1.5,0,null,-1.5,0,null,2,0,null,0.5,0,null,-0.5,0,null,1,0,null,-1,0,null,1.5,0,null,-1.5,0,null,2,0,null,0.5,0],"text":"","type":"scatter","mode":"lines","line":{"width":0.755905511811024,"color":"rgba(0,0,0,1)","dash":"solid"},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18199,18227,18512,18513,18569],"y":[0,0,0,0,0],"text":"","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(100,143,255,1)","opacity":1,"size":11.3385826771654,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(100,143,255,1)"}},"hoveron":"points","name":"Development","legendgroup":"Development","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18708],"y":[0],"text":"","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(120,94,240,1)","opacity":1,"size":11.3385826771654,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(120,94,240,1)"}},"hoveron":"points","name":"Strategy Launch","legendgroup":"Strategy Launch","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18808,18813,18815,18875,18943,19024,19034],"y":[0,0,0,0,0,0,0],"text":"","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(220,38,127,1)","opacity":1,"size":11.3385826771654,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(220,38,127,1)"}},"hoveron":"points","name":"Delivery","legendgroup":"Delivery","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[19081],"y":[0],"text":"","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(254,97,0,1)","opacity":1,"size":11.3385826771654,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(254,97,0,1)"}},"hoveron":"points","name":"Update","legendgroup":"Update","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[19191],"y":[0],"text":"","type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(255,176,0,1)","opacity":1,"size":11.3385826771654,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(255,176,0,1)"}},"hoveron":"points","name":"Implementation","legendgroup":"Implementation","showlegend":true,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18138,18169,18199,18230,18260,18291,18322,18351,18382,18412,18443,18473,18504,18535,18565,18596,18626,18657,18688,18716,18747,18777,18808,18838,18869,18900,18930,18961,18991,19022,19053,19081,19112,19142,19173,19203,19234],"y":[-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1,-0.1],"text":["Aug","Sep","Oct","Nov","Dec","Jan","Mar","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec","Jan","Mar","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec","Jan","Mar","Mar","Apr","May","Jun","Jul","Aug"],"hovertext":["","","","","","","","","","","","","","","","","","","","","","","","","","","","","","","","","","","","",""],"textfont":{"size":11.3385826771654,"color":"rgba(0,0,0,1)"},"type":"scatter","mode":"text","hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18262,18628,18993],"y":[-0.2,-0.2,-0.2],"text":["2020","2021","2022"],"hovertext":["","",""],"textfont":{"size":15.1181102362205,"color":"rgba(0,0,0,1)"},"type":"scatter","mode":"text","hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18199,18227,18512,18513,18569],"y":[0.6,-0.6,1.1,-1.1,1.6],"text":["Steering Committee<br />Workshop 1","Steering Committee<br />workshop 2","The AI Of The<br />Possible","The AI of The<br />Possible 2","Working Group<br />Discussions"],"hovertext":["Title: Steering Committee Workshop 1<\/br><\/br>Type: Workshop Report<\/br>Strategy Stage: Development<\/br>Status: Complete","Title: Steering Committee workshop 2<\/br><\/br>Type: Workshop Report<\/br>Strategy Stage: Development<\/br>Status: Complete","Title: The AI Of The Possible: Developing Scotland’s Artificial Intelligence (AI) Strategy<\/br><\/br>Type: Consultation Report<\/br>Strategy Stage: Development<\/br>Status: Complete","Title: The AI of The Possible: Developing Scotland’s Artificial Intelligence (AI) Strategy, Public Engagement Report<\/br><\/br>Type: Consultation Report<\/br>Strategy Stage: Development<\/br>Status: Complete","Title: Key findings from the Working Group discussions<\/br><\/br>Type: Report<\/br>Strategy Stage: Development<\/br>Status: Complete"],"textfont":{"size":15.1181102362205,"color":"rgba(100,143,255,1)"},"type":"scatter","mode":"text","hoveron":"points","name":"Development","legendgroup":"Development","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18708],"y":[-1.6],"text":"Scotland’s AI<br />Strategy","hovertext":"Title: Scotland’s AI Strategy<\/br><\/br>Type: Strategy<\/br>Strategy Stage: Strategy Launch<\/br>Status: Complete","textfont":{"size":15.1181102362205,"color":"rgba(120,94,240,1)"},"type":"scatter","mode":"text","hoveron":"points","name":"Strategy Launch","legendgroup":"Strategy Launch","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[18808,18813,18815,18875,18943,19024,19034],"y":[2.1,0.6,-0.6,1.1,-1.1,1.6,-1.6],"text":["First 100 Days","AI Alliance<br />Engagement Workshop","Strategy & Playbook<br />Sessions Report","Personas Workshop<br />Report","User Requirements<br />Mapping Summary<br />Report","Participation<br />Strategy","Digital, Data and AI<br />Skills"],"hovertext":["Title: First 100 Days<\/br><\/br>Type: Key Milestone<\/br>Strategy Stage: Delivery<\/br>Status: Complete","Title: AI Alliance Engagement Workshop<\/br><\/br>Type: Workshop Report<\/br>Strategy Stage: Delivery<\/br>Status: Complete","Title: The Scottish AI Strategy & Playbook Sessions Report<\/br><\/br>Type: Feedback Report<\/br>Strategy Stage: Delivery<\/br>Status: Complete","Title: The Scottish AI Playbook Personas Workshop Report<\/br><\/br>Type: Workshop Report<\/br>Strategy Stage: Delivery<\/br>Status: Complete","Title: Scottish AI Playbook: User requirements mapping summary report<\/br><\/br>Type: Report<\/br>Strategy Stage: Delivery<\/br>Status: Complete","Title: Ensuring Full Participation in the Delivery of Scotland’s AI Strategy<\/br><\/br>Type: Case Study<\/br>Strategy Stage: Delivery<\/br>Status: Complete","Title: Digital, Data and AI Skills sector in Scotland<\/br><\/br>Type: Report<\/br>Strategy Stage: Delivery<\/br>Status: Complete"],"textfont":{"size":15.1181102362205,"color":"rgba(220,38,127,1)"},"type":"scatter","mode":"text","hoveron":"points","name":"Delivery","legendgroup":"Delivery","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[19081],"y":[2.1],"text":"State of AI Report","hovertext":"Title: State of AI Report<\/br><\/br>Type: Report<\/br>Strategy Stage: Update<\/br>Status: Complete","textfont":{"size":15.1181102362205,"color":"rgba(254,97,0,1)"},"type":"scatter","mode":"text","hoveron":"points","name":"Update","legendgroup":"Update","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[19191],"y":[0.6],"text":"Ethical and<br />Regulatory<br />Frameworks","hovertext":"Title: Develop ethical and regulatory frameworks for AI in Scotland<\/br><\/br>Type: Working Group<\/br>Strategy Stage: Implementation<\/br>Status: Delayed","textfont":{"size":15.1181102362205,"color":"rgba(255,176,0,1)"},"type":"scatter","mode":"text","hoveron":"points","name":"Implementation","legendgroup":"Implementation","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null}],"layout":{"margin":{"t":25.1483025610482,"r":7.30593607305936,"b":12.8012705975779,"l":10.958904109589},"plot_bgcolor":"rgba(255,255,255,1)","paper_bgcolor":"rgba(255,255,255,1)","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187},"xaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[18083.2,19288.8],"tickmode":"array","ticktext":["2020","2021","2022"],"tickvals":[18262,18628,18993],"categoryorder":"array","categoryarray":["2020","2021","2022"],"nticks":null,"ticks":"","tickcolor":null,"ticklen":3.65296803652968,"tickwidth":0,"showticklabels":false,"tickfont":{"color":null,"family":null,"size":0},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":false,"gridcolor":null,"gridwidth":0,"zeroline":false,"anchor":"y","title":{"text":"","font":{"color":null,"family":null,"size":0}},"hoverformat":".2f"},"yaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[-1.785,2.285],"tickmode":"array","ticktext":["-1","0","1","2"],"tickvals":[-1,0,1,2],"categoryorder":"array","categoryarray":["-1","0","1","2"],"nticks":null,"ticks":"","tickcolor":null,"ticklen":3.65296803652968,"tickwidth":0,"showticklabels":false,"tickfont":{"color":null,"family":null,"size":0},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":false,"gridcolor":null,"gridwidth":0,"zeroline":false,"anchor":"x","title":{"text":"","font":{"color":null,"family":null,"size":0}},"hoverformat":".2f"},"shapes":[{"type":"rect","fillcolor":null,"line":{"color":null,"width":0,"linetype":[]},"yref":"paper","xref":"paper","x0":0,"x1":1,"y0":0,"y1":1}],"showlegend":true,"legend":{"bgcolor":"rgba(255,255,255,1)","bordercolor":"transparent","borderwidth":1.88976377952756,"font":{"color":"rgba(0,0,0,1)","family":"","size":11.689497716895},"title":{"text":"Milestones","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187}}},"hovermode":"closest","barmode":"relative"},"config":{"doubleClick":"reset","modeBarButtonsToAdd":["hoverclosest","hovercompare"],"showSendToCloud":false},"source":"A","attrs":{"14d28361eb0b":{"yintercept":{},"type":"scatter"},"14d282c645af4":{"x":{},"y":{},"colour":{},"label":{},"yend":{},"xend":{}},"14d2833232d9a":{"x":{},"y":{},"colour":{},"label":{}},"14d2844a9cf34":{"x":{},"y":{},"colour":{},"label":{}},"14d28326901c2":{"x":{},"y":{},"colour":{},"label":{},"fontface":{}},"14d286814ce5a":{"x":{},"y":{},"colour":{},"label":{},"text":{}}},"cur_data":"14d28361eb0b","visdat":{"14d28361eb0b":["function (y) ","x"],"14d282c645af4":["function (y) ","x"],"14d2833232d9a":["function (y) ","x"],"14d2844a9cf34":["function (y) ","x"],"14d28326901c2":["function (y) ","x"],"14d286814ce5a":["function (y) ","x"]},"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
```


***

Information and navigation

- This timeline shows the various activities and outputs associated with the launch of Scotland's AI Strategy in March 2022, and over the past few months to date

- Hovering the cursor over the text will reveal summary information about each activity and output

- To zoom in, use the '+' icon at the top right, or click and drag the cursor across the area of interest

- To zoom out, use the '-' icon at the top right, or double click on the image

- Clicking one any of the 'Milestones' types in the legend will remove those types from the timeline allowing you to focus on specific types; clicking twice will remove all other types from the timeline

### Apps for managing mental health and sleep patterns {data-commentary-width=500}

![](appdiagram.png)

***

This diagram provides a summary of three apps for supporting different aspects of good mental health in the general population.

The Strategy contains a case study on 'Alli-chat' - a chatbot supported by the Scottish Government to help young people manage their mental health. This app may have been re-designed and launched as <a href="https://www.ubok.app/">'UB-OK'</a>.

The UB-OK app uses AI to provide therapeutic conversations on an ongoing basis. Its predecessor, Alli-chat, uses an algorithm known as natural language understanding - a form of AI that aims to create 'natural' conversation by recognising speech in the form of text and generating an appropriate response.

The apps <a href="https://www.trydaylight.com/">Daylight</a> and <a href="https://onboarding.sleepio.com/sleepio/nhs-sleepio/171#1/1">Sleepio</a> are both freely available for anyone in Scotland. Both apps are promoted by NHS Scotland and use Cognitive Behavioural Therapy approaches over a six-week period to help people manage anxiety and sleep difficulties respectively.

Sleepio is based on AI to deliver tailored guidance on improving sleep patterns.

Daylight has a 'fully automated' approach to providing guided CBT for worry, anxiety and management of General Anxiety Disorder.

An algorithm known as 'Natural Language Understanding' has been used in Alli-chat. This type of algorithm required large amounts of text to provide responses to text inputs from a user, based on a process known as 'pattern-matching'. In short, it uses text in its database to determine the most likely response to a phrase or query.

However, human language is very complex. Words may have different meanings depending on the context of how they are used in a sentence. This can lead to errors in responses from AI. These errors may be confusing or even distressing to some people, particularly children, who may not be aware of these problems and lack the emotional resources to manage inappropriate responses.

None of these apps are recommended for people with mental illness, and serious mental health problems, such as General Anxiety Disorder, despite the Daylight app stating this on the website. These apps are also not recommended for people in crisis or distress.

### Network diagram showing the relationships between Scotland's AI Strategy and other policies {data-commentary-width=500}

<div class="knitr-options" data-fig-width="576" data-fig-height="460"></div>

```{=html}
<div id="htmlwidget-c5555d87d6efcfac021b" style="width:100%;height:500px;" class="visNetwork html-widget"></div>
<script type="application/json" data-for="htmlwidget-c5555d87d6efcfac021b">{"x":{"nodes":{"id":[7,10,11,21,22,2,3,4,8,13,16,17,18,19,20,1,6,9,12,14,15,5],"label":["Scotland’s Digital Health and Care Strategy 2021","Transforming Places Together: digital strategy for planning","Scottish technology ecosystem: review","The AI Act","OECD AI in Society","AI Sector Deal","Centre for Data Ethics and Innovation","The Assessment List for Trustworthy Artificial Intelligence","A Fairer Scotland for Women: Gender Pay Gap Action Plan","Infrastructure Investment Plan for Scotland 2021-22 to 2025-26","UNICEF’s Policy Guidance on AI for Children","High-Level Expert Group on AI","National AI Strategy","Fostering a European Approach to Artificial Intelligence","How the EU Can Achieve Legally Trusthworthy AI","Scotland’s AI Strategy","The UN Convention on the Rights of the Child (UNCRC)","Cyber Resilient Scotland: strategic framework","iCAIRD","Digital Strategy for Scotland 2021","Scotland’s Vision for Trade","Life Science Strategy for Scotland 2025 Vision"],"group":["AI","AI","AI","AI","AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics, Mental Health & AI","Ethics, Mental Health & AI","Ethics, Mental Health & AI","Ethics, Mental Health & AI","Ethics, Mental Health & AI","Ethics, Mental Health & AI","Mental Health"],"value":[1,1,7,1,1,2,450,144,9,30,1043,1463,673,1221,2740,10,13,4,65,810,934,2],"ethics":[0,0,0,0,0,2,37,2,3,25,19,37,59,20,127,10,9,1,57,45,25,0],"mental.health":[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,5,2,1,4,1,2],"ai":[1,1,7,1,1,0,413,142,11,5,1024,1426,614,1201,2613,258,4,1,7,761,908,0]},"edges":{"from":[1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,10,16,17,18],"to":[2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,1,1,1,1],"weight":[10,2,450,144,2,13,1,9,4,1,7,0,65,30,1043,1463,673,1221,2740,1,1,1,4,3,4]},"nodesToDataframe":true,"edgesToDataframe":true,"options":{"width":"100%","height":"100%","nodes":{"shape":"dot"},"manipulation":{"enabled":false},"edges":{"width":"weight","arrows":"to"},"groups":{"AI":{"shape":"square","color":{"border":"#648FFF","background":"#648FFF"}},"Ethics & AI":{"shape":"square","color":{"border":"#DC267F","background":"#DC267F"}},"Ethics, Mental Health & AI":{"shape":"square","color":{"border":"#FE6100","background":"#FE6100"}},"useDefaultGroups":true,"Mental Health":{"shape":"square","color":{"border":"#FFB000","background":"#FFB000"}}},"interaction":{"navigationButtons":true,"hover":true,"zoomSpeed":1},"physics":{"solver":"forceAtlas2Based","forceAtlas2Based":{"gravitationalConstant":-50}}},"groups":["AI","Ethics & AI","Ethics, Mental Health & AI","Mental Health"],"width":"100%","height":"500px","idselection":{"enabled":false,"style":"width: 150px; height: 26px","useLabels":true,"main":"Select by id"},"byselection":{"enabled":false,"style":"width: 150px; height: 26px","multiple":false,"hideColor":"rgba(200,200,200,0.5)","highlight":false},"main":{"text":"Interactive network diagram showing relationships between key policies based on references to 'ethics', 'mental health' and 'AI'","style":"font-family: Roboto; font-size:1.25rem; text-align:center"},"submain":null,"footer":null,"background":"rgba(0, 0, 0, 0)","clusteringGroup":{"groups":["AI","Ethics & AI","Ethics, Mental Health & AI","Mental Health"],"label":"Cluster on group : ","shape":["database","database","database","database"],"color":["grey","grey","grey","grey"],"force":[false,false,false,false],"scale_size":[true,true,true,true]},"tooltipStay":300,"tooltipStyle":"position: fixed;visibility:hidden;padding: 5px;white-space: nowrap;font-family: verdana;font-size:14px;font-color:#000000;background-color: #f5f4ed;-moz-border-radius: 3px;-webkit-border-radius: 3px;border-radius: 3px;border: 1px solid #808074;box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);","highlight":{"enabled":true,"hoverNearest":true,"degree":1,"algorithm":"all","hideColor":"rgba(200,200,200,0.5)","labelOnly":true},"collapse":{"enabled":false,"fit":false,"resetHighlight":true,"clusterOptions":null,"keepCoord":true,"labelSuffix":"(cluster)"}},"evals":[],"jsHooks":[]}</script>
```


***

Information and navigation

- This network diagram shows the relationships between Scotland's AI Strategy and the various policies and strategies it references, based on the extent of 'relatedness' in terms of quantity of content discussing one or all of the themes of ethics, AI and mental health

- There are navigation buttons in the left bottom corner, which will allow you to move the diagram around the screen. Alternatively you can click the left mouse buttong and drag the diagram around the screen.

- The buttons in the bottom right of the screen will allow you to resize the diagram to fit your screen, and zoom in and out with the plus and minus buttons. You can also zoom in and out using the mouse wheel.

- Each of the coloured squares shows documents 'clustered' according to which of the themes they address, with the exception of the Life Science Strategy for Scotland, which only includes mental health and none of the other themes.

- Double-clicking with the left mouse button on one of the clusters will open that cluster and allow you to see the various policies and other documents linked to Scotland's AI Strategy. Clusters can be closed by double-clicking with the left mouse button on any of the cluster members.

- Within clusters, some squares will be bigger than others which indicates those documents have a greater quantity of content discussing particular themes. For example, within the 'Ethics & AI' cluster, the document 'How the EU can Achieve Legally Trustworthy AI' mentions ethics and AI more than the 'Infrastructure Investment Plan'.

- Below the navigation buttons in the bottom left corner, the 'Reinitialize clustering' button will close all clusters.

- To find out more about each of the linked policies, navigate to the Policy Reference Table tab at the top of the storyboard.

### Policy Reference Table

<div class="knitr-options" data-fig-width="576" data-fig-height="460"></div>

```{=html}
<div id="htmlwidget-e9f3748947685baf827e" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-e9f3748947685baf827e">{"x":{"style":"bootstrap4","filter":"none","vertical":false,"caption":"<caption style=\"caption-side: top; text-align: left;\">Table 1: Policies, strategies and organisations referenced within Scotland's AI Strategy with references to ethics, AI and mental health<\/caption>","fillContainer":true,"data":[["<img src=\"http://localhost/network-images/scotlands_ai_strategy.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/AI_sector_deal.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/centre_for_data_ethics_and_innovation.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/ALTAI.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/life_science_strategy_for_scotland.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/United_Nations_Convention_onthe_Rights_ofthe_Child.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/scotlands_digital_healthcare_strategy_2021.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/gender_paygap_action_plan.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/cyber_resilience_strategy.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/transforming_places_together.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/scottish_technology_ecosystem_review.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/iCAIRD.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/infrastructure_investment_plan.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/digital_strategy_2021.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/vision_for_trade.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/UNICEFs_policy_guidance_on_AI_for_children.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/high-level_expert_group_on_AI.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/national_ai_strategy.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/fostering_a_european_approach_to_AI.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/how_the_eu_can_achieve_legally_trustworthy_ai.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/the_AI_act.png\" height = \"80vh\"><\/img","<img src=\"http://localhost/network-images/OECD_AI_in_society.png\" height = \"80vh\"><\/img"],["<a href=\"https://www.scotlandaistrategy.com/\">Scotland’s AI Strategy<\/a>","<a href=\"https://www.gov.uk/government/publications/artificial-intelligence-sector-deal/ai-sector-deal\">AI Sector Deal<\/a>","<a href=\"https://www.gov.uk/government/organisations/centre-for-data-ethics-and-innovation\">Centre for Data Ethics and Innovation<\/a>","<a href=\"https://ec.europa.eu/newsroom/dae/document.cfm?doc_id=68342\">The Assessment List on Trustworthy AI<\/a>","<a href=\"https://www.lifesciencesscotland.com/wp-content/uploads/2017/08/Life-Sciences-Strategy-for-Scotland-2025-VisionFINALlow-res.pdf\">Life Sciences Strategy for Scotland 2025 Vision<\/a>","<a href=\"https://www.unicef.org.uk/wp-content/uploads/2010/05/UNCRC_united_nations_convention_on_the_rights_of_the_child.pdf\">The UN Convention on the Rights of the Child (UNCRC)<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2021/10/scotlands-digital-health-care-strategy/documents/enabling-connecting-empowering-care-digital-age/enabling-connecting-empowering-care-digital-age/govscot%3Adocument/enabling-connecting-empowering-care-digital-age.pdf\">Scotland’s Digital Health and Care Strategy 2021<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2019/03/fairer-scotland-women-gender-pay-gap-action-plan/documents/fairer-scotland-women-gender-pay-gap-action-plan/fairer-scotland-women-gender-pay-gap-action-plan/govscot%3Adocument/fairer-scotland-women-gender-pay-gap-action-plan.pdf\">A Fairer Scotland for Women: Gender Pay Gap Action Plan<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2021/02/strategic-framework-cyber-resilient-scotland/documents/strategic-framework-cyber-resilient-scotland/strategic-framework-cyber-resilient-scotland/govscot%3Adocument/strategic-framework-cyber-resilient-scotland.pdf\">Cyber Resilient Scotland: strategic framework<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2020/11/transforming-places-together-scotlands-digital-strategy-planning/documents/transforming-places-together-scotlands-digital-strategy-planning/transforming-places-together-scotlands-digital-strategy-planning/govscot%3Adocument/transforming-places-together-scotlands-digital-strategy-planning.pdf\">Transforming Places Together: digital strategy for planning<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/independent-report/2020/08/scottish-technology-ecosystem-review/documents/scottish-technology-ecosystem-review/scottish-technology-ecosystem-review/govscot%3Adocument/scottish-technology-ecosystem-review.pdf\">Scottish technology ecosystem: review<\/a>","<a href=\"https://icaird.com/\">The Industrial Centre for Artificial Intelligence Research in Digital Diagnostics (iCAIRD)<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2021/02/national-mission-local-impact-infrastructure-investment-plan-scotland-2021-22-2025-26/documents/national-mission-local-impact-infrastructure-investment-plan-scotland-2021-22-2025-26/national-mission-local-impact-infrastructure-investment-plan-scotland-2021-22-2025-26/govscot%3Adocument/national-mission-local-impact-infrastructure-investment-plan-scotland-2021-22-2025-26.pdf\">Infrastructure Investment Plan for Scotland 2021-22 to 2025-26<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2021/03/a-changing-nation-how-scotland-will-thrive-in-a-digital-world/documents/a-changing-nation-pdf-version/a-changing-nation-pdf-version/govscot%3Adocument/DigiStrategy.FINAL.APR21.pdf\">Digital Strategy for Scotland 2021<\/a>","<a href=\"https://www.gov.scot/binaries/content/documents/govscot/publications/strategy-plan/2021/01/scottish-government-vision-trade/documents/scotlands-vision-trade/scotlands-vision-trade/govscot%3Adocument/scotlands-vision-trade.pdf\">Scotland’s Vision for Trade<\/a>","<a href=\"https://www.unicef.org/globalinsight/reports/policy-guidance-ai-children\">UNICEF’s Policy Guidance on AI for Children<\/a>","<a href=\"https://digital-strategy.ec.europa.eu/en/policies/expert-group-ai\">High-level expert group on artificial intelligence<\/a>","<a href=\"https://www.gov.uk/government/publications/national-ai-strategy\">National AI Strategy<\/a>","<a href=\"https://ec.europa.eu/transparency/documents-register/api/files/COM(2021)205_0/de00000001034487?rendition=false\">Fostering a European Approach to AI<\/a>","<a href=\"https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3899991\">How the EU Can Achieve Legally Trusthworthy AI<\/a>","<a href=\"https://artificialintelligenceact.eu/the-act/\">The AI Act<\/a>","<a href=\"https://www.oecd.org/publications/artificial-intelligence-in-society-eedfee77-en.htm\">OECD AI in Society<\/a>"],["Ethics, Mental Health & AI","Ethics","Ethics & AI","Ethics & AI","Mental Health","Ethics, Mental Health & AI","AI","Ethics & AI","Ethics, Mental Health & AI","AI","AI","Ethics, Mental Health & AI","Ethics & AI","Ethics, Mental Health & AI","Ethics, Mental Health & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","Ethics & AI","AI","AI"]],"container":"<table class=\"table table-striped table-hover row-border order-column display fill-container\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>Policy Title<\/th>\n      <th>Key Theme<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"initComplete":"function(settings, json) {\n$('body').css({'font-family': 'Calibri'});\n}","columnDefs":[{"className":"dt-left","targets":"_all"},{"orderable":false,"targets":0}],"order":[[2,"asc"]],"pageLength":22,"autoWidth":false,"orderClasses":false,"lengthMenu":[10,22,25,50,100]}},"evals":["options.initComplete"],"jsHooks":[]}</script>
```


***

Information and navigation

- This table contains all the policies and strategies referenced in the network diagram, with direct links to the documents and websites in the Policy Title column.

- Documents are organised according to Key Theme, but can be organised by policy title.

- The search box allows for text searches.

### Summary of the Strategy's guidance on ethical frameworks for the use of AI

![](spiderman_meme.jpg)

***

Scotland's AI Strategy aims to be promoting AI for Scotland that is 'trustworthy, ethical and inclusive'.

It is difficult to identify practical guidance on ethical frameworks for AI as the Strategy points to other documents, which in turn reference other documents in a circular referencing system, as illustrated by this Spiderman meme.
