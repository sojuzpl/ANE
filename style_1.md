[-> powrót do spisu treści](README.md)
---

## style_1.css

linia: 267 -> zmieniona klasa 'top_header' na:

```css
.top_header {
    display: block;
    width: 100%;
    height: 300px;
    background: url(../../res/baner100.jpg) no-repeat center;
}
```

linia: 10 -> zmiana definicji atrybutu 'h2' na:

```css
h2 {
    font-size: 25px;
    font-weight: 600; }
```

linia: 274 -> zmiana koloru tła na:

```css
background: #4D443C;
```

linia: 863 -> zmiana koloru tła menu na:

```css
background: #4D443C;
```

linia: 776 -> zmiana koloru tła:

```css
background-color: #F5F5F5;
```

linia: 811 -> zmiana rozmiaru fontu i koloru:

```css
.login label {
    font-size: 14px;
    /*14px;*/
    vertical-align: bottom;
    color: #4D443C;
}
```

linia: 888 -> zmiana koloru tła pola:

```css
background-color: white;
```

linia: 1007 -> zmiana wyglądu stopki:

```css
.copyright {
    padding-top: 25px;;
    text-align: center;
    font-size: 13px; 
}
```

linia: 1144 -> jak wyżej ale odnośnie linka

```css
.copyright a {
	font-weight: 600;
	color: #4D443C;
}
```

linia: 1138 -> definicja klasy 'ramka'

```css
.ramka {
    display: block;
    width: 100%;
    border-top: solid 1px #BBE0DE;
    margin: 0 0 25px 0;
    padding: 0;
}
```

linia: 918 -> zmiana koloru fontu w menu po najechaniu:

```css
.menu > li > a:hover, .menu > li > ul > li > a:hover {
    color: #BBE0DE;
    text-decoration: none;
}
```

linia: 248 -> zmiana wyglądu nagłówka tabeli

```css
.th_archive {
    background-color: #4D443C;
    color: #FFFFFF;
    padding: 15px 0px 15px 15px;
    font-size: 16px; 
    font-weight: 600; 
    text-align: left;
}
```

linia: 3601 -> zmiana wyglądu komórek tabeli

```css
table tbody td a {
	color: #4D443C;
	font-size: 16px;
	line-height: 1.8em;
}
```

linia: 3607 -> styl linku w tabeli

```css
table tbody td a:hover {
	color: #4D443C;
	text-decoration: underline;
}
```

linia: 3612 -> wyrównanie komórek tabel

```css
tr {
	vertical-align: top !important;
}
```

linia: 1017 -> zmiana wyglądu informacji o ciasteczkach i przycisku

```css
.info_cookies_container {
    padding: 0.625rem 0;
    /*10px 0px;*/
    font-size: 0.875rem;
    /*14px;*/
    line-height: 1.5rem;
    /*24px;*/
    text-align: center;
    position: fixed;
    bottom: 0;
    background-color: #4D443C;
    opacity: 1.0;
    filter: alpha(opacity=100);
    width: 100%;
    z-index: 999;
}

.info_cookies_text {
    color: #ffffff;
    opacity: 1;
    filter: alpha(opacity=100);
}

.info_cookies_link {
    color: #ffffff;
    text-decoration: underline;
}

.info_cookies_link:hover, .info_cookies_link:focus {
    color: #ffffff;
    text-decoration: underline; 
}

.info_cookies_button {
    background-color: #BBE0DE;
    padding: 0.3125rem 0.625rem;
    /*5px 10px;*/
    color: #4D443C;
    border-radius: 0.25rem;
    /*4px;*/
    -moz-border-radius: 0.25rem;
    /*4px;*/
    -webkit-border-radius: 0.25rem;
    /*4px;*/
    display: inline-block;
    margin-left: 0.625rem;
    /*10px;*/
    text-decoration: none;
    cursor: pointer; 
}

.info_cookies_button:hover {
  color: #4D443C;
  /* background: #B2D233; */
  text-decoration: underline;
}
```
