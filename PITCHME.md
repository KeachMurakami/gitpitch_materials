------------------------------------------------------------------------

external files

`root/PITCHME.yaml`

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

`root/css/PITCHME.css`

``` css
.reveal .slides section .column1 {
  float: left;
  width: 49%;
}
.reveal .slides section .column2 {
  float: right;
  width: 49%;
}
```

---?color=linear-gradient(to left, \#56ccf2, \#2f80ed) <!-- .slide: class="center" -->

background

+++?image=img/sample.png&size=contain `+++?image=img/sample.png&size=contain`

+++?image=img/sample.png&size=cover `+++?image=img/sample.png&size=cover`

---?color=linear-gradient(to left, \#56ccf2, \#2f80ed) <!-- .slide: class="center" -->

two-column

+++

    <div class="column1">
    LEFT SIDE
    </div class="column1">

    <div class="column2">
    RIGHT SIDE
    </div class="column2">

LEFT SIDE

RIGHT SIDE

---?color=linear-gradient(to left, \#56ccf2, \#2f80ed) <!-- .slide: class="center" -->

fixed position
