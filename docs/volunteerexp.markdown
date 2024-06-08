---
layout: page
title: Volunteer Experience
permalink: /volunteerexp
---


<!-- see notes for overhaul ideas -->




<!-- ## ############################################## ## -->
<!-- ## Images captured in markdown to be used in html ## -->
<!-- ## ############################################## ## -->

{% capture ctwimage %} 
![Clean the world](assets/images/cleantheworld.jpeg){: style="width: 155px; height: auto; border-radius: 15px; float: right; object-fit: cover; margin-left: 10px; margin-top: 7px"}
{% endcapture %}

<!-- ## ############################################## ## -->
<!--                  ## Introduction ##                  -->
<!-- ## ############################################## ## -->

Volunteering is the basis for social change. Social change, to me, is the persistent striving for the betterment of our communities at large. This betterment ultimately involves providing help, awareness, and goodness without expecting return. This social change starts with those who are in the position to provide the most help at the most opportune time.

Below is my timeline of Volunteering Experiences, I hope to grow this list as I grow likewise.

<html>
<head>
    <style>

<!-- ## ############################################## ## -->
<!--                 ## Timeline Styling ##               -->
<!-- ## ############################################## ## -->

        .timeline { /* This creates the space to the left of our timeline-item where teh date and other content can be placed */
          position: relative;
        }

        .timeline-item {
          display: flex;
          margin-bottom: 50px; /* space between each entry */
        }

        .date {
          flex: 0 0 120px; /* width */
          text-align: right;
          margin-right: 20px;
          font-weight: bold;
        }

        .timeline-content {
          /* This new div class is empty to keep markdownify images unchanged. Becareful changing this. */
        }
        
        
        
        
        
        
        

    </style>
</head>

    
<!-- ## ############################################## ## -->
<!--              ## Volunteer Timeline ##             ## -->
<!-- ## ############################################## ## -->
    
<body>
    <script></script><!--<hr>--><br>
    
    
    
        <!-- 

        Use this template below to create a new entry:

        <div class="timeline">
        <div class="timeline-item">
        <div class="date">Semester 2049</div>
        <div class="timeline-content">
          <h3>Title</h3>
          {{ VARIABLE | markdownify }}<p>Paragraph text</p>
        </div>
        </div>

        -->
    
    <!-- Volunteer UCF Fall 2023 -->
    
    <div class="timeline">
    <div class="timeline-item">    <hr>
    <div class="date">Fall 2023</div>
    <div class="timeline-content">
      <h3>Volunteer UCF</h3>
      {{ ctwimage | markdownify }}<p>Involved myself in student-run orginization dedicated to allowing students to get envolved in community research around the Orlando area. I engaged in many projects over the Semester including <i>Clean The World Sorting</i>, where I helped sort soap and other hygine products for recycling; assisted <i>Knights Pantry</i> with moving backlogs of items in storage; creating Holiday Cards for Children; helped <i>United Against Poverty</i> with food donation sorting; and gave water out for a hosted 5 and 2 mile race sponsored by <i>Advent Health</i>.</p>
    </div>
    </div>
    </div>
    
    <!-- Summer Student Front Desk Intern BTHS Summer 2021 -->

    <div class="timeline">  
    <div class="timeline-item">  <hr>
    <div class="date">Summer 2021</div>
    <div class="timeline-content">
      <h3>Summer Student Front Desk Intern</h3>
      {{ VARIABLE | markdownify }}<p>In this position I oversaw and managed front desk duties including organizing mail, answering calls, and handled communication with parents and school personnel. I also learned professional etiquette and accountability.</p> 
    </div>  
    </div>  <!--<hr>-->
    </div>
    
    
    
  
        
        
</body>
</html>
