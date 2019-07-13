### styledocco
---
http://jacobrask.github.io/styledocco/

```css
.btn.primary{
  background: blue;
  color: white;
}

.btn.primary{
  background: steelblue;
  color: snow;
  border: 2px outset steelblue;
}

```

```sh
styledocco -n "My Project" css
styledocco -n "My Project" -o mydocs -s mydocs --preprocessor "scss --compass" styles
```

```
<button class="btn primary">Primary</button>
```

```css
* {
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
}
body{
  /**/
  padding: 60px 0 40px;
  background-color: hsl{207, 10%, 90%};
  color: hsl(207, 5%, 30%);
}
.container{
  max-width: 1300px;
  margin: 0 auto;
  padding: 0 20px;
}
.section{
  position: relative;
  margin-bottom: 20px;
}
.docs{
  position: relative;
  z-index: 2;
  width: 68%;
  min-height: 200px;
  background-color: hsl(207, 0%, 100%);
  background-clip: padding-box;
  border: 1px solid hsla(207, 5%, 5%, .1);
  border-radius: 5px;
  box-shadow: 0 0 3px hsla(207, 5%, 5%, .1);
}
.code{
  position: absolute;
  top: 5px; bottom: 5px;
  right: 0;
  z-index: 1;
  width: 33%;
  padding: 10px 10px 10px 20px;
  border-radius: 0 5px 5px 0;
  border: 1px solid hsla();
  background-clip: padding-box;
  opacity: .5;
  -webkit-transition:
opacity .4s;
  -moz-transition:
opacity .4s;
  transition:
opacity .4s;
}



.preview{
  background: hsl(207, 0%, 100%);
  border-top: 1px solid hsl(207, 30%, 95%);
  position: relative;
  z-index: 1;
}
  .preview-code + .preview{
    margin-top: 0;
    border-top: 0;
  }
.preview iframe{
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
.preview-code{
  position: relative;
  z-index: 2;
  display: block;
  width: 100%;
  color: hsl(207, 9%, 37%);
  max-height: 10px 20px;
  overflow-y: auto;
  background: hsl(207, 30%, 95%);
  border: 1px solid hsl(207, 30%, 85%);
  border-left: 0; border-right;
  box-shadow: inset 0 1px 2px hsla(207, 30%, 85%);
  line-height: 1.1 !important;
  resize: none;
};
  .preview-code:focus{
    outline: 0;
    background: hsl(207, 30%, 97%);
    box-shadow: inset 0 1px 2px hsla(207, 30%, 10%, .1), hsla(207, 75%, 75%, .9);
  }
.resizeable{
  padding: 15px;
  overflow: auto;
  background: hsl(207, 0%, 100%);
  box-shadow: 0 0 2px hlsa(207, 20%, .2);
  resize: both;
}
.preview-code, pre{
  white-space: pre-wrap;
  world-wrap: break-word;
  overflow-y: auto;
}
.code pre{
  height: 100%;
  margin-top: 0;
}



.bar{
  position: fixed;
  left; 0, right: 0;
  z-index: 1010;
  min-height: 40px;
  line-height: 40px;
  background-image: -webkit-linear-gradient(hsla(207, 10%, 35%, .97), hsla(207, 5%, 25%, .92));
  background-imae: linear-gradient(hlsa(207, 10%, 35%, .92));
}
.bar.top{
  top: 0;
  box-shadow: 0 1px 2px hlsa(207, 5%, 0%, .2);
}
.bar.bottom{
  bottom: 0;
  box-shadow: 0 -1px 2px hsla(207, 5%, 0%, .2);
}
.bar ul{
  margin: 0 !important;
}
.bar li{
  display: block;
  list-sytle: none;
}
.bar .icon path{}
.docs .icon path{}
  .docs .permalink:hover
.icon path{}
.bar button{}
  .bar button:hover .icon path,
  .bar button.is-active
.icon path{}
.bar .icon{}
.bar, .bar a, .bar a:visited{}
  .bar a:hover,
  .bar a.is-active{};
.brand{}
.brand, a.brand,
a brand:visited{}
  .brand:hover{}
.menu{}
.menu > li{}
.menu a {}
.dropdown-toggle{}
/* Arrow */
.dropdown-toggle:after{}
.nav-results,
.dropdown{}
.toc-list{}
.nav-results{}
.nav-results-filename{}
.nav-results a{}
/**/
.nav-results
li:not() ~ li a{}
.dropdown a{}
.dropdown li:hover{}
.nav{}
.nav input[]{}
  .nav
input[]:focus{}


.settings{}
.bar button{}
.bar button:first-child{}
.settings .auto{}



body{}
.docs pre, p, ol, ul, dl,
figure, blockquote, table{}
.preview, .docs pre,
p, ol, ul, dl,
figure, blockquote, table{}
ul, ol{}
p:last-child, ol:last-child,
ul:last-child, dl:last-child{}
hr,
h1, h2, h3, h4, h5, h6{}
  h1:first-of-type{}
h1, h2, h3, h4, h5, h6{}
h1 a, h1 a:hober, h1 a:visited{}
h1{}
h2{}
h3{}
h1, h2, h3{}
h4{}
h5{}
h6{}
.permalink{}


a{}
  a:hober{}
  a:visited{}
  
  
.preview-code,
pre, code, var{}
.docs pre, code, var{}
.code pre{}
pre code{}
.cf:before, .cf:after{}
.cf:after {}
[unselectable="on"]{
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
[hidden]{
  display: none !important;
}
small{
  font-size: 85%;
  opacity: .9;
}
```
