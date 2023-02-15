+++
title = "An Introduction To Shortcodes"
date = "2023-02-15T13:11:36+10:00"
author = "Liam Ward"
tags = ["HUGO", "Shortcodes", "UNIFY"]
keywords = ["", ""]
description = "This is a Test to See what the configuration values do In The Front Matter."
showFullContent = false
readingTime = true
hideComments = false
color = "orange" #color from the theme settings
+++

This Post outlines the start of what i hope to be a small series on Exploring shortcodes in HUGO. Lets see what we can do!

Firstley i should define what a shortcode Isn't. It's not somethign that Markdown does normally, like *Italic* or **Bold** Text. `Code is also a thing` as is
```HTML
<div> Indented Code </div>
```  
Shortcodes use 2 curle braces `{{` to denote something. They each have a name and then are passed in parameters, Like embedding a youtube video.

{{< youtube vnKKNZLVh2Q>}}

Pretty cool, I Didn't need anything aside from a video ID vnKKNZLVh2Q&t to make that happen!

A Shortcodes are cool becasue thay allow you to select a piece of HTML and display it on the page. Observe the *Highlight* feature. it's like the *```* feature. But *Better*

{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

{{< highlight csharp >}}
public static void main(string[] args){
    console.WriteLine("Hello World!")
}   
{{< /highlight >}}

These Languages are useful if you want to Define Code and have it copyable, Remember, *Shortcodes are just snippits of HTML you Call to embed in a page that take inputs* You can define your own however you like!

That will be explored in Post 2 However, See you there!
