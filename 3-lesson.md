---
title: Abstracts
nav: true
---

# Abstracts
Claudio Muñoz (Universidad de Chile)
Bounds on the approximation error for deep neural networks applied to dispersive models: Nonlinear waves

We present a framework for deriving rigorous and efficient bounds on the approximation error of deep neural networks in PDE models characterized by branching mechanisms, such as waves, Schrödinger equations, and other dispersive models. This framework utilizes the probabilistic setting established by Henry-Labordère and Touzi. We illustrate this approach by providing rigorous bounds on the approximation error for both linear and nonlinear waves in physical dimensions d=1,2,3, and analyze their respective computational costs starting from time zero. We investigate two key scenarios: one involving a linear perturbative source term, and another focusing on pure nonlinear internal interactions. This is joint work with Nicolás Valenzuela.

Edit the lesson Markdown files to create content pages.

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to [simplify writing](https://evanwill.github.io/_drafts/notes/writing-markdown.html) content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub and in Jekyll.
The basics are intuitive, you can learn in about a minute!
See [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html) to get started.

When creating content pages:

- to include a page in the nav, add `nav: true` to the file's yml front matter.
- the `title:` value will appear in the nav, sorted in the order of filenames. For simplicity use leading numbers in the lesson page filenames to create correct order.
- the default layout does not add `title` to the page, so it can be a short for the nav. So add a title in the Markdown content.

## Add Figures 

Using figure include:

- put all images in the `images` directory.
- figures will be centered, and can optionally be given a caption and percentage width.
- in a markdown file where you want the image to appear, use the `figure.html` include on its own line.
- pattern: `{% raw %}{% include figure.html img="my-cat.jpg" alt="cat" caption="My cat" width="50%" %}{% endraw %}`

## Additionally 

Lorem ipsum `dolor sit amet`, consectetur adipiscing elit. Pellentesque eu velit felis. 
Duis *fermentum est nec* mollis scelerisque. 
Vivamus interdum **efficitur mauris**, et dignissim velit egestas vitae. Cras dignissim sagittis varius.
Pellentesque eu laoreet dui.
Praesent congue, eros eget accumsan euismod, lorem dui vulputate leo, tincidunt efficitur risus metus ut risus.

{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Make sure participants are on the same page!" width="75%" %}

> Sed pharetra ipsum orci, eu cursus turpis semper egestas. 
> Pellentesque sodales, felis auctor auctor rutrum, velit quam interdum erat, sit amet placerat urna nisl at justo.

## Furthermore... 

Nam maximus eget orci id pretium. Pellentesque feugiat mauris eu nulla viverra consectetur. Nullam rutrum augue eget mauris accumsan, ac elementum tellus lacinia. Sed pretium aliquet tortor in ornare. Sed eget aliquet metus. Integer sed arcu turpis. Duis auctor sollicitudin semper. Cras posuere, neque nec varius cursus, massa libero sodales elit, sed tempor nibh ex sit amet nisi. Quisque consequat ante quis diam malesuada, in imperdiet tortor mattis. Aliquam erat volutpat. Morbi tortor elit, sagittis quis nibh ut, gravida cursus arcu.

Ut dapibus lectus tristique efficitur dictum. Quisque efficitur ornare sagittis. Donec ex sem, volutpat quis scelerisque quis, scelerisque non neque. Vivamus convallis felis vel eros pulvinar faucibus. Aliquam finibus pretium odio a pharetra. Nullam ac commodo magna. Fusce et feugiat sem. Nunc vitae scelerisque metus. Aenean sodales placerat mi in aliquet. Curabitur pulvinar auctor mauris quis faucibus. Ut commodo imperdiet ante, at dignissim tellus ultricies ut. Donec at lacus ultrices sem vulputate semper. Donec commodo porta nunc, non tristique mi interdum quis. Phasellus rhoncus bibendum ipsum, ac malesuada augue pulvinar et. Etiam finibus lacus massa, sit amet faucibus lorem consequat sit amet. 
