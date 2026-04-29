---
isIndex: false
draft: false
title: Shortcodes
---
## Hugolify shortcodes

### Alert

{{< alert text="Curabitur scelerisque sollicitudin lobortis" >}}
{{< alert text="Suspendisse egestas augue a egestas consectetur" state="light" >}}
{{< alert text="Sed pharetra, massa eu varius egestas" state="warning" >}}
{{< alert text="Donec varius velit nisi, a accumsan odio molestie ut" state="info" >}}
{{< alert text="Maecenas at quam vel lorem malesuada euismod nec vel nibh" state="success" >}}
{{< alert text="Cras ac facilisis nunc" state="danger" >}}

### Alert block

{{< alert-block title="Lorem ipsum" state="info" >}}
Curabitur scelerisque sollicitudin lobortis. Sed pharetra, massa eu varius
egestas, metus nulla rutrum diam, et accumsan purus lacus vel ante.

* Suspendisse egestas augue a egestas consectetur. 
* Aliquam interdum hendrerit porta. 
* Maecenas at quam vel lorem malesuada euismod nec vel nibh. 
* Cras ac facilisis nunc.
{{< /alert-block >}}

{{< alert-block state="warning" >}}
Hugolify uses {{< blank_link link="https://github.com/twbs/bootstrap/blob/v5.3.8/scss/_variables.scss" text="Bootstrap variables" >}} and {{< blank_link link="https://github.com/Hugolify/hugolify-theme/blob/main/assets/sass/abstracts/_variables.default.sass" text="Hugolify variables" >}}.
{{< /alert-block >}}

### Badge

{{< badge state="danger" text="Danger" >}}
{{< badge state="dark" text="Dark" >}}
{{< badge state="info" text="Info" >}}
{{< badge state="light" text="Light" >}}
{{< badge state="primary" text="Primary" >}}
{{< badge state="secondary" text="Secondary" >}}
{{< badge state="success" text="Success" >}}
{{< badge state="warning" text="Warning" >}}

### Blank link

{{< blank_link text="Cras ac facilisis nunc" link="#" >}}

### Blockquote

{{< blockquote quote="Donec varius velit nisi, a accumsan odio molestie ut" >}}
{{< blockquote quote="Donec varius velit nisi, a accumsan odio molestie ut" title="Sed Pharetra" >}}
{{< blockquote quote="Donec varius velit nisi, a accumsan odio molestie ut" title="Sed Pharetra" text="Egestas augue a egestas" >}}
{{< blockquote quote="Donec varius velit nisi, a accumsan odio molestie ut" title="Sed Pharetra" text="Egestas augue a egestas" image="/images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg" >}}

### Button

{{< button url="/" text="Back home" blank=false >}}
{{< button url="/" text="External link button" blank=true >}}
{{< button url="/" text="Danger button" class="btn-danger" >}}
{{< button url="/" text="Dark button" class="btn-dark" >}}
{{< button url="/" text="Ghost button" class="btn-ghost" >}}
{{< button url="/" text="Info button" class="btn-info" >}}
{{< button url="/" text="Light button" class="btn-light" >}}
{{< button url="/" text="Link button" class="btn-link" >}}
{{< button url="/" text="Secondary button" class="btn-secondary" >}}
{{< button url="/" text="Success button" class="btn-success" >}}
{{< button url="/" text="Warning button" class="btn-warning" >}}

### Dailymotion

{{< dailymotion x9t0c4w >}}

### Details

{{< details summary="Maecenas at quam" >}}
Maecenas at quam vel lorem malesuada euismod nec vel nibh
{{< /details >}}

### Figure

{{< figure
  src="/images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg"
  alt="Alternative text"
  legend="Donec varius velit nisi, a accumsan" 
  credit="Donec varius velit nisi, a accumsan odio molestie ut"
>}}

{{< figure
  src="/images/uploads/bernd-dittrich-tfwcwynxibw-unsplash.jpg"
  alt="Alternative text"
  link="#"
  legend="Donec varius velit nisi, a accumsan"
  credit="Donec varius velit nisi, a accumsan odio molestie ut"
  class="p-2 border border-dark bg-light"
>}}

### Map

{{< map markers=`{"coordinates":[44.8425666,-0.5737107]},{"coordinates":[45.8425666,1.5937107]},{"coordinates":[46.8425666,-0.5737107]}` >}}

### Twitch

{{< twitch 2656646242 >}}

### Video

{{< video mp4="/videos/lawyerify-independent.mp4" webm="/videos/lawyerify-independent.mp4" legend="Donec varius velit nisi, a accumsan" credit="Donec varius velit nisi, a accumsan odio molestie ut" controls=true screenshot=true >}}

## Hugo shortcodes

### Highlight

{{< highlight go "linenos=table,hl_lines=8 15-17,linenostart=199" >}}
// GetTitleFunc returns a func that can be used to transform a string to
// title case.
//
// The supported styles are
//
// - "Go" (strings.Title)
// - "AP" (see https://www.apstylebook.com/)
// - "Chicago" (see https://www.chicagomanualofstyle.org/home.html)
//
// If an unknown or empty style is provided, AP style is what you get.
func GetTitleFunc(style string) func(s string) string {
  switch strings.ToLower(style) {
  case "go":
    return strings.Title
  case "chicago":
    return transform.NewTitleConverter(transform.ChicagoStyle)
  default:
    return transform.NewTitleConverter(transform.APStyle)
  }
}
{{< /highlight >}}

### QR

{{< qr text="https://gohugo.io" />}}

### Twitter

{{< x user="SanDiegoZoo" id="1453110110599868418" >}}

### Vimeo

{{< vimeo 146022717 vimeo "iframe title" >}}

### Youtube

{{< youtube id="JP8HNPKQWfI" title="Proin maximus" class="youtube" >}}
