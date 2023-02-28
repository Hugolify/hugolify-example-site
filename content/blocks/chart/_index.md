---
isPage: true
draft: false
title: Chart
description: Add different chart (bar, line, pie…)
image:
  src: /images/uploads/bar-chart.svg
hero:
  cta:
    blank: false
    url: "#main"
    text: Discover
  cta_second:
    blank: true
    text: Documentation
    url: https://github.com/hugolify/hugolify-template/wiki/block-chart
  title: Block chart
  text: Add different charts like bar, line, pie, radar… (with Chart JS library)

    - https://www.chartjs.org/
blocks:
  - type: chart
    title: Chart pie example
    grid: small
    chart:
      type: pie
      title: Chart pie example
      items:
        - label: Example 1
          value: 60
          color: "#6699bb"
        - label: Example 2
          value: 20
          color: "#337799"
        - label: Example 3
          value: 30
          color: "#115577"
        - label: Example 4
          value: 45
          color: "#003355"
  - type: chart
    title: Chart bar example
    grid: medium
    chart:
      type: bar
      title: Chart bar example
      items:
        - label: Example 1
          value: 60
          color: "#6699bb"
        - label: Example 2
          value: 20
          color: "#337799"
        - label: Example 3
          value: 30
          color: "#115577"
        - label: Example 4
          value: 45
          color: "#003355"
  - type: chart
    title: Chart line example
    grid: large
    chart:
      type: line
      title: Chart line example
      items:
        - label: Example 1
          value: 60
          color: "#6699bb"
        - label: Example 2
          value: 20
          color: "#337799"
        - label: Example 3
          value: 30
          color: "#115577"
        - label: Example 4
          value: 45
          color: "#003355"
  - type: chart
    title: Chart doughnut example
    grid: small
    chart:
      type: doughnut
      title: Chart doughnut example
      items:
        - label: Example 1
          value: 60
          color: "#6699bb"
        - label: Example 2
          value: 20
          color: "#337799"
        - label: Example 3
          value: 30
          color: "#115577"
        - label: Example 4
          value: 45
          color: "#003355"
  - type: chart
    title: Chart polarArea example
    grid: small
    chart:
      type: polarArea
      title: Chart polarArea example
      items:
        - label: Example 1
          value: 60
          color: "#6699bb"
        - label: Example 2
          value: 20
          color: "#337799"
        - label: Example 3
          value: 30
          color: "#115577"
        - label: Example 4
          value: 45
          color: "#003355"
  - type: chart
    title: Chart radar example
    grid: small
    chart:
      type: radar
      title: Chart radar example
      backgroundColor: "rgba(50, 100, 150, 0.2)"
      borderColor: "rgba(50, 100, 150)"
      items:
        - label: Eating
          value: 65
        - label: Drinking
          value: 59
        - label: Sleeping
          value: 90
        - label: Designing
          value: 81
        - label: Coding
          value: 56
        - label: Cycling
          value: 55
  - type: chart
    title: Chart polarArea example
    text: via expert mode (json)
    chart:
      type: polarArea 
      data:
        lang: JSON
        json: |-
          {
            labels: [
              'Red',
              'Green',
              'Yellow',
              'Grey',
              'Blue'
            ],
            datasets: [{
              label: 'My First Dataset',
              data: [11, 16, 7, 3, 14],
              backgroundColor: [
                'rgb(255, 99, 132)',
                'rgb(75, 192, 192)',
                'rgb(255, 205, 86)',
                'rgb(201, 203, 207)',
                'rgb(54, 162, 235)'
              ]
            }]
          };
    grid: small
    background: false
  - type: chart
    title: Chart bubble example
    text: via expert mode (json)
    chart:
      type: bubble
      data:
        lang: JSON
        json: |-
          {
            datasets: [{
              label: 'First Dataset',
              data: [{
                x: 20,
                y: 30,
                r: 15
              }, {
                x: 40,
                y: 10,
                r: 10
              }],
              backgroundColor: 'rgb(255, 99, 132)'
            }]
          };
    grid: full
    background: false
  - type: chart
    title: Chart radar example
    text: via expert mode (json)
    chart:
      type: radar
      data:
        lang: JSON
        json: |-
          {
            labels: [
              'Eating',
              'Drinking',
              'Sleeping',
              'Designing',
              'Coding',
              'Cycling',
              'Running'
            ],
            datasets: [{
              label: 'My First Dataset',
              data: [65, 59, 90, 81, 56, 55, 40],
              fill: true,
              backgroundColor: 'rgba(255, 99, 132, 0.2)',
              borderColor: 'rgb(255, 99, 132)',
              pointBackgroundColor: 'rgb(255, 99, 132)',
              pointBorderColor: '#fff',
              pointHoverBackgroundColor: '#fff',
              pointHoverBorderColor: 'rgb(255, 99, 132)'
            }, {
              label: 'My Second Dataset',
              data: [28, 48, 40, 19, 96, 27, 100],
              fill: true,
              backgroundColor: 'rgba(54, 162, 235, 0.2)',
              borderColor: 'rgb(54, 162, 235)',
              pointBackgroundColor: 'rgb(54, 162, 235)',
              pointBorderColor: '#fff',
              pointHoverBackgroundColor: '#fff',
              pointHoverBorderColor: 'rgb(54, 162, 235)'
            }]
          };
    grid: small
    background: false
---

