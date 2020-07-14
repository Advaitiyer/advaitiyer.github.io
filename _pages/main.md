---
title: "About Me"
permalink: /
---

I am a Data Scientist who mines data and fits it into frameworks that generate business value. Through my academic and professional experience in Data Analytics and Management Consulting, I understand the use-case in short turnaround times, build a data collection methodology, and recommend a predictive/explanatory model with the optimal mixture of bias and variance. Multi-domain cross-functional work has helped me learn how to communicate boring technical insights to management professionals.

<body>
  <div class="container", style="width:80%;height:80%">
    <canvas id="Strengths"></canvas>
  </div>
  <script>
    let Strengths = document.getElementById('Strengths').getContext('2d');

    // Global Options
    Chart.defaults.global.defaultFontFamily = 'Lato';
    Chart.defaults.global.defaultFontSize = 18;
    Chart.defaults.global.defaultFontColor = '#777';

    let strengthsChart = new Chart(Strengths, {
      type:'doughnut', // bar, horizontalBar, pie, line, doughnut, radar, polarArea
      data:{
        labels:['Data Collection', 'Data Mining', 'Machine Learning', 'Hypothesis Testing', 'Data Visualization', 'Management Consulting'],
        datasets:[{
          label:false,
          data:[
            99,
            95,
            93,
            90,
            85,
            74
          ],
          backgroundColor:[
            'rgba(255, 99, 132, 0.6)',
            'rgba(54, 162, 235, 0.6)',
            'rgba(255, 206, 86, 0.6)',
            'rgba(75, 192, 192, 0.6)',
            'rgba(153, 102, 255, 0.6)',
            'rgba(255, 159, 64, 0.6)',
            'rgba(255, 99, 132, 0.6)'
          ],
          borderWidth:1,
          borderColor:'#777',
          hoverBorderWidth:3,
          hoverBorderColor:'#000'
        }]
      },
      options:{
        title:{
          display:true,
          text:'Strengths',
          fontSize:20
        },
        legend:{
          display:true,
          position:'top',
          labels:{
            fontColor:'#000'
          }
        },
        layout:{
          padding:{
            left:5,
            right:5,
            bottom:5,
            top:5
          }
        },
        tooltips:{
          enabled:true
        }
      }
    });
  </script>
</body>
