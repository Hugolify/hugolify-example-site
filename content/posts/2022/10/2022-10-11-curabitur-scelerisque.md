---
isIndex: false
draft: false
date: 2022-10-11T12:47:22.395Z
title: Curabitur scelerisque
description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam
  lacinia ligula non facilisis eleifend. Cras at gravida ipsum. Donec quam erat,
  fermentum nec commodo sed, tincidunt vitae nisl.
'posts/categories': Donec maximus a nulla ut feugiat
authors:
  - john-doe
tags:
  - Lorem
  - Ipsum
image:
  src: /images/uploads/bertrand-borie-tmlculvqha0-unsplash.jpg
  credit: Photo by [Bertrand
    Borie](https://unsplash.com/@bertrand1212?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
    on
    [Unsplash](https://unsplash.com/s/photos/cap-ferret?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
---

## Markdown (Heading 2)

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

Quisque vestibulum, mi eget semper laoreet, **odio quam ullamcorper turpis**, auctor fermentum magna leo eget nisi. Fusce *id imperdiet nunc*. Mauris tincidunt velit sed rhoncus tincidunt. Vestibulum vulputate odio eget risus lacinia, eget sollicitudin lectus dictum. Donec varius velit nisi, a accumsan odio molestie ut. Donec quis tristique elit. Nunc tempus tempor neque a fringilla.

* list 
* list 
* list 

Curabitur scelerisque sollicitudin lobortis. Sed pharetra, massa eu varius egestas, metus nulla rutrum diam, et accumsan purus lacus vel ante. Suspendisse egestas augue a egestas consectetur. Aliquam interdum hendrerit porta. Maecenas at quam vel lorem malesuada euismod nec vel nibh. Cras ac facilisis nunc.

## Hugolify shortcodes

### Alerts
{{< alert text="Curabitur scelerisque sollicitudin lobortis" >}}
{{< alert text="Suspendisse egestas augue a egestas consectetur" state="light" >}}
{{< alert text="Sed pharetra, massa eu varius egestas" state="warning" >}}
{{< alert text="Donec varius velit nisi, a accumsan odio molestie ut" state="info" >}}
{{< alert text="Maecenas at quam vel lorem malesuada euismod nec vel nibh" state="success" >}}
{{< alert text="Cras ac facilisis nunc" state="danger" >}}

### Buttons
{{< button url="/" text="Back home" blank=false >}}
{{< button url="/" text="External link button" blank=true >}}
{{< button url="/" text="Secondary button" class="btn-secondary" >}}

### Details
{{< details title="Maecenas at quam" text="Maecenas at quam vel lorem malesuada euismod nec vel nibh" >}}

## Hugo shortcodes

### Figure
{{< figure src="/images/uploads/sebastien-jermer-ty9wjiijyj0-unsplash.jpg" legend="Legend" >}}
{{< figure src="/images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg" alt="Alternative text" legend="Donec varius velit nisi, a accumsan" credit="Donec varius velit nisi, a accumsan odio molestie ut" >}}

### Highlight
{{< highlight go >}} A bunch of code here {{< /highlight >}}

### Twitter
{{< tweet user="SanDiegoZoo" id="1453110110599868418" >}}

### Vimeo
{{< vimeo 146022717 vimeo "iframe title" >}}

### Youtube
{{< youtube id="t9H_Jl1rc6k" title="Proin maximus" class="youtube" >}}
