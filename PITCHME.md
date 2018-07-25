
```r
knitr::knit(input = "~/Dropbox/gitpitch/PITCHME.Rmd", output = "~/Dropbox/gitpitch/PITCHME.md")

system("
git add --all
git commit -m 'update'
git push -u origin master
")
```

external files

```
## root/PITCHME.yaml

# Layout
layout : top-left
# Look-and-Feel
theme : white
vertical-center : false
# additinal css theme
theme-override: css/PITCHME.css
# Plugins
mathjax : TeX-AMS_HTML-full
footnote : "© 2018 Keach Murakami"


## root/css/PITCHME.css
.reveal .slides section .column1 {
float: left;
width: 49%;
}
.reveal .slides section .column2 {
float: right;
width: 49%;
}
```

---?color=linear-gradient(to left, #56ccf2, #2f80ed)
<!-- .slide: class="center" -->

background

+++?image=img/sample1.png&size=contain
`+++?image=img/sample1.png&size=contain`

+++?image=img/sample1.png&size=50% auto
`+++?image=img/sample1.png&size=50% auto`





---?color=linear-gradient(to left, #56ccf2, #2f80ed)
<!-- .slide: class="center" -->

two-column

+++

```
<div class="column1">
LEFT SIDE
</div class="column1">

<div class="column2">
RIGHT SIDE
</div class="column2">
```

<div class="column1">
LEFT SIDE
</div class="column1">

<div class="column2">
RIGHT SIDE
</div class="column2">


---?color=linear-gradient(to left, #56ccf2, #2f80ed)
<!-- .slide: class="center" -->

image

+++

fixed position (demo)

<div style="position:relative; left:0px; top:0px; width:500px; height:500px">
<div class="fragment" data-fragment-index = "1" style="position:absolute; left:0px; top:0px; width:100%; height:100%">
![](img/sample1.png)
</div>
<div class="fragment" data-fragment-index = "2" style="position:absolute; left:0px; top:0px; width:100%; height:100%">
![](img/sample2.png)
</div>
</div>

+++

fixed position (code)

```
<div style="position:relative; left:0px; top:0px; width:500px; height:500px">
<div class="fragment" data-fragment-index = "1" style="position:absolute; left:0px; top:0px; width:100%; height:100%">
![](img/sample1.png)
@![](img/sample1.png)
</div>
<div class="fragment" data-fragment-index = "2" style="position:absolute; left:0px; top:0px; width:100%; height:100%">
# ![](img/sample2.png)
</div>
</div>
```

@[1, 8](generate fixed rectangle)
@[2-4](display the first plot using ‘fragment’)
@[5-7](display the second plot using ‘fragment’)

+++

resize (demo)

<div class="column1">
![](img/sample1.png)
</div>
<div class="column2">
<img src="img/sample1.png" width="20%">
</div>

+++

resize (code)

```
<div class="column1">
![](img/sample1.png)
</div>
<div class="column2">
<img src="img/sample1.png" width="20%">
</div>
```

work

- `<img src="img/sample1.png" width="20%">`

not work

- `![](img/sample1.png){width=20%}`




--- REFERENCES
<!-- .slide: class="center" -->
