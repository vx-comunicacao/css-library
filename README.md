# CSS Library
> Biblioteca com trechos reutilizáveis de códigos css/scss.

## Sumário

### C
- [center-block](https://github.com/t-components/css-library/blob/master/src/c/_center-block.scss)
- [clearfix](https://github.com/t-components/css-library/blob/master/src/c/_clearfix.scss)

### D
- [display](https://github.com/t-components/css-library/blob/master/src/d/_display.scss)

### F
- [float](https://github.com/t-components/css-library/blob/master/src/f/_float.scss)
- [font-size](https://github.com/t-components/css-library/blob/master/src/f/_font-size.scss)
- [font-weight](https://github.com/t-components/css-library/blob/master/src/f/_font-weight.scss)

### H
- [hide-text](https://github.com/t-components/css-library/blob/master/src/h/_hide-text.scss)

### I
- [img-full](https://github.com/t-components/css-library/blob/master/src/i/_img-full.scss)

### L
- [line-height](https://github.com/t-components/css-library/blob/master/src/l/_line-height.scss)
- [list-reset](https://github.com/t-components/css-library/blob/master/src/l/_list-reset.scss)

### M
- [margin](https://github.com/t-components/css-library/blob/master/src/m/_margin.scss)

### P
- [padding](https://github.com/t-components/css-library/blob/master/src/p/_padding.scss)
- [position](https://github.com/t-components/css-library/blob/master/src/p/_position.scss)
- [px-rem](https://github.com/t-components/css-library/blob/master/src/p/_px-rem.scss)

### T
- [text-align](https://github.com/t-components/css-library/blob/master/src/t/_text-align.scss)

### V
- [vertical-align](https://github.com/t-components/css-library/blob/master/src/v/_vertical-align.scss)

## CSS Funcional

Atenção

{foo} = {valor em px/rem ou escala configurada}

Requer o uso de 'breakpoints' e 'ddScale'. (_required.scss)

### font size 
[Source]([https://github.com/t-components/css-library/blob/master/src/]f/_font-size.scss)

```html
fs-{foo} | sm:fs-{foo} | md:fs-{foo} | lg:fs-{foo}

Exemplo de uso:
<p class="fs-12 sm:fs-16 md:fs-25 lg:fs-30"></p>
```

### font weight 
[Source](https://github.com/t-components/css-library/blob/master/src/f/_font-weight.scss)

```html
fw-{foo} | sm:fw-{foo} | md:fw-{foo} | lg:fw-{foo}

Exemplo de uso:
<p class="fw-100 sm:fw-300 md:fw-500 lg:fw-700"></p>
```

### line height 
[Source](https://github.com/t-components/css-library/blob/master/src/l/_line-height.scss)

```html
lh-{foo} | sm:lh-{foo} | md:lh-{foo} | lg:lh-{foo}

Exemplo de uso:
<p class="lh-12 sm:lh-16 md:lh-25 lg:lh-30"></p>
```
### display
[Source](https://github.com/t-components/css-library/blob/master/src/d/_display.scss)

```html
db | sm:db | md:db | lg:db (display: block) 
di | sm:di | md:di | lg:di (display: inline)
dib | sm:dib | md:dib | lg:dib (display: inline-block)
dt | sm:dt | md:dt | lg:dt (display: table)
dtc | sm:dtc | md:dtc | lg:dtc (display: table-cell)

Exemplo de uso:
<ul class="di"><li class="sm:di"><li></ul>
```

### vertical align 
[Source](https://github.com/t-components/css-library/blob/master/src/v/_vertical-align.scss) 

```html
vat | sm:vat | md:vat | lg:vat (vertical-align: top) 
vam | sm:vam | md:vam | lg:vam (vertical-align: middle)
vab | sm:vab | md:vab | lg:vab (vertical-align: bottom)

Exemplo de uso:
<div class="vat md:vam lg:vab"></div>
```

### floats 
[Source](https://github.com/t-components/css-library/blob/master/src/f/_floats.scss)

```html
fl | sm:fl | md:fl | lg:fl (float: left) 
fr | sm:fr | md:fr | lg:fr (float: right)
fn | sm:fn | md:fn | lg:fn (float: none)

Exemplo de uso:
<div class="fr: sm:fl lg:fn"></div>
```
### margin 
[Source](https://github.com/t-components/css-library/blob/master/src/m/_margin.scss) 

```html
mg-{foo} | sm:mg-{foo} | md:mg-{foo} | lg:mg-{foo} (margin all)  
mgt-{foo} | sm:mgt-{foo} | md:mgt-{foo} | lg:mgt-{foo}  (margin top)
mgr-{foo} | sm:mgr-{foo} | md:mgr-{foo} | lg:mgr-{foo}  (margin right)
mgb-{foo} | sm:mgb-{foo} | md:mgb-{foo} | lg:mgb-{foo}  (margin bottom)
mgl-{foo} | sm:mgl-{foo} | md:mgl-{foo} | lg:mgl-{foo}  (margin left)

Exemplo de uso:
<div class="mg-5 sm:mg-15 md:mg-25 lg:mg-50"></div>
```

### padding 
[Source](https://github.com/t-components/css-library/blob/master/src/p/_padding.scss) 

```html
pd-{foo} | sm:pd-{foo} | md:pd-{foo} | lg:pd-{foo} (padding all)  
pdt-{foo} | sm:pdt-{foo} | md:pdt-{foo} | lg:pdt-{foo}  (padding top)
pdr-{foo} | sm:pdr-{foo} | md:pdr-{foo} | lg:pdr-{foo}  (padding right)
pdb-{foo} | sm:pdb-{foo} | md:pdb-{foo} | lg:pdb-{foo}  (padding bottom)
pdl-{foo} | sm:pdl-{foo} | md:pdl-{foo} | lg:pdl-{foo}  (padding left)

Exemplo de uso:
<div class="pd-5 sm:pd-15 md:pd-25 lg:pd-50"></div>
```

### position 
[Source](https://github.com/t-components/css-library/blob/master/src/p/_position.scss) 

```html
pos-a | sm:pos-a | md:pos-a | lg:pos-a (position: absolute)
pos-r | sm:pos-r | md:pos-r | lg:pos-r (position: relative)
pos-s | sm:pos-s | md:pos-s | lg:pos-s (position: static)
pos-f | sm:pos-f | md:pos-f | lg:pos-f (position: fixed)

top-{foo} | sm:top-{foo} | md:top-{foo} | lg:top-{foo}
right-{foo} | sm:right-{foo} | md:right-{foo} | lg:right-{foo}
bottom-{foo} | sm:bottom-{foo} | md:bottom-{foo} | lg:bottom-{foo}
left-{foo} | sm:left-{foo} | md:left-{foo} | lg:left-{foo}

Exemplo de uso:
<div class="pos-f top:0 left:0 lg:pos-s"></div>
```

## Referências

- Tachyons
- Tailwind CSS
- Basscss
- Bootstrap
- Bulma