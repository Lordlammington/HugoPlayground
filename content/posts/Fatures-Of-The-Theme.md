+++
title = "Features Of The Theme"
date = "2023-02-15T15:57:38+10:00"
author = "Liam Ward"
cover = ""
tags = ["UNIFY", "", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
+++

So, Now we've got a hang of the custom Hugo snippets done we can now go onto ones inlcluses in the theme of this site. Lets go!'

Here's the Image
{{<image src="https://www.pocruises.com/content/dam/po/inventory-assets/ports/BNE/BNE.jpg" alt="Brisvegas!"  style="border-radius: 8px;">}}
Cool, But not Amazing

{{< figure src="https://www.pocruises.com/content/dam/po/inventory-assets/ports/BNE/BNE.jpg" alt="Hello Friend" position="center" style="border-radius: 8px;" caption="Hello Friend!" captionPosition="right" >}}
Once Again, Cool But kinda Meh

{{< code language="css" title="Really cool snippet" id="1" expand="Show" collapse="Hide" isCollapsed="true" >}}
pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media (--phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }
}
{{< /code >}}
Now THIS is cool!