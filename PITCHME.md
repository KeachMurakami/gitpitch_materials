

external files

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<script type="text/javascript" src="./footerFixed.js"></script>


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

Geometry

+++

<div style="position:absolute; left:0px; top:0px; width:100%; height:3px; background-color:red">top: 0px</div>
<div style="position:absolute; left:0px; top:100px; width:100%; height:3px; background-color:red">top: 100px</div>
<div style="position:absolute; left:0px; top:200px; width:100%; height:3px; background-color:red">top: 200px</div>
<div style="position:absolute; left:0px; top:300px; width:100%; height:3px; background-color:red">top: 300px</div>
<div style="position:absolute; left:0px; top:400px; width:100%; height:3px; background-color:red">top: 400px</div>
<div style="position:absolute; left:0px; top:500px; width:100%; height:3px; background-color:red">top: 500px</div>
<div style="position:absolute; left:0px; top:600px; width:100%; height:3px; background-color:red">top: 600px</div>

<div style="position:absolute; left:0px; top:0px; width:3px; height:50px; background-color:orange"></div>
<div style="position:absolute; left:100px; top:0px; width:3px; height:150px; background-color:orange"></div>
<div style="position:absolute; left:200px; top:0px; width:3px; height:250px; background-color:orange"></div>
<div style="position:absolute; left:300px; top:0px; width:3px; height:350px; background-color:orange"></div>
<div style="position:absolute; left:400px; top:0px; width:3px; height:450px; background-color:orange"></div>
<div style="position:absolute; left:500px; top:0px; width:3px; height:550px; background-color:orange"></div>
<div style="position:absolute; left:600px; top:0px; width:3px; height:650px; background-color:orange"></div>
<div style="position:absolute; left:700px; top:0px; width:3px; height:750px; background-color:orange"></div>
<div style="position:absolute; left:800px; top:0px; width:3px; height:850px; background-color:orange"></div>
<div style="position:absolute; left:900px; top:0px; width:3px; height:950px; background-color:orange"></div>

+++?image=img/sample1.png&size=50% auto
`+++?image=img/sample1.png&size=50% auto`


---?color=linear-gradient(to left, #56ccf2, #2f80ed)
<!-- .slide: class="center" -->

Layout

+++

two column

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

+++

fixed horizontal element

```
<div style="position:absolute; top=700px; heigth:200px; color:white; background-color:orange">
Fixed Footer Text
</div>
```

<div style="position:absolute; top=700px; heigth:200px; color:white; background-color:orange">
Fixed Footer Text
</div>

+++

fixed horizontal element

<div id="footer" style="position:relative; heigth:200px; color:white; background-color:orange">
Fixed Footer Text JS
</div>

+++

fixed horizontal element

<div style="position:fixed; bottom=0; heigth:200px; color:white; background-color:orange">
Fixed Footer Text fix
</div>

+++

fixed horizontal element

<div style="position:relative; bottom=100px; heigth:200px; color:white; background-color:orange">
Fixed Footer Text
</div>

---?color=linear-gradient(to left, #56ccf2, #2f80ed)
<!-- .slide: class="center" -->

Image

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
# ![](img/sample1.png)
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
# ![](img/sample1.png)
</div>
<div class="column2">
# <img src="img/sample1.png" width="20%">
</div>
```

- <!--html_preserve-->@fa[thumbs-up]<!--/html_preserve-->: `<img src="img/sample1.png" width="20%">`

- <!--html_preserve-->@fa[thumbs-down]<!--/html_preserve-->: `![](img/sample1.png){width=20%}`


---

REFERENCES
<!-- .slide: class="center" -->
