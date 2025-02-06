# HTML and CSS

Make your webpage with HTML and CSS

## 🕸 HTML

### 🔎 HTML ?

- Hyper Text Markup Language : describes content (not a "programming language")
- [1990](https://en.wikipedia.org/wiki/Tim_Berners-Lee) : Tim Berners Lee, for research papers
- .html files interpreted by web browsers (Microsoft Edge, Firefox, Chrome, Brave...)
- moteur de rendu : Chromium, Gecko
- [page minimale](http://mob.u-strasbg.fr/lab/test.html)

### 🧰 Tools

#### 🌐 Web Browser

- ctrl U (see html) , Ctrl shift i (developers tools)

#### 👓 Visual Studio Code (VScode)

- **provides** : completion, coloration...
- **extensions** : Github copilot, Live Preview, Live Server, Python...
- **AI assistant**:
  - create a Github.com account (for free version of copilot and to publish later your webpage)
  - for students and teachers Pro version is also free at : [github.com/education](https://github.com/education)
  - Online version : [vscode.dev](https://vscode.dev/)

### 🉐 Tags

- **<>** Tags
- `<tagname> ... </tagname>`
- **complete [list](https://www.w3schools.com/tags/)**
  - [`<!DOCTYPE html>`](https://www.w3schools.com/tags/tag_doctype.asp), [html](https://www.w3schools.com/tags/tag_html.asp), [head](https://www.w3schools.com/tags/tag_head.asp) ([title](https://www.w3schools.com/tags/tag_title.asp), [meta](https://www.w3schools.com/tags/tag_meta.asp), [link](https://www.w3schools.com/tags/tag_link.asp), [script](https://www.w3schools.com/tags/tag_script.asp)...), [body](https://www.w3schools.com/tags/tag_body.asp)
  - [Blocks](https://www.w3schools.com/Html/html_blocks.asp) ([div](https://www.w3schools.com/tags/tag_div.ASP),h1,p...) or [Inline](https://www.w3schools.com/Html/html_blocks.asp) (span, img, a, ...)
  - [lists](https://www.w3schools.com/html/html_lists.asp) ul, li
  - **attributes**
    - anchor [a](https://www.w3schools.com/TAGS/tag_a.asp) : `<a href="https://www.unistra.fr">Unistra</a>`
    - [img](https://www.w3schools.com/tags/tag_img.asp)  `<img src="planet.jpg" alt="my planet" width="500" height="600">`
  - [`<!-- comments -->`](https://www.w3schools.com/Html/html_comments.asp)
    - or select text and **ctrl + /**  in Visual Studio Code
  - **semantics tags** : [header](https://www.w3schools.com/tags/tag_header.asp), [main](https://www.w3schools.com/tags/tag_main.asp), [footer](https://www.w3schools.com/tags/tag_footer.asp), [nav](https://www.w3schools.com/tags/tag_nav.asp), [article](https://www.w3schools.com/tags/tag_article.asp), [section](https://www.w3schools.com/tags/tag_section.asp), [aside](https://www.w3schools.com/tags/tag_aside.asp)

## 👚 CSS

### 📰 CSS ?

- Cascading Style Sheets : describes the **presentation** (not a "programming language")
- 1996 (W3C : **separate content from presentation** easier multipages, integration)

### 🔎 [Where](https://www.w3schools.com/css/css_howto.asp) to put CSS instructions?

- [inline](https://www.w3schools.com/css/tryit.asp?filename=trycss_howto_inline) **`<HTMLtag style="">...<HTMLtag>`**
- in the [head](https://www.w3schools.com/css/tryit.asp?filename=trycss_howto_internal) section **`<style> ... </style>`**
- in an external CSS file `<link rel="stylesheet" href="style.css">`

### 📚 Examples

- Browser inspect : ctrl + shift + i (developers tools) or right click page “inspect”
- inspect and modify existing pages : [test](http://mob.u-strasbg.fr/lab/test.html) and [unistra](https://www.unistra.fr/)
- Readability extensions : [Just Read](https://chrome.google.com/webstore/detail/just-read/dgmanlpmmkibanfdgjocnabmcaclkmod?hl=en), [Mercury Reader](https://chrome.google.com/webstore/detail/mercury-reader/oknpjjbmpnndlpmnhmekjpocelpnlfdi?hl=en)...

### 🧰 In practice

 🥢 [selector](https://www.w3schools.com/cssref/sel_element.asp) {[property](<https://www.w3schools.com/cssref/>):value;}

- tag name : `a {background-color:blue;}`
- unique #id : `#myid {background-color:blue;}` ([test.html](http://mob.u-strasbg.fr/lab/test.html))
- many .class : `.myclass {background-color:blue;}`
- combining selectors : `nav a`
- tags often used for styling?
  - div (block type), span (inline type)
  - [semantics](https://www.w3schools.com/html/html5_semantic_elements.asp) (nav, header, footer, article, section, main, aside)
- [box](https://www.w3schools.com/css/css_boxmodel.asp) model
- [color](https://www.w3schools.com/colors/default.asp), background-color :- by name (blue, red...), hexa #00ff00, rgb rgb(0,0,255), color pickers
- [text](https://www.w3schools.com/css/css_text.asp) format
  - font-family : [websafe](https://www.w3schools.com/cssref/css_websafe_fonts.asp) fonts, [google](https://fonts.google.com/) fonts ([example](https://fonts.google.com/specimen/Annie+Use+Your+Telescope)), [font awesome](https://fontawesome.com/)...
  - text-decoration, letter-spacing, word-spacing...
- [images](https://www.w3schools.com/css/css3_images.asp)
  - background-image: url("paper.gif");
- [position](https://www.w3schools.com/css/css_positioning.asp), position [property](https://www.w3schools.com/css/css_positioning.asp) : [tuto](https://www.youtube.com/watch?v=jx5jmI0UlXU), [flexbox](https://www.w3schools.com/css/css3_flexbox.asp), [grid](https://www.w3schools.com/css/css_grid.asp)
- [Responsive](https://www.w3schools.com/html/html_responsive.asp) design
  - [viewport](https://www.w3schools.com/css/css_rwd_viewport.asp) `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
  - [units](https://www.w3schools.com/cssref/css_units.asp)
    - [%](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_unit_percentage) relative to parent tag
      - `<img src="img_girl.jpg" style="width:100%;">`
      - `<img src="img_girl.jpg" style="max-width:100%;height:auto;">`
    - [vw/vh](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_unit_vw) : viewport width / height
      - `<h1 style="font-size:10vw">Hello World</h1>`
  - [media query](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
    - CSS: `@media screen and (max-width: 800px) {...}`
- CSS framework
  - Helps with CSS and Responsive Design
  - Most known : [Bootstrap](https://getbootstrap.com/), [tutoriel](https://www.youtube.com/watch?v=JZ6R1PaEpww) (FR)

## 🎯 Challenges, Projects

- 🤵🏻‍♂️ Make single page website for Tim  
  - Goals (end result manually) : [HTML](http://mob.u-strasbg.fr/lab/atelier/web/indexHTML.html), [HTML/CSS](http://mob.u-strasbg.fr/lab/atelier/web/indexHTMLCSS.html), [HTML/CSS/JS](http://mob.u-strasbg.fr/lab/atelier/web/indexHTMLCSSJS.html)
  - [via copilot](https://francoisschnell.github.io/site/)
  - [tasks](https://docs.google.com/document/d/1VflA-kPei9EZjnd_qEj8sUmE9xHyMFbFBwRW6oldMmg/edit#heading=h.s1of1n1nbntb) to complete
  - Solution ... [code](https://seafile.unistra.fr/f/24f4e71ad8824c2dbc2f/)
- Modify an existing template
  - Free template [Kards](https://www.styleshout.com/free-templates/kards/) or [w3.css](https://www.w3schools.com/w3css/w3css_templates.asp)
