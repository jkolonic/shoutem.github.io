---
layout: doc
permalink: /docs/ui-toolkit/components/CommonStyleNames
title: Common style names
section: UI toolkit
---

# Common style names

This section covers common style names that can be used in several UI toolkit components, and their variations.

## Size-based style name variations
* **sm** : small size, defaults to 5px.  
* **md** : medium size, defaults to 15px.  
* **lg** : large size, defaults to 30px.  
* **xl** : extra large size, defaults to 45px.  

This means that you can apply `sm-gutter` to component, for example `Tile`, and it will have 5px gutter around content.  
  
If you want to apply gutter only to specific side of component (i.e. `right`), or to vertical sides, you can specify that by using additional position style name keywords listed below.

## Position based style name variations  
* **left** : gutter will be applied only to left side of targeted component.  
* **right** : gutter will be applied only to right side of targeted component.  
* **top** : gutter will be applied only to top side of targeted component.  
* **bottom** : gutter will be applied only to bottom side of targeted component.  
* **horizontal** : gutter will be applied only to horizontal sides (left and right) of targeted component.  
* **vertical** : gutter will be applied only to vertical sides (top and bottom) of targeted component.
  
Note that on `View`, `Tile` and `Overlay` components gutter is applied as padding, while on `Text` (Typography) and `Button` components gutter is applied as margin.   
  
### rounded-corners
- This style name applies border radius (defaults to 2 px) to targeted component.  

### flexible
- This style name applies flexbox to targeted component, so that it fills parent container component.  

### inflexible
- With this style name, component is sized according to its width/height properties, but makes it fully inflexible.  

### collapsible
- This style name causes component to shrink if it overflows parent container.  

### stretch
- This style name causes component to fully fill parent container.  

Below is one example where common Style names can be used:  
<br />  

#### JSX Declaration
```JSX
<Overlay>
  <Overlay styleName="collapsed"><Heading>-20%</Heading></Overlay>
  <Title styleName="md-gutter-top">COOL BLACK AND WHITE STYLISH WATCHES</Title>
  <Subtitle styleName="line-through sm-gutter-top">$280.00</Subtitle>
  <Heading>$250.00</Heading>
  <Button styleName="md-gutter-top"><Icon name="cart" /><Text>ADD TO BASKET</Text></Button>
</Overlay>
```
