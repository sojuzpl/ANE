## foundation.css

linia: 385 -> zmiana koloru tekstu na:

```css
color: #4D443C;
```

linia: 3562 -> dodana definicja klasy '_baner-row_'

```css
.baner-row {
	max-width: 100%;
  	margin-left: auto;
  	margin-right: auto;
}
```

linia: 3572 -> dodana definicja klasy '_rightSide h2_'

```css
.rightSide h2 {
	background-color: #5856D6 !important;
}
```

linia: 3583 -> schowanie znaków '>' w menu:

```css
.fa-chevron-right {
	display: none !important;
}
```

linia: 3587 -> modufikacja ikonki domku w menu

```css
.fa-home {
    font-size: 18px !important;
    padding-right: 10px;
}
```

linia: 3592 -> schowanie ikonki telefonu

```css
.fa-phone-square {
	display: none !important;
}
```

linia: 2853 -> małe litery w menu, rozmiar fontu w menu (18px)

```css
.menu {
    margin: 0; 
    list-style-type: none;
    text-transform: lowercase; 
    font-size: 18px !important;
}
```

linia: 2061 -> zmiana odstępów między elementami menu:

```css
  .menu > li > a {
    display: block;
    padding: 0.7rem 1.6rem; 
    border-right: solid 1px #BBE0DE !important;
    line-height: 1 !important; 
  }
```

linia: 3596 -> dodana definicja klasy 'accountColor a'

```css
.accountColor a {
	color: #4D443C;
	font-size: 14px;
	line-height: 25.2px;
}
```

linia: 1669 -> zmiany w wyglądzie przycisku:

```css
.button {
    display: inline-block;
    text-align: center;
    line-height: 1;
    cursor: pointer;
    -webkit-appearance: none;
    transition: background-color 0.25s ease-out, color 0.25s ease-out;
    vertical-align: middle;
    border: 0px !important; /* solid transparent;
    border-radius: 0; */
    padding: 0.35em 1.5em !important;
    margin: 0 0 1rem 0;
    font-size: 14px !important;
    background-color: #4D443C;
    color: #BBE0DE;
}

.button:hover, .button:focus {
    background-color:  #BBE0DE;
    color: #4D443C;
}
```

---
